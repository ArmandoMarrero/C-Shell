<br>


<h1><p align="Simple-Shell">Simple_shell</h1></p></font>

## Table of Contents

- [Overview](#overview) 🌐
- [Learning Objectives](#learning-objectives) 📚
- [List of Allowed Functions and System Calls](#list-of-allowed-functions-and-system-calls) 🛠️
- [Compilation](#compilation) 🚀
- [Files](#files) 📂
- [Authors](#authors) ✒️


## Overview

This project is an implementation of a simple Unix-like shell written in C. The C-Shell provides a command-line interface where users can interact with the operating system by executing various commands. The goal of this project is to offer a basic understanding of shell functionality, process creation, and system calls.

## Learning Objectives

In this project, you will learn:

- Who designed and implemented the original Unix operating system
- Who wrote the first version of the UNIX shell
- Who invented the B programming language (the direct predecessor to the C programming language)
- Who is Ken Thompson
- How does a shell work
- What is a pid and a ppid
- How to manipulate the environment of the current process
- What is the difference between a function and a system call
- How to create processes
- What are the three prototypes of main
- How does the shell use the PATH to find the programs
- How to execute another program with the execve system call
- How to suspend the execution of a process until one of its children terminates
- What is EOF / “end-of-file”?

## List of Allowed Functions and System Calls

The following functions and system calls are allowed for this project:


    all functions from string.h
    access (man 2 access)
    chdir (man 2 chdir)
    close (man 2 close)
    closedir (man 3 closedir)
    execve (man 2 execve)
    exit (man 3 exit)
    _exit (man 2 _exit)
    fflush (man 3 fflush)
    fork (man 2 fork)
    free (man 3 free)
    getcwd (man 3 getcwd)
    getline (man 3 getline)
    getpid (man 2 getpid)
    isatty (man 3 isatty)
    kill (man 2 kill)
    malloc (man 3 malloc)
    open (man 2 open)
    opendir (man 3 opendir)
    perror (man 3 perror)
    printf (man 3 printf)
    fprintf (man 3 fprintf)
    vfprintf (man 3 vfprintf)
    sprintf (man 3 sprintf)
    putchar (man 3 putchar)
    read (man 2 read)
    readdir (man 3 readdir)
    signal (man 2 signal)
    stat (__xstat) (man 2 stat)
    lstat (__lxstat) (man 2 lstat)
    fstat (__fxstat) (man 2 fstat)
    strtok (man 3 strtok)
    wait (man 2 wait)
    waitpid (man 2 waitpid)
    wait3 (man 2 wait3)
    wait4 (man 2 wait4)
    write (man 2 write)


## Compilation

To compile the C-Shell project, use the following command:

gcc -Wall -Werror -Wextra -pedantic -std=gnu89

## Files

1. **atoi.c**
2. **errors.c**
3. **history.c**
4. **memory.c**
5. **shell_loop.c**
6. **builtin1.c**
7. **exits.c**
8. **lists1.c**
9. **parser.c**
10. **string1.c**
11. **builtin.c**
12. **getenv.c**
13. **lists.c**
14. **README.md**
15. **string.c**
16. **environ.c**
17. **getinfo.c**
18. **main.c**
19. **realloc.c**
20. **tokenizer.c**
21. **errors1.c**
22. **getLine.c**
23. **man_1_simple_shell**
24. **shell.h**
25. **vars.c**

For More Info About It Check The Man Page by
```
Username@your-regular-prompt:~$ man ./man_1_simple_shell
```

## Authors
Armando Marrero 7355@holbertonstudents.com
Ninoshka Perez 7366@holbertonstudents.com
