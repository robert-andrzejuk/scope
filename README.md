# Overview
During the C++20 cycle [P0052 Generic Scope Guard and RAII Wrapper for the Standard Library](https://wg21.link/P0052) added 4 types: scope_exit, scope_fail, scope_success and unique_resource to [LTFSv3](https://www.open-std.org/jtc1/sc22/wg21/docs/papers/2022/n4908#scopeguard).  In the intervening time, two standard libraries have implemented support as well as Boost. With the imperative for safety and security in C++ developers need every tool in the toolbox. The authors believe it is time to move this facility into the standard.  The paper will re-examine the five year old design and any learning from deployment of the LTFSv3.

For discussions of this library see:
- [Discourse for discussion of scope](https://discourse.bemanproject.org/t/scope-library/315)
# Prior And Other Work
- TS design and wording paper [p0052 - Generic Scope Guard and RAII Wrapper for the Standard Library](https://wg21.link/p0052) 
- TS adoption paper [p1411 - Please reconsider <scope> for C++20](https://wg21.link/p1411)
- pointer to GSL (todo)
- [Boost.scope](https://www.boost.org/doc/libs/1_87_0/libs/scope/doc/html/index.html)
# Examples
- [TS example of scope_exit](https://godbolt.org/z/T5KhTYjP7)
