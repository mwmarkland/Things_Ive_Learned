# LLVM
A huge topic. But something I want to learn more about.

## Compliation Flow

### High-Level
Reading about LTO and the article had a nice high-level view of the compilation process for C/C++/Rust code. The blog post is [here](http://blog.llvm.org/2019/09/closing-gap-cross-language-lto-between.html).

The basic idea is:

`.c --clang--> .bc --LLVM--> .bc (opt) --LLVM--> .o`

clang generates un-optimized `bitcode` which is fed through LLVM to get optimized bitcode which is fed through LLVM to get "lowered" into object code.

