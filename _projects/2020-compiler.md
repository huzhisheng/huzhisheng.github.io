---
title: "Compiler Project"
collection: projects
type: "contest project"
permalink: /projects/2020-compiler
venue: "Harbin Institute of Technology (Shenzhen)"
date: 2020-08-01
location: "Shenzhen"
---

Developed a compiler for ARM hardware platform, which can compile a simplified C language (Sysy2020, a custom language for the contest) into ARMv7 instructions.

Main Work
======
* Use Flex as a lexical analyzer and Bison as a parser to analyze the source code to generate an abstract syntax tree (AST).
* Convert the abstract syntax tree into an intermediate representation (IR), and do some machine-independent optimizations on this basis.

Technology
======
* C++
* Flex and Bison
* Compilation optimization techniques