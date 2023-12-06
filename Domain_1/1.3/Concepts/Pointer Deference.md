An attack that consists of finding null references in a target program and [[Derefence|dereferencing]] them, causing an exception to be generated.

The vulnerability in memory that usually causes the applications to crash or a denial of service is a **NULL Pointer dereference.**

In this case, there is **nothing at that memory address** to dereference (it is empty, or NULL) and the application crashes

BEST DEFENSE → Good coding. Code should be check to make sure it is null before [[Derefence|dereferencing]] it.