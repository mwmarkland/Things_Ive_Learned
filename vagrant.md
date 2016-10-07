# Vagrant stuff.

## Vagrant with ansible.

Vagrant allows for provisioning via Ansible. It is really easy to setup
and allows you to name the type of machine, and point to a specific playbook. You can also do cool things like this:

```Ruby
# Vagrantfile
worker.vm.provision "ansible" do |ansible|
# ansible.verbose = "v"
ansible.playbook = "../ansible/vagrant_ambari.yml"
ansible.limit = "data"
ansible.extra_vars = { vagrant: 'true' }
```

And then put this in your Ansible task to select which version
to run.

```YAML
when: not vagrant
```
 or
 
 ```YAML
 when: vagrant
 ```
