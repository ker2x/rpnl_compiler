# RPNL : The reverse polish notation language

_It's a good thing that it doesn't works, because it's not ready for production._
-- Me, October 2021

## Basic rules

* It's all about speed, math & speed
* When in doubt about a syntax or rule, look at RPL first and then Fortran (not Forth)
* 64 bits, possibly arbitrary precision in the future.
* Everything is postfix, except when it's not
* the "#" sign is reserved (include, pragma, who knows ?)
* integers are : int64_t as defined in cstdint
* unsigned integer are : uint64_t as defined in cstdint
* floating points are : double
* a bool is a bool
* An interactive shell is planned but it may be discontinued later.

---

## Candidate for ext library

### logging
* glog for log : https://github.com/google/glog

### profiling & benchmarks
* google-benchmark : https://github.com/google/benchmark

### testing
* google-test : https://github.com/google/googletest

### maths
* https://github.com/google/ruy : ruy for matrix multiplication (inactive?)
* https://github.com/google/mathfu : for "fast math", not sure (developed primarily for games) (abandoned?)
* https://gitlab.com/libeigen/eigen : Eigen is a C++ template library for linear algebra
* https://github.com/limeoats/BigNumber BigNumber is a C++ class that allows for the creation and computation of arbitrary-length integers.
* http://oprecomp.eu/ : arbitrary low precision thingy


### database
* support for sqlite probably make sense
* i might as well support postgresql too
* mysql can die in a fire

### file format (data, image, ...)

* image : png ? ppm ? jpg ? tga ? tiff ? ... ?
* data : json ? yaml ? xml (eww) ?

### large library

* https://www.boost.org/ : everything
* https://abseil.io : Abseil is an open source collection of C++ libraries drawn from the most fundamental pieces of Google’s internal codebase.
* https://github.com/facebook/folly : Folly contains a variety of core library components used extensively at Facebook.


### misc
* https://github.com/gflags/gflags : a library for parsing commandline argument (abandoned?)
* https://github.com/fmtlib/fmt {fmt} is an open-source formatting library providing a fast and safe alternative to C stdio and C++ iostreams.
* https://github.com/r35382/bnflite BNFLite is a C++ template library for lightweight flexible grammar parsers.

---

## random links and stuff



### tutorials

* https://llvm.org/docs/tutorial/
* https://cmake.org/cmake/help/latest/guide/tutorial/index.html
* https://www.youtube.com/watch?v=m8G_S5LwlTo : LLVM IR Tutorial

### References
* https://en.wikipedia.org/wiki/RPL_(programming_language)
* https://en.wikipedia.org/wiki/Cache-oblivious_algorithm
* https://llvm.org/docs/CompilerWriterInfo.html
* https://llvm.org/docs/Reference.html LLVM API reference
* https://llvm.org/docs/LangRef.html : LLVM IR reference

### LLVM based compilers
* https://github.com/saturn597/RPN/blob/master/rpn.cpp
* https://github.com/c3lang/c3c

### tools
* https://www.sonarsource.com/products/sonarlint/ : Sonar Linter