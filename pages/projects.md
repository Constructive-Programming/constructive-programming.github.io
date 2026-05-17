---
layout: page
title: Projects
subtitle: Libraries, a language, and teaching material around constructive programming
permalink: /projects/
feature-img: "assets/img/pexels/circuit.jpeg"
bootstrap: true
tags: projects
---

Each project below is independently versioned at
[github.com/Constructive-Programming](https://github.com/Constructive-Programming).
They share a common motivation — making *correct by construction* practical
— but each tackles a different slice: today's tooling, tomorrow's language,
or the ideas underneath both.

{% include projects.html %}

## How the pieces fit together

- **Libraries** make constructive idioms practical in Scala *today*.
  [cats-eo](https://github.com/Constructive-Programming/eo) is the
  flagship — production-grade optics with discipline-checked laws and
  performance benchmarked against Monocle.
  [scala-cardinality](https://github.com/Constructive-Programming/scala-cardinality)
  and [surreals](https://github.com/Constructive-Programming/surreals)
  are smaller explorations that back the methodology with code.

- **The language**,
  [Fixed](https://github.com/Constructive-Programming/fixed), is the
  long-term bet: programs written against *capabilities* (predicate
  functors à la Quine) instead of concrete data types, with the three
  constructive criteria — referential transparency, totality, and
  termination — enforced by the type system. Algebraic effects,
  refinement types, and `prop` invariants give compiler-checked
  lightweight theorem proving.

- **Learning** — the
  [workshops](https://github.com/Constructive-Programming/workshops)
  and conference [talks](https://slides.com/rodolfohansen) explain
  *why*, not just *how*. Start with *Correct by Construction* or
  *Keep Your Types Small* if you're new to the idea.

## Contributing

Everything is on GitHub under
[Constructive-Programming](https://github.com/Constructive-Programming).
Open issues and PRs welcome on the active projects — `eo` and `fixed`.
