# Collapsing Towers for Fun and Profit

## Research Goal

Modern computer stacks run over multiple levels of abstraction. A payroll form
might use formulas written into a spreadsheet, which is executed by the
spreadsheet's internal evaluator, which is implemented in Javascript, running
in a browser, and so on. Because each layer has its own distinct semantics,
reasoning at the level of the complete system is difficult, with errors often
creeping in at the boundaries. Even worse, layers may not even have *consistent*
semantics -- a Python interpreter may dynamically load performance instrumentation
for certain functions mid-flight.

There *is* a way out. Via staged programming and specialization, we can
*collapse* this tower into one program, operating under one semantics.

Our goals are twofold:

- To find new ways of constructing and reasoning about systems of collapsing towers.
- To find and explore practical use-cases of collapsing towers in novel domains.

## Current Projects

### Collapsing Towers for Side-Channel Security

Much recent attention has been placed on *microarchitectural* side-channel
attacks, where hardware-level optimizations are exploited to leak information
about a supposedly-secure process through differences in execution time. We
propose to address this by collapsing the abstract semantics of the top-level
program with the underlying hardware semantics to reify such side channel
information into a form more amenable to formal verification. Then, we can use
off-the-shelf static analyzers to discover and repair microarchitectural flaws.

## Collaborators

- [Cameron Wong](https://camdar.io/) (Harvard University)
- [Muhammad Abdullah](https://itsabdullah.dev) (MIT)
- [Yuheng Yan](https://people.csail.mit.edu/yuhengy/) (MIT)
- [Nada Amin](https://namin.seas.harvard.edu/about) (Harvard University)
- [Mengjia Yan](https://people.csail.mit.edu/mengjia/) (MIT)
- [Adam Chlipala](http://adam.chlipala.net) (MIT)

<!--  LocalWords:  Nada Amin Cameron Wong Scala Lightweight Modular Staging LMS
 -->
