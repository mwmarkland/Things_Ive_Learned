# Stuff

## Mac
`#include <OpenCL/cl.h>`

The paths look like:

```
# 1 "/System/Library/Frameworks/OpenCL.framework/Headers/cl.h" 1 3
# 28 "/System/Library/Frameworks/OpenCL.framework/Headers/cl.h" 3
# 1 "/System/Library/Frameworks/OpenCL.framework/Headers/cl_platform.h" 1 3
# 31 "/System/Library/Frameworks/OpenCL.framework/Headers/cl_platform.h" 3
```

```
/System/Library/Frameworks/OpenCL.framework/Libraries
```

IMPORTANT: *`-framework opencl`*

```
g++ -o cl_enumerate_devs cl_enumerate_devs.cc -framework opencl
```

## clinfo projects
### Mac 
Doesn't have a clinfo command built-in. Source for one is here:

https://github.com/simleb/clinfo
