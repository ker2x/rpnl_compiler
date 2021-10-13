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
* 