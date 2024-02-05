# Neuro-Symbolic Artificial Intelligence

## Objectives

### Self-Programming Interpreter Neural Networks (Spinners)

Through the introduction of **Self-Programming Interpreter Neural Networks**, or **Spinners**, we aim to create neuro-symbolic artificial intelligence systems that can match the human ability to:
- Reason symbolically.
- Learn composable skills.
- Satisfy safety constraints.

Spinners are neural networks that are structurally equivalent to programming language interpreters. We expect that Spinners will improve sample efficiency, interpretability, and task performance.

At present, we focus on creating Spinner architectures within the logic/relational and functional programming paradigms.

### Meta-Reflective Neural Networks

We believe that the sample efficiency of human learning arises in part from a capacity for meta-reflection, catching and learning from errors by reasoning about reasoning itself at multiple levels. Thus, we seek to create meta-reflective neural networks, taking inspiration from [reflective towers of interpreters](https://blog.sigplan.org/2021/08/12/reflective-towers-of-interpreters/).

### Formal Verification of Safety in Neural Networks

We intend to apply formal software verification techniques in order to establish safety guarantees about our neural networks.

## Current Projects

### Relational Programming
  - The **vectorKanren Machine** is a relational programming language interpreter that represents all symbols with vector embeddings. The vectorKanren Machine integrates vector database search into the unification process of miniKanren, enabling what we call *semantic unification*. Semantic unification allows the relational query engine to tolerate semantic ambiguity in queries. As the vectorKanren Machine is an interpreter, it requires that a programmer provide vector embeddings of query code to execute.
  - The **neuroKanren Machine** is a Spinner, augmenting the vectorKanren Machine with program learning in order to solve tasks autonomously through self-programming.

### Functional Programming
  - The **Neural Lisp Machine** is a Spinner that interprets Neural Lisp, storing structured information using cons cells as in classical Lisp while representing all symbols with vector embeddings. Like the neuroKanren Machine, it is self-programming and intended to solve tasks autonomously.

## Programming Language of Thought

As programming language theorists and machine learning researchers, we take up the task of formally specifying the semantics of, and implementing, the *programming language of thought*.

> One imagines a hierarchy of "executive" programs which function to analyze macrotasks into microtasks. Such programs may "call" both one another and lower-level problem-solving routines, though the extent of such cross-referencing is limited by the ingenuity of the program and, of course, the overall computational capacity of the machine.
>
>
> —Jerry Fodor in *The Language of Thought* (1975)

## People
- [Matthew Retchin](https://mhr.ai)
- [Raffi Sanna](https://github.com/rvs314)
- [Will Byrd](http://webyrd.net/)
- [Nada Amin](https://namin.seas.harvard.edu/)
