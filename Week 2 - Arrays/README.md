# Week 2 - Arrays

[Link to project page](https://cs50.harvard.edu/x/2025/psets/2/)

## Notes from lecture

### Compiling
Compilers turn code into 0s and 01s \
When we are using _make-_ in the terminal we're using a compiler \
A common compiler is **clang**, but it names programs 'a.out' by default \
So if we use
> clang hello.c

we get a program named \
> a.out 

#### Arguments
Arguments are inputs to a program. Clang supports additional arguments at command line, so we can name out programs. \
So if we use
> clang -o hello hello.c

we get 
> hello 
