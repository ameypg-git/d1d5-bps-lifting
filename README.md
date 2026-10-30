# The Fate of 1/4-BPS States in the D1-D5 CFT

Project page for

> S. Bintanja, A. P. Gaikwad, D. Rathore, *The Fate of 1/4-BPS States in the D1-D5 CFT*,
> [arXiv:2610.36057](https://arxiv.org/abs/2610.36057) [hep-th].

## The question

The D1-D5 system is one of the best-understood examples of holography. At one point in
its space of theories it is described by supergravity on AdS₃ × S³ × T⁴. At another, very
far away, it is described by a simple, solvable model: the symmetric product orbifold
Sym<sup>N</sup>(T⁴). The orbifold point has far more protected (BPS) states than supergravity
does. So as the theory is deformed from one point towards the other, most of these states have to
stop being protected and pick up anomalous dimensions, a process called *lifting*.

**Which states lift, by how much, and why do exactly the right ones survive?**

## What we did

- We followed the lightest 1/4-BPS states away from the orbifold point using second-order
  conformal perturbation theory.
- We computed their anomalous dimensions **exactly in the number of copies N**, covering
  every twisted sector and not only the untwisted one studied before.
- We found that states from different twisted sectors **mix**, and that this mixing stays
  important even at large N.
- Once the mixing is taken into account, the states that remain BPS are **precisely those
  that supergravity requires**.

## How

The calculation is done with a computer-algebra pipeline written in Mathematica. It builds
the relevant states, evaluates the correlators that control lifting, and assembles the
result exactly in N. Several independent cross-checks are built in, including explicit
computations at small N. All of them agree.

**Code:** written in Mathematica; available on request.

## Citation

```bibtex
@article{Bintanja:2026lifting,
  author        = {Bintanja, Suzanne and Gaikwad, Amey P. and Rathore, Dikshant},
  title         = {{The Fate of 1/4-BPS States in the D1-D5 CFT}},
  eprint        = {2610.36057},
  archivePrefix = {arXiv},
  primaryClass  = {hep-th},
  year          = {2026}
}
```
