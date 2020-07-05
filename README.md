## Prerequisites

https://clang.llvm.org/docs/LibASTMatchersTutorial.html

## How to build

```
export LLVM_DIR=<PATH_TO_LLVM>
cmake -H. -Bbuild -DCMAKE_EXPORT_COMPILE_COMMANDS=ON -GNinja
cmake --build build
```
