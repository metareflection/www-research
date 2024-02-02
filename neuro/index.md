# Neuro-Symbolic Isomorphisms (NSIs)

Through the introduction of **Neuro-Symbolic Isomorphisms**, we aim to create neural networks that can match the human ability to:
- Reason symbolically.
- Learn composable skills.
- Satisfy safety constraints.

Neuro-Symbolic Isomorphisms are neural architectures that are structurally equivalent to programming language interpreters. At present, we focus on integrating the logic/relational and functional programming paradigms into neural networks. We expect that Neuro-Symbolic Isomorphisms will improve sample efficiency, interpretability, and task performance.

## Meta-Reflective Programming

We believe that the sample efficiency of human learning arises in part from a capacity for meta-reflection, catching and learning from errors by reasoning about reasoning itself at multiple levels. Thus, we take inspiration from [reflective towers of interpreters](https://blog.sigplan.org/2021/08/12/reflective-towers-of-interpreters/) and seek to create meta-reflective neural networks.

## Formal Verification of Safety

We intend to apply formal software verification techniques in order to establish safety guarantees.

# Projects
- Relational Programming Neural Networks
  - The **semKanren Machine** is a relational programming language interpreter that represents all symbols with vector embeddings. The semKanren Machine integrates vector database search into the unification process of miniKanren, enabling what we call *semantic unification*. Semantic unification allows the relational query engine to tolerate semantic ambiguity in queries. As the semKanren Machine is an interpreter, it requires that a programmer provide query code to execute.
  - The **neuroKanren Machine** augments the semKanren Machine with program learning and program synthesis in order to solve tasks autonomously.
- Functional Programming Neural Networks
  - The **Neural Lisp Machine** is an interpreter for Neural Lisp, which stores structured information using cons cells as in classical Lisp while representing all symbols with vector embeddings. Like the neuroKanren Machine, it is self-programming and intended to solve tasks autonomously.

# Programming Language of Thought

Cognitive philosopher Jerry Fodor proposed a language of thought as the basis for a computational theory of mind, using metaphors from programming language theory: programs, subroutines calling subroutines, and computation. As programming language theorists and machine learning researchers, we take up the task of formally specifying the semantics of, and implementing, the *programming language of thought*.

> One imagines a hierarchy of "executive" programs which function to analyze macrotasks into microtasks. Such programs may 'call' both one another and lower-level problem-solving routines, though the extent of such cross-referencing is limited by the ingenuity of the program and, of course, the overall computational capacity of the machine. —Jerry Fodor in *The Language of Thought* (1975)

# People
- [Matthew Retchin](https://mhr.ai)
- [Will Byrd](http://webyrd.net/)
- Raffi Sanna
