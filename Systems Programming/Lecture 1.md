---
tags:
  - SP
  - Lecture
---
Lecture 1 | 25/09/23
:-- | --:

---
## Structured Programming Introduction

---
### Programming Paradigms
- Imperative
- Structured
- Object Orientated
- Functional

### Advantage
System languages aim to allow developers to make accurate assumptions on memory usage and time complexity. This helps develop efficient code. 

### Compiling
This course will use clang as compiler.

---
	stages
		- preprocessor (expands ```#include <stdio.h or #define PI 3.14```)
		- intermediate phase will optimise code
		- machine specific assembly generated
		- machine code made in object file
	- ```clang source.c -o program```
	- ```./program```

```clang source.c -E -o source.e```
generates code at the processor stage

```clang source.c -emit-llvm -S source.llvm```
generates intermediate phase code

```clang source.c -S source.s```
generates machine code