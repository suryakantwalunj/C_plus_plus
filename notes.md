> ### Headers Should Not Include using Declarations
> Using declaration should not come inside header file since header files get included in everywhere.

> ### Exception and Error Handling
> - Exception is an error handling mechanism.
> - C++ exceptions are designed to support error handling.


> ### Forward references
> Forward references enable perfect forwarding which means the ability to pass arguments by maintaining their value category.
> Forwarding references allow a reference to bind to either an lvalue or rvalue depending on the type. Forwarding references follow the rules of reference collapsing:
> - T& & becomes T&
> - T& && becomes T&
> - T&& & becomes T&
> - T&& && becomes T&&
