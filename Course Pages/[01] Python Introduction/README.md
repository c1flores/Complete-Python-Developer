<!-- omit in toc -->
# Complete Python Developer
<!-- omit in toc -->
## Table of Contents
- [What is a Programming Language](#what-is-a-programming-language)
- [Python Interpreter](#python-interpreter)
- [How to Run Python Code](#how-to-run-python-code)
- [Latest Version of Python](#latest-version-of-python)
- [Our First Python Program](#our-first-python-program)
- [Python2 vs, Python3](#python2-vs-python3)
- [Why So Many Languages](#why-so-many-languages)

<br />

## What is a Programming Language
In the journey of becoming a Python developer, it's crucial to understand the fundamental question: What is a programming language? At its core, a programming language is a set of instructions that can be understood by a computer. It's a bridge between human logic and machine operations, enabling us to communicate complex ideas and algorithms in a way that machines can execute.To appreciate this bridge, imagine you have an idea or a task you wish to accomplish—like finding flights to Bali. You know what you want to do, but how do you communicate this to a computer?

<br />


This is where programming languages like Python and Java come into play. They allow us to write instructions in a human-readable form, which are then translated into a language that the computer's processor can understand. This computer-readable language is often referred to as "bytecode" or machine code, which consists of binary digits (0s and 1s) arranged in a specific sequence that represents our original instructions. The conversion from human-readable code to machine code happens through one of two primary methods: interpretation or compilation.

<br />


![](https://github.com/c1flores/Complete-Python-Developer/assets/81927296/4c0e3b69-2a2b-4f5b-82ae-ec8af25eb5b2)

<br />

An interpreter takes the code you write and reads it line-by-line, executing it on the fly. It's like having a live translator who interprets your English into another language in real-time during a conversation.On the other hand, a compiler translates the entire set of code into machine code before execution, like someone translating a whole book into another language before anyone reads it.

<br />

![](https://github.com/c1flores/Complete-Python-Developer/assets/81927296/21b58e65-13d6-4ccf-922e-ace46a6be603)

<br />


Each method has its advantages and trade-offs. Interpreted languages, like Python, are generally more flexible and easier to debug since you can run and test your code as you write it. However, this might come with a performance cost. Compiled languages, like Java, might take more time upfront to translate the code, but the resulting machine code is often faster to execute.

<br />


So, when we write code in high-level languages, we are essentially giving the computer a set of high-level instructions. These are then broken down into the low-level commands that the machine can act upon, allowing our original idea—such as finding flights—to be carried out effectively by the computer.As we progress through this course, we'll delve deeper into how Python works, both as a language and within the ecosystem of development tools, to turn your ideas into executable programs.

<br />


## Python Interpreter
In this module, we're going to dive into how the Python interpreter works. When you decide to start working with Python, the first step is to download the interpreter. This is a program that will read and execute your Python code. Although we call it the "Python interpreter," what we're actually downloading is a specific implementation of the Python language called CPython, which is written in the C programming language.

<br />

![](https://github.com/c1flores/Complete-Python-Developer/assets/81927296/ce45eea1-7849-4133-8d79-d0b700698ea8)

<br />

This is the official and most widely used Python interpreter. It not only interprets the Python code but also compiles it into a bytecode.

<br />

![](https://github.com/c1flores/Complete-Python-Developer/assets/81927296/facf8c4c-19ee-4a4e-aaaf-051b5663435e)

<br />

When you write Python code, you're writing a set of instructions in a syntax that is readable to humans and conforms to the rules of the Python language. Once you run your Python script, the CPython interpreter kicks in and does a few things under the hood:

<br />

1. Lexical Analysis: The interpreter reads your Python code, breaking it down into tokens—these are the language syntax elements like keywords, operators, and identifiers.

<br />

2. Parsing: The tokens are then assembled into a structure that represents the instructions in a way that the interpreter can understand. This structure is called the Abstract Syntax Tree (AST).

<br />

3. Compilation: The AST is compiled into bytecode. Bytecode is a low-level set of instructions that is not human-readable, but it's also not binary machine code. It's a middle ground that's specific to Python.

<br />

4. Interpretation: Finally, the bytecode is sent to the Python Virtual Machine (PVM), which is part of the CPython interpreter. The PVM is an emulation of a computer, and it reads and executes the bytecode.

<br />

![](https://github.com/c1flores/Complete-Python-Developer/assets/81927296/a1a801a6-4dd2-48a3-929c-25bbf06f4480)

<br />

The PVM executes the bytecode in a step-by-step manner. Each bytecode instruction is translated into one or more machine code instructions that the computer's processor understands. This is done through a process called "just-in-time" compilation or JIT, which compiles the bytecode to machine code on the fly. This process happens each time you run a Python script, which means that Python is an interpreted language, as opposed to a compiled one like C or Java, which compiles down to machine code before the program is run for the first time.


<br />

Understanding how the interpreter works is essential because it affects how you write and debug your programs. It explains why Python might be slower than languages like C, which are compiled ahead of time to machine code, but also why it's more flexible and easier to work with for rapid development and prototyping.

<br />



## How to Run Python Code

## Latest Version of Python

## Our First Python Program

## Python2 vs, Python3

## Why So Many Languages



