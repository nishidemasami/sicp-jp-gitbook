# Preface to the Second Edition

> Is it possible that software is not like anything else, that it is meant to be
discarded: that the whole point is to always see it as a soap bubble?

> ---Alan J. Perlis



The material in this book has been the basis of <abbr title="MIT">MIT</abbr>'s entry-level
computer science subject since 1980.  We had been teaching this material for
four years when the first edition was published, and twelve more years have
elapsed until the appearance of this second edition.  We are pleased that our
work has been widely adopted and incorporated into other texts.  We have seen
our students take the ideas and programs in this book and build them in as the
core of new computer systems and languages.  In literal realization of an
ancient Talmudic pun, our students have become our builders.  We are lucky to
have such capable students and such accomplished builders.

In preparing this edition, we have incorporated hundreds of clarifications
suggested by our own teaching experience and the comments of colleagues at
<abbr title="MIT">MIT</abbr> and elsewhere.  We have redesigned most of the major programming
systems in the book, including the generic-arithmetic system, the interpreters,
the register-machine simulator, and the compiler; and we have rewritten all the
program examples to ensure that any Scheme implementation conforming to the
<abbr title="IEEE">IEEE</abbr> Scheme standard ([IEEE 1990](References.md#IEEE)) will be able to run the
code.

This edition emphasizes several new themes.  The most important of these is the
central role played by different approaches to dealing with time in
computational models: objects with state, concurrent programming, functional
programming, lazy evaluation, and nondeterministic programming.  We have
included new sections on concurrency and nondeterminism, and we have tried to
integrate this theme throughout the book.

The first edition of the book closely followed the syllabus of our
<abbr title="MIT">MIT</abbr> one-semester subject.  With all the new material in the second
edition, it will not be possible to cover everything in a single semester, so
the instructor will have to pick and choose.  In our own teaching, we sometimes
skip the section on logic programming ([Section 4.4](Logic_Programming.md)), we have students use
the register-machine simulator but we do not cover its implementation ([Section 5.2](A_Register_Machine_Simulator.md)),
and we give only a cursory overview of the compiler ([Section 5.5](Compilation.md)).
Even so, this is still an intense course.  Some instructors may
wish to cover only the first three or four chapters, leaving the other material
for subsequent courses.

The World-Wide-Web site [http://mitpress.mit.edu/sicp](http://mitpress.mit.edu/sicp) provides
support for users of this book.  This includes programs from the book, sample
programming assignments, supplementary materials, and downloadable
implementations of the Scheme dialect of Lisp.