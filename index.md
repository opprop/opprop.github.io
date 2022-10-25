# Optional Properties (OpProp)

[Checker Framework
Inference](https://github.com/opprop/checker-framework-inference) is a general
type inference framework, built upon the
[Enforcing, Inferring, and Synthesizing Optional Properties (EISOP) Framework](https://eisop.github.io/) project,
which aims to provide a unified framework for optional properties in Java.


## Precise Inference of Expressive Units of Measurement Types (OOPSLA 2020)

*Abstract*

Ensuring computations are unit-wise consistent is an important task in software
development. Numeric computations are usually performed with primitive types
instead of abstract data types, which results in very weak static guarantees
about correct usage and conversion of units.

This paper presents PUnits, a pluggable type system for expressive units of
measurement types and a precise, whole-program inference approach for these
types. PUnits can be used in three modes: (1) modularly check the correctness of
a program, (2) ensure a possible unit typing exists, and (3) annotate a program
with units. Annotation mode allows human inspection and is essential since
having a valid typing does not guarantee that the inferred specification
expresses design intent. PUnits is the first units type system with this
capability. Compared to prior work, PUnits strikes a novel balance between
expressiveness, inference complexity, and annotation effort.

We implement PUnits for Java and evaluate it by specifying the correct usage of
frequently used JDK methods. We analyze 234k lines of code from eight
open-source scientific computing projects with PUnits. We compare PUnits against
an encapsulation-based units API (the javax.measure package) and discovered unit
errors that the API failed to find. PUnits infers 90 scientific units for five
of the projects and generates well-specified applications.

The experiments show that PUnits is an effective, sound, and scalable
alternative to using encapsulation-based units APIs, enabling Java developers to
reap the performance benefits of using primitive types instead of abstract data
types for unit-wise consistent scientific computations.

[OOPSLA 2020 conference page](https://2020.splashcon.org/details/splash-2020-oopsla/18/Precise-Inference-of-Expressive-Units-of-Measurement-Types)

[Paper DOI](https://doi.org/10.1145/3428210)

[Artifact DOI](https://doi.org/10.5281/zenodo.4061106)

[units-inference GitHub repo](https://github.com/opprop/units-inference)


## Security Type System Demo

Demo type system with a simple security lattice.

[security-demo GitHub repo](https://github.com/opprop/security-demo)


## Checker Framework Live Demo

To experience the
[Checker Framework](http://checkerframework.org/)
from within your browser, see our
[Checker Framework Live Demo](http://eisop.uwaterloo.ca/live/).


## Contact

Please address your questions and comments to
[Werner Dietl](https://ece.uwaterloo.ca/~wdietl/contact.html).

