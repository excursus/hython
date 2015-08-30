#hython

A Python 3 interpreter implemented in Haskell.

The goal of this project is to become more familiar with Haskell. It is not to produce a replacement for CPython or PyPy. I would like to implement as much of the core language as I can. While I list features out below, they're more for me to remember what I have remaining in each part of the project.

## Features

### Lexical Analysis

 * [x] Line comments
 * [x] Significant indentation
 * [x] Integer literals
 * [x] Floating point literals
 * [x] Imaginary literals
 * [x] Single quoted string literals
 * [x] Double quoted string literals
 * [x] Triple quoted string literals
 * [x] String escape sequences
 * [x] Byte literals
 * [x] All operators, delimiters, and keywords
 * [x] Implicit line joining in collections
 * [x] Explicit line joining via `\\`

### Parsing

 * [x] Scalar literals
 * [x] Adjacent string literal concatenation
 * [x] Function calls
 * [x] Attribute access
 * [x] Tuples
 * [x] List literals
 * [x] List comprehensions
 * [x] Dictionary literals
 * [x] Decorators
 * [x] Subscript operators
 * [x] Set literals
 * [x] All arithmetic operators
 * [x] All bitwise operators
 * [x] All boolean operators
 * [x] All comparison operators
 * [x] `assert` statement
 * [x] `break` statement
 * [x] `class` statement
 * [x] `def` statement
 * [x] `del` statement
 * [x] `for` statement
 * [x] `global` statement
 * [x] `if`/`elif`/`else` statements
 * [x] `import` statement (and friends)
 * [x] `lambda` statement
 * [x] `nonlocal` statement
 * [x] `pass` statement
 * [x] `raise` statement
 * [x] `return` statement
 * [x] `try` statement
 * [x] `while` statement
 * [x] `with` statement
 * [x] `yield` statement
 * [x] Keyword arguments to functions
 * [x] Default arguments to functions

### Interpreter

 * [x] `print` built-in function
 * [x] Variable assignment and retrieval
 * [x] Loop control flow
 * [x] Function control flow
 * [x] Scoping (basic)
 * [x] Functions
 * [x] Classes
 * [x] `global` statement
 * [x] `nonlocal` statement
 * [x] `lambda` expressions
 * [ ] Inheritance
 * [ ] Modules
 * [x] Exception handling
 * [ ] Generators
 * [ ] Standard built-in functions
 * [ ] Built-in exception types

## Running

1. Install [Stack](https://github.com/commercialhaskell/stack)

2. Clone the repository:

        $ git clone https://github.com/mattgreen/hython.git
        $ cd hython

3. Build:

        $ make

4. Run automated test suite:

        $ make test

## Reference
 * [Python 3.4 Language Reference](https://docs.python.org/3.4/reference/)
 * [Alex + Happy Whitespace Handling](https://github.com/jmoy/alexhappy)
 * [berp](https://github.com/bjpop/berp)
 * [Language.Python](https://github.com/bjpop/language-python)
