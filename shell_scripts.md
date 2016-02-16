* Shebang

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

