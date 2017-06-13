---
layout: page
title: Projects
permalink: /projects/
---

This is a non-exhaustive list of (mostly coding) projects I've been
involved with. Feel free to fork them, criticize them, [send me][email-me]
feedback about them, or use them (or parts thereof) in your own work.

---


### [Coq-Polyhedra][coq-polyhedra]
This is the Coq project I'm working on
(with [Xavier Allamigeon][allamigeon-page] & Ricardo Katz),
which aims to provide an as-complete-as-possible formalization for convex
polyhedra based on the [Simplex][simplex-method] method. You might not see all
commits yet, since the Github repo is a mirror which is synchronized only prior
to major releases or publications.

---


### [Maxplus][maxplus-toolbox]
This is an abruptly interrupted attempt to create a toolbox in Octave for
common operations in $ (\max, +) $ algebra. I might pick it up again someday,
but if you want to hack on it in the meantime, send me an [email][email-me].

---


### [simple-markov][simple-markov-lib]
A small, self-contained (as much as possible) library in `Python` for markov
chains. This was developed to replace an older version of an educational
library which was provided for a Stochastic Processes course, but then became a
project on its own. It was developed together with
[Mandragorian][mandragorian], go check him out.

The initial version of the library was developed by [tetraktida][tetraktida].

---


### [Simpletar][simpletar]
This should be self-explanatory if you are a Linux user. Honestly, *who the
can type a valid `tar` command without cheating?* I tried to make it as simple
as possible, so some information about the archive type you are trying to work
with is inferred automatically using magic bytes, file endings etc.

---


### [JInsect][jinsect]
JInsect used to be a Java toolkit created as the reference implementation for
[N-Gram Graphs][n-gram-graphs]. I never managed to fully merge the refactored
core branch (`core-rc`), but it works pretty fine (plus, it can be used as a Maven
project). I worked on this when I was interning at NCSR
[Demokritos][demokritos], supervised by another [cool guy][ggianna].

---


### [BioGraphs][biographs]
BioGraphs was an attempt to use N-Gram graphs as part of a graph indexing
pipeline, initially aimed towards biological sequence indexing and approximate
nearest neighbours search. I might finish my work on this someday, as I think
it still remains publishable (and hopefully will remain for a few more months).

By the way, you can find the relevant presentation I did as part of this work
[here][biographs-presentation].

---


### Tonyc
No link for this one, but once upon a time we built a complete compiler (from
lexer up to machine code generation) for a [toy language][tony-spec] (sorry,
international friends, the spec was given in Greek :( ) called Tony together
with [Mandragorian][mandragorian], using [OcaML][ocaml] and [LLVM][llvm].
If you'd like to get the code, you [know][email-me] what to do.


[allamigeon-page]: http://www.cmap.polytechnique.fr/~allamigeon/
[biographs]: https://github.com/VHarisop/BioGraphs
[biographs-presentation]: https://www.iit.demokritos.gr/sites/default/files/5_similaritysearchinbiologicalsequences.pdf
[coq-polyhedra]: https://github.com/nhojem/Coq-Polyhedra
[demokritos]: https://www.iit.demokritos.gr
[email-me]: mailto:vharisop@gmail.com
[ggianna]: http://users.iit.demokritos.gr/~ggianna/
[jinsect]: https://github.com/VHarisop/JInsect/tree/core-rc
[llvm]: http://llvm.org/
[mandragorian]: https://github.com/Mandragorian
[maxplus-toolbox]: https://github.com/VHarisop/maxplus
[n-gram-graphs]: https://tac.nist.gov/publications/2009/participant.papers/DemokritosGR.proceedings.pdf
[ocaml]: https://ocaml.org/
[simple-markov-lib]: https://github.com/VHarisop/simple-markov
[simpletar]: https://github.com/VHarisop/Simpletar
[simplex-method]: https://en.wikipedia.org/wiki/Simplex_algorithm
[tetraktida]: https://github.com/tetraktida
[tony-spec]: http://courses.softlab.ntua.gr/compilers/2015a/tony2015.pdf
