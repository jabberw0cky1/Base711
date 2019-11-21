jabberw0cky1 , 17.11.2019 , Base 711


"Base711" is meant as basement for creation and maintaining of and operating with some objects hierarchy. 

Objects must have abilities of:
1. having persistent unique identity as class
2. ownership in tree relations (parents-children)
3. "horizontal" relations
4. serialization and restoration as a whole structure (with all their data and relations between them).

General expected features: 
1. Code minimalism for future reuse
2. Execution time processor and RAM resources economy
3. Shortness of serialized representation.

Infrastructure utilities must also be implemented:
1. CLI processor as HUI
2. Files as storage for serialized representation, so file I/O routines
3. C++ specific memory management (maybe ref counting).

That's all.
