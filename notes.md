
# Internal Notes intended for contributors to / authors of this book

## Structure

### Getting Started

* Why use MeTTa?
* Getting the interpreter installed and running (Should we put this at the end of the book, since the code examples will inline-executable?)
* Additional Resources, MeTTa spec, etc.

### MeTTa basics

Build to "shopping list" example. Reorganize this section if appropriate.

* Symbols & Expressions
* Matching
* Unification / Graph Rewriting
* Types in MeTTa

### Grounded Atoms

* Executable Atoms
* Custom Matching
* Standard Atom Library

### Inference

* TBD

### Probabalistic Primitives

* TBD

### Embedding & Extending MeTTa

* Rust Interface
* C Interface
* Python Interface

## Notes for inline-executable MeTTa code, within book

Plan is to try and use CZ interpreter, compiled to Javascript, executed in browser.

Notes for embedding non-rust 

For executing JS inline, look here for an issue: https://github.com/rust-lang/mdBook/issues/1453
and here for an example of how it was worked around: https://github.com/md-rehman/js-by-example

