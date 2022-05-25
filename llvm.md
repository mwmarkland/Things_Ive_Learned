# LLVM
A huge topic. But something I want to learn more about.

## General Hints/Notes
- clang is, by default, heavily tied to UTF-8 as its input file format.

## Build hints
### How to compile an out-of-tree LLVM program without using any sort of build system
  g++ test.cpp -O `llvm-config -cxxflags` `llvm-config --ldflags` `llvm-config --libs`

## Compliation Flow

### High-Level
Reading about LTO and the article had a nice high-level view of the compilation process for C/C++/Rust code. The blog post is [here](http://blog.llvm.org/2019/09/closing-gap-cross-language-lto-between.html).

The basic idea is:

`.c --clang--> .bc --LLVM--> .bc (opt) --LLVM--> .o`

clang generates un-optimized `bitcode` which is fed through LLVM to get optimized bitcode which is fed through LLVM to get "lowered" into object code.

## Education Resources
### Machine Level Stuff
[2017 LLVM Developers’ Meeting: M. Braun “Welcome to the back-end: The LLVM machine representation”](https://www.youtube.com/watch?v=objxlZg01D0)
[2017 LLVM Developers’ Meeting: J. Bogner & A. Nandakumar & D. Sanders “Tutorial: GlobalISel ”](https://www.youtube.com/watch?v=Zh4R40ZyJ2k)
