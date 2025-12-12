# JIT Compiler

A simple Just-In-Time compiler that generates and executes x86 machine code at runtime.

## Features
- Runtime code generation
- Arithmetic operations (add, sub, mul)
- Stack-based expression evaluation
- Direct execution of generated code

## Building
```bash
gcc -o jit jit.c -Wall -Wextra -m32
./jit
```

## Example
Generates machine code for expressions like `(5 + 10) * 2` and executes them directly on the CPU.

## Status
✓ Phase 1: Code generation and execution (COMPLETE)
⏳ Phase 2: Parser (next)
⏳ Phase 3: Full expression evaluator
