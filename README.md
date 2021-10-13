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

## random links and ressources

* https://llvm.org/docs/tutorial/
* https://en.wikipedia.org/wiki/RPL_(programming_language)
* https://github.com/saturn597/RPN/blob/master/rpn.cpp
* https://en.wikipedia.org/wiki/Cache-oblivious_algorithm
* https://cmake.org/cmake/help/latest/guide/tutorial/index.html