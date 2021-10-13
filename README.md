# RPNL : The reverse polish notation language

_It's a good thing that it doesn't works, because it's not ready for production._
-- Me, October 2021

## Basic rules

* It's all about speed, math & speed
* When in doubt about a syntax or rule, look at RPL and Fortran, not Forth
* https://en.wikipedia.org/wiki/RPL_(programming_language)
* 64 bits, possibly arbitrary precision in the future.
* Everything is postfix, except when it's not
* the "#" sign is reserved (include, pragma, who knows ?)
* integers are : int64_t as defined in cstdint
* unsigned integer are : uint64_t as defined in cstdint
* floating points are : double
* a bool is a bool
* An interactive shell is planned but it may be discontinued later.

## Candidate for ext library

* glog for log
* google-benchmark
* google-test for testing, and because google benchmark require it
* ruy for matrix multiplication
* need a library for parsing commandline argument
* perhaps mathfu, for "fast math", not sure
* I don't want to use boost but it would be nice to have boost. Argh.
* gflags, for commandline parsing ?
* Eigen is a C++ template library for linear algebra
* FloatX, or Float eXtended, is a header-only library for low-precision, floating point type emulation.
* sqlite

## random links and ressources and more libs

* https://llvm.org/docs/tutorial/
* https://en.wikipedia.org/wiki/RPL_(programming_language)
* https://github.com/saturn597/RPN/blob/master/rpn.cpp
* https://en.wikipedia.org/wiki/Cache-oblivious_algorithm
* https://cmake.org/cmake/help/latest/guide/tutorial/index.html
* http://oprecomp.eu
* https://abseil.io Abseil is an open source collection of C++ libraries drawn from the most fundamental pieces of Google’s internal codebase.
* https://github.com/facebook/folly Folly (acronymed loosely after Facebook Open Source Library)
* https://github.com/limeoats/BigNumber BigNumber is a C++ class that allows for the creation and computation of arbitrary-length integers.
* https://github.com/fmtlib/fmt {fmt} is an open-source formatting library providing a fast and safe alternative to C stdio and C++ iostreams.
* https://github.com/r35382/bnflite BNFLite is a C++ template library for lightweight flexible grammar parsers.
* 