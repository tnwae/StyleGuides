# C and C++

C and C++ code written by Dreamacy Digital must follow PEP 7, with sections relevant only to the Python project
disregarded and with modifications as provided below.

Method and variable names should be spelled in snake_case.  Preprocessor macro names should be spelled in
SCREAMING_SNAKE_CASE.  Macro usage should be kept to a minimum since it induces many difficult-to-debug
behaviors.

__Code in C++ that uses multiple inheritance will not be accepted into the `trunk` branch of any Dreamacy
project for any reason.  Bjarne Stroustrup himself could submit a pull request and if it were to use multiple
inheritance, I wouldn't merge it.__

In C, I prefer that the names of structures and other custom types end in `_t`, in keeping with C library
conventions.  As a general rule, I always use named structures (as in the below), which allows self-reference
within a structure type definition, useful for trees and lists:

```c
typedef struct _node_t {
    struct _node_t *next;
    struct _node_t *prev;
    NODE_DATA_TYPE_T *value; // set by the preprocessor
} node_t;
```

Class names in C++ should be written in snake_case, in keeping with STL conventions.  All C++ code written for
Dreamacy should be enclosed within the dreamacy namespace.  If needed, C names can be munged with the `dcy_` prefix
(not `ddd` as this is a potential reference to the _Data Display Debugger_, a visual frontend to GDB).
