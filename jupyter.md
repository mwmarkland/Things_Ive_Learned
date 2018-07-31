# Invocation

jupyter allows you to pass options to the underlying implementation. This is an example from my work at Mayo where I had large notebooks that wouldn't get saved without increasing the `max_body_size` and `max_buffer_size` values.

```
jupyter notebook --NotebookApp.iopub_data_rate_limit=100000000 --NotebookApp.tornado_settings="{'max_body_size': 104857600, 'max_buffer_size': 104857600}" ~/git_repos/cra-data-review/python/pkg_cra/notebooks/
```

# Version Control
By default notebooks have the output in base64 encoded blobs which can make merging and diffing difficult. Some ideas here:

[Jupyter Notebook Best Practices for Data Science](https://www.svds.com/jupyter-notebook-best-practices-for-data-science/)

# Getting a kernel into Jupyter.
This is how I got my own kernel usable from the global Jupyter install:

Basic docs are here: https://ipython.readthedocs.io/en/stable/install/kernel_install.html

I was on a machine with a base python and jupyter install running and available and I wanted to point to an Anaconda environment I had created as a kernel. So I looked at the following

```
nid00030:~/.jupyter> jupyter --json --paths
{"runtime": ["/run/user/12826/jupyter"], "data": ["/home/users/markland/.local/share/jupyter", "/usr/local/share/jupyter", "/usr/share/jupyter"], "config": ["/home/users/markland/.jupyter", "/usr/etc/jupyter", "/usr/local/etc/jupyter", "/etc/jupyter"]}
```

So there is a local directory in the jupyter search path. I then dug on the internet and found the website above. I did the following: 

Activate my Anaconda python install by putting it in the PATH.
```
nid00030:~/.local/share/jupyter/runtime> source ~/bin/setup_anaconda.sh
```
Activate my conda environment.
```
nid00030:~/.local/share/jupyter/runtime> source activate cra_tools
```

Run the ipython command to install a kernel.
```
(cra_tools) nid00030:~/.local/share/jupyter/runtime> python -m ipykernel install --user --name cra_tools --display-name "Python3 (cra_tools)"
Installed kernelspec cra_tools in /home/users/markland/.local/share/jupyter/kernels/cra_tools
```
