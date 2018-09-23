# Operating-Systems-ECE344
Course is based on the design and implementation of operating systems software. Topics include: Introduction to operating systems concepts, process management, memory management and file systems. Time permitting, we will discuss additional topics. The laboratory exercises will require implementing software that helps understand core operating system concepts.

The source code is on a private github repository due to plagiarism issues. If you would like to request the source code for the private repo, please contact me at jeffb.liu@mail.utoronto.ca

## Lab 1
In this lab, you will review C by writing some very simple C programs. You will also write some simple data structures. These data structures will be useful for your future labs, so make sure that they work correctly. To help you, we are providing a testing framework for your programs.


## Lab 2
In this lab, you will create a library of functions that define a user-level threads package. Using your library, a program will be able to create threads, destroy them, and run them concurrently on a single processor.

Background on Threads
Threads and processes are key abstractions for enabling concurrency in operating systems. To gain a deeper understanding of how these abstractions are constructed, this project asks you to build the core of a user-level threads package. Building kernel-level threads and processes is much different, but we'll do this project at user level since installing new kernels on the lab machines is problematic.

Threads provide the illusion that different parts of your program are executing concurrently. Through the years, a model of executing multithreaded programs has emerged as a defacto standard. In this model, threads share the code, heap, and the runtime system. Each thread, however, has a separate stack and, naturally, a separate set of CPU registers. This programming model also provides synchronization primitives so that different threads can coordinate access to shared resources.
