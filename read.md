## Modern C++ topics 
* https://github.com/AnthonyCalandra/modern-cpp-features
### RAII
* https://en.cppreference.com/w/cpp/language/raii
* https://en.wikipedia.org/wiki/Resource_acquisition_is_initialization#:~:text=Resource%20acquisition%20is%20initialization%20(RAII,describe%20a%20particular%20language%20behavior.
* https://www.tomdalling.com/blog/software-design/resource-acquisition-is-initialisation-raii-explained/
### Smart Pointers

### Exceptions and Error Handling
* https://isocpp.org/wiki/faq/exceptions
* https://www.drdobbs.com/when-and-how-to-use-exceptions/184401836

## C++11 topics

_"If you're an experienced C++ programmer and are anything like me, you initially approached C++11 thinking, "Yes, yes, I get it. It's C++, only more so." But as you learned more, you were surprised by the scope of the changes. **auto** declarations, range-based **for** loops, **lambda** expressions, and **rvalue references** change the face of C++, to say nothing of the new **concurrency** features. And then there are the idiomatic changes. **0** and **typedefs** are out, **nullptr** and **alias** declarations are in. **Enums** should now be scoped. **Smart pointers** are now preferable to built-in ones. Moving objects is normally better than copying them."_ - Effective Modern C++ by **Scott Meyers**

* https://www.freecodecamp.org/news/some-awesome-modern-c-features-that-every-developer-should-know-5e3bf6f79a3c/

### rvalue
_"C++11's most pervasive feature is probably move semantics, and the foundation of move semantics is distinguishing expressions that are rvalue from those that are lvalues. That's because rvalues indicate objects eligible for move operations, while lvalues generally don't. In concept (though not always in practice), rvalue correspond to temporary objects returned from functions, while lvalues correspond to objects you can refer to, either by name or by following a pointer or lvalue reference."
"A useful heuristic to determine whether an expression is an lvalue is to ask if you can take its address. If you can, it typically is. If you can't, it's usually an rvalue." -Effective Modern C++_

* https://www.bogotobogo.com/cplusplus/C11/4_C11_Rvalue_Lvalue.php
* https://docs.microsoft.com/en-us/cpp/cpp/lvalues-and-rvalues-visual-cpp?view=msvc-170
* https://www.internalpointers.com/post/understanding-meaning-lvalues-and-rvalues-c

### typedef vs using
* https://www.educba.com/c-plus-plus-using-vs-typedef/
* https://www.nextptr.com/tutorial/ta1193988140/how-cplusplus-using-or-aliasdeclaration-is-better-than-typedef
