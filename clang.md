# clang Information

## AST
[Documentation](https://clang.llvm.org/docs/IntroductionToTheClangAST.html)

```
# Clang by default is a frontend for many tools; -Xclang is used to pass
# options directly to the C++ frontend.
$ clang -Xclang -ast-dump -fsyntax-only test.cc
```
