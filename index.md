# mulle-core

The mulle-core library collection is written for C11. It is based on
[mulle-concurrent](//github.com/mulle-concurrent) and 
[mulle-c](//github.com/mulle-c). 

*mulle-core* provides functionality that is outside of the C standard libraries
but doesn't provide concurrency support. So it's a grabbag of libraries, that
is set to grow and that might be reorganized into more topical library 
collections when the need arised.

The [MulleFoundation](https://MulleFoundation.github.io) runtime is based on *mulle-core*.

Library                                                             | Description
--------------------------------------------------------------------|----------------------
[mulle-sprintf](//github.com/mulle-core/mulle-sprintf)              | An extensible sprintf function supporting stdarg and mulle-vararg
[mulle-stacktrace](//github.com/mulle-core/mulle-stacktrace)        | Stracktrace support for various OS 
[mulle-testallocator](//github.com/mulle-core/mulle-testallocator)  | C memory leak and double free checking

