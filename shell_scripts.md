# Shell commands
`tree`

# bash
## Safer bash scripts (from twitter)
```bash
#!/usr/bin/bash
set -exuo pipefail
```
- `-e`: exit if a command fails
- `-u`: exit if a variable is undefined
- `-x`: print each script line before it is run
- `-o pipefail`: exit if a command in a pipeline fails

# Shebang

Typically you might see a hard-coded path like `#!/usr/bin/bash`. A
more general way is to use `#!/usr/bin/env bash` which will search the
`$PATH` to find the binary. However, even that is not completely
portable as `env` may be in another spot and it doesn't handle passing
command-line parameters to your program well. On StackExchange I found
this:

[http://unix.stackexchange.com/questions/29608/why-is-it-better-to-use-usr-bin-env-name-instead-of-path-to-name-as-my](Why is it better to use “#!/usr/bin/env NAME” instead of “#!/path/to/NAME” as my shebang?)

And it specifically calls out this as *the most generic* idiom.

~~~
#!/bin/sh
exec perl -x $0 "$@"
#!perl
~~~

You could do something similar with other items. Need to look into the
`-x` option for perl. Also not sure what the second shebang is for
there, but the idea seems right.


# Snippets

## bash for-loop

Here is an example which grabs a certain set of files and renames them.

```bash
for x in `ls -l *.out | grep "Dec 16" | sed 's/\t/ /g' | cut -d' ' -f 9`; do cp $x "$x.faster"; done
```

# SSH
`ssh -Tv`

