# Mechanization of Logic and Meta-Logic

We are working on the mechanization of logic and meta-logic. Logic is the study of formal systems for reasoning and understanding, and meta-logic is the study of the formal systems which encode those systems. By mechanizing our knowledge of these fundamental fields, we aim to better understand and express the techniques which underlie other mathematical and scientific areas of study.

# Current Research

The basis of our mechanization is [miniKanren](http://minikanren.org/), a relational programming language which allows the concise expression of high-level ideas. We aim to develop extensions, techniques and software systems which use miniKanren in new and novel ways. These include staging systems, constraint solvers, optimizing compilers and runtime optimizations.

# Applications

## Exploration of Language Semantics

One common application of logical inference is the formalization of programming language syntaxes and semantics, and a common application of meta-logic is the formalization of the methods of formalizing those syntaxes and semantics. By mechanizing these, we intend to make the study, development and understanding of programming languages easier.

## Program Synthesis

Complete, relational programming languages lend themselves to the task of program synthesis. By defining an interpreter, then running it backward, one can synthesize arbitrary programs with little effort. Our work is to make relational programming languages more efficient, allowing this task to become even more effortless. Current approaches include the use of annotations to compile away overhead through staging or other optimization passes.

# Collaborators

- [Michael Ballantyne](https://mballantyne.net/) (Northeastern University)
- [Rafaello Sanna](https://github.com/rvs314) (Harvard University)
- [William Byrd](http://webyrd.net/) (University of Alabama at Birmingham)
- [Nada Amin](https://namin.seas.harvard.edu/about) (Harvard University)

<!--  LocalWords:  Nada Amin Rafaello Sanna Ballantyne LocalWords miniKanren
 -->
