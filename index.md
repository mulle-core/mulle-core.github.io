# mulle-core

The mulle-core library collection is written for C11.

*mulle-core* provides functionality that is outside of the C standard libraries.
These libraries are not strictly concerned with concurrency like mulle-concurrent is,
but may use features of mulle-concurrent. So *mulle-core* is a grabbag of libraries, that
is set to grow and that might get reorganized into more topical library 
collections later on.

Library                                                             | Description
--------------------------------------------------------------------|----------------------
[mulle-atexit](//github.com/mulle-core/mulle-atexit)                | A workaround for deficient c-library implementations
[mulle-sprintf](//github.com/mulle-core/mulle-sprintf)              | An extensible sprintf function supporting stdarg and mulle-vararg
[mulle-stacktrace](//github.com/mulle-core/mulle-stacktrace)        | Stracktrace support for various OS 
[mulle-testallocator](//github.com/mulle-core/mulle-testallocator)  | C memory leak and double free checking


*mulle-core* is based on [mulle-concurrent](//github.com/mulle-concurrent) and 
[mulle-c](//github.com/mulle-c). 

The [MulleFoundation](https://MulleFoundation.github.io) is based on *mulle-core*.

