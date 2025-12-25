
# Why study?
## Programmers always use compilers or interpreters to make computer program, with that said it is neccessary to know it's behavior.

# Purpose of comillers and interpreters.
## Convert machine code to assemply to low level programming language to high level language in order to be human friendly

# How study?
## View compilers and interpreters source code and understand it's policy or concept.

### [jdk](https://github.com/atomSS-1/jdk)
### [Node.js](https://github.com/atomSS-1/node)
### [Gcc](https://github.com/atomSS-1/gcc)
### [v8](https://github.com/atomSS-1/v8)

## watch overall comiler design.
### [MIT open courseware Computation Structures](https://ocw.mit.edu/courses/6-004-computation-structures-spring-2017/pages/c11/)

## Interpreters vs Comilers
### Thoughts: interpreters are silimar stucture as framework as compilers are built from a library
### [facts](https://chatgpt.com/s/t_68f3161c4ca881918bb15834f9c88d50)


### Compilers — Overview

A **compiler** is a program that translates **high-level source code** written by humans into **machine code** (or an intermediate form) that a computer can execute.

---

## 1. Compiler vs. Interpreter

| Aspect          | Compiler               | Interpreter              |
| --------------- | ---------------------- | ------------------------ |
| Translation     | Entire program at once | Line by line             |
| Execution speed | Faster                 | Slower                   |
| Error detection | At compile time        | At runtime               |
| Examples        | C, C++, Rust, Go       | Python, JavaScript, Ruby |

**Java** uses a hybrid approach:
source code → bytecode → JVM (interpreter + JIT)

---

## 2. Main Phases of a Compiler

1. **Lexical Analysis**

   * Converts characters into tokens
   * Example: `int x = 3;` → `int`, `x`, `=`, `3`, `;`

2. **Syntax Analysis (Parsing)**

   * Checks grammatical structure
   * Builds a parse tree or **AST (Abstract Syntax Tree)**

3. **Semantic Analysis**

   * Type checking
   * Scope and declaration checks

4. **Intermediate Code Generation**

   * Produces an **Intermediate Representation (IR)**

5. **Optimization**

   * Removes redundant computations
   * Improves performance and memory usage

6. **Code Generation**

   * Produces target machine code (x86, ARM, etc.)

---

## 3. Key Compiler Concepts

* **AST (Abstract Syntax Tree)**
  Structural representation of program logic

* **IR (Intermediate Representation)**
  Platform-independent intermediate code

* **Symbol Table**
  Stores information about variables, functions, and types

* **Optimization Levels**

  * `-O0`: no optimization
  * `-O2`: standard optimization
  * `-O3`: aggressive optimization

---

## 4. Common Compilers

| Language | Compiler           |
| -------- | ------------------ |
| C / C++  | GCC, Clang         |
| Rust     | rustc (LLVM-based) |
| Go       | gc                 |
| Java     | javac              |
| Swift    | swiftc             |
| Haskell  | GHC                |

---

## 5. Modern Compiler Trends

* Widespread use of **LLVM**
* **Just-In-Time (JIT) compilation**
* Hybrid **AOT + JIT** approaches
* **AI/ML compilers**

  * XLA
  * TVM
  * MLIR

---

## 6. Learning Path (Suggested)

1. Compiler theory (e.g., *Dragon Book*)
2. Parsing and AST construction (ANTLR)
3. LLVM IR fundamentals
4. Build a simple compiler for a toy language

---

If you want, I can also explain:

* How compilers interact with **operating systems**
* How to **build a compiler step by step**
* The role of compilers in **AI and ML frameworks**

Just let me know.







