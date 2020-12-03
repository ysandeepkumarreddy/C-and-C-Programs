# C-and-C++Programs

This Reposistory is created for practice purpose who are new to **C & C++**

## What is C?
C is a general-purpose, procedural computer programming language supporting structured programming, lexical variable scope, and recursion, with a static type system. By design, C provides constructs that map efficiently to typical machine instructions


## What is C++?
C++ is a powerful general-purpose programming language. It can be used to develop operating systems, browsers, games, and so on. C++ supports different ways of programming like procedural, object-oriented, functional, and so on. This makes C++ powerful as well as flexible.

## Benefits of C language over other programming languages
C is a middle-level programming language developed by Dennis Ritchie during the early 1970s while working at **AT&T Bell Labs in the USA.** The objective of its development was in the context of the re-design of the UNIX operating system to enable it to be used on multiple computers.

Earlier the language B was now used for improving the UNIX system. Being a high-level language, B allowed much faster production of code than in assembly language. Still, B suffered from drawbacks as it did not understand data-types and did not provide the use of “structures”.

These drawbacks became the driving force for Ritchie for development of a new programming language called C. He kept most of language B’s syntax and added data-types and many other required changes. Eventually, C was developed during 1971-73, containing both high-level functionality and the detailed features required to program an operating system. Hence, many of the UNIX components including UNIX kernel itself were eventually rewritten in C.

## Benefits of C language
1. As a middle-level language, C combines the features of both high-level and low-level languages. It can be used for low-level programming, such as scripting for drivers and kernels and it also supports functions of high-level programming languages, such as scripting for software applications etc.
2. C is a structured programming language which allows a complex program to be broken into simpler programs called functions. It also allows free movement of data across these functions.
3. Various features of C including direct access to machine level hardware APIs, the presence of C compilers, deterministic resource use and dynamic memory allocation make C language an optimum choice for scripting applications and drivers of embedded systems.
4. C language is case-sensitive which means lowercase and uppercase letters are treated differently.
5. C is highly portable and is used for scripting system applications which form a major part of Windows, UNIX, and Linux operating system.
6. C is a general-purpose programming language and can efficiently work on enterprise applications, games, graphics, and applications requiring calculations, etc.
7. C language has a rich library which provides a number of built-in functions. It also offers dynamic memory allocation.
8. C implements algorithms and data structures swiftly, facilitating faster computations in programs. This has enabled the use of C in applications requiring higher degrees of calculations like MATLAB and Mathematica.
9. Riding on these advantages, C became dominant and spread quickly beyond Bell Labs replacing many well-known languages of that time, such as ALGOL, B, PL/I, FORTRAN, etc. C language has become available on a very wide range of platforms, from embedded microcontrollers to supercomputers.

# Compiling on windows 10?
## [Turbo C++](https://github.com/vineetchoudhary/turbocpp/releases/download/v3.2/Turbo.C.3.2.zip?raw=true)  <-- Download

# Run a C/C++ program on terminal using gcc compiler

## Follow these steps to run programs on terminal:

**Step 1.** Open terminal.

**Step 2.** Type command to install gcc or g++ complier:
```
$ sudo apt-get install build-essential
```
This will install the necessary C/C++ development libraries for your Ubuntu to create C/C++ programs.

To check gcc version type this command:
```
$ gcc –version or gcc –v
```
**Step 3.** Open a file using any editor.
```
$ sudo gedit first.c (for C programs)
```
```
$ sudo gedit hello.cpp (for C++ prgrams)
```
**Step 4.** Write the Code on Text Editor

**Step 5.** Save the file and exit.

**Step 6.** Compile the program using any of the following command:

(i). Compiling C program.
```
$ sudo gcc first.c
```
It will create an executable file with “.out” extension named as “a.out”.

Or
```
$ sudo gcc –o first first.c
```
Where first is the executable or object file of first.c program.

(ii). Compiling C++ program.
```
$ sudo g++ hello.cpp 
```
(or)
```
$ sudo g++ -o hello hello.cpp
```
[Note: Make sure you are in the same directory where you have created your program before compiling it.]

**Step 7.** To run this program type this command:

(i). For running C program
```
$ ./a.out (If you compiled using first command)
```
Or
```
$ ./first (If you compiled using second command)
```
(ii). For running C++ program
```
$ ./a.out (If you compiled using first command)
```
Or
```
$ ./hello (If you compiled using second command)
```
It will show output on the terminal.


### Try this. All the best!!!

