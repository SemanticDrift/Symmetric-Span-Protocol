# The Symmetric Span Protocol (SSP)
### Completing the Pythagorean Theorem

**Series:** Mathematical Foundations for Universal Systems
**Author:** Carolina Johnson (CJ) 
**Date:** April 2026
**License:** CC BY 4.0, Attribution required
**DOI:** https://doi.org/10.5281/zenodo.19447063
**ORCID:** https://orcid.org/0009-0002-8819-3347

---

## What This Does

Restores the missing linear context of the Pythagorean theorem. A four-variable coordinate derivation engine that generates any triangle from a boundary span using elementary arithmetic. One degree of freedom determines the entire structure. The Pythagorean theorem appears as the special case Δ = 0.

---

## The Problem It Solves

The Pythagorean theorem a² + b² = c² is correct but incomplete. It tells you the relationship between three sides of a right triangle. It does not tell you where the triangle sits on a circle, how it balances around its center, or why a rope of fixed length pinned at three points must form a specific triangle.

Ancient builders used a 12-knot rope to produce a 3-4-5 right triangle. The standard theorem confirms it works. It does not explain why it must work.

The Symmetric Span Protocol fills that gap.

---

## The Protocol

For any anchor boundary [a, d] with a < d, define:

```
b = (a + d) / 2     — Centroid: arithmetic midpoint
c = d - a           — Span: displacement between anchors
```

These are not hypotheses. They are the definitions of midpoint and distance. Given a and d, the values b and c are forced.

The four variables form a closed symmetry matrix:

```
a = b - (c / 2)
b = (a + d) / 2
c = d - a
d = b + (c / 2)
```

Any one variable can be derived from any two others. The system is closed by arithmetic.

---

## The Delta Constant

For any triangle produced by the SSP:

```
Δ = b² + c² - d²
  = (5a - d)(a - d) / 4
```

Since a < d, the sign of Δ is determined by (5a - d):

| Condition | Δ | Triangle |
|-----------|---|----------|
| d = 5a | 0 | Right (Rectangulo) |
| d < 5a | < 0 | Obtuse (Obtusangulo) |
| d > 5a | > 0 | Acute (Acutangulo) |

The standard Pythagorean theorem addresses only Δ = 0. The SSP extends it to all triangles.

---

## The Pythagorean Subclass

When d = 5a, let a = n:

```
a = n,  b = 3n,  c = 4n,  d = 5n
```

This is the 3-4-5 family. It satisfies b² + c² = d² exactly. It scales to any magnitude. The 12-knot rope corresponds to the boundary [1, 5], producing b = 3, c = 4, d = 5 as arithmetic necessity — not geometric intuition.

---

## What the Standard Theorem Is Missing

Two things:

**Missing context:** The theorem does not specify where the triangle sits within a circle. It ignores the anchor points that define the base span and centroid.

**No balance point:** The centroid b is not used as a primary variable. Without it, the triangle has no reference to the linear field from which it was derived.

The Pythagorean theorem is not wrong. It is incomplete. This paper completes it.

---

## The SSP Logic Engine

An interactive tool is included in this repository. Enter any two of the four variables and the engine derives the remaining two, computes Δ, classifies the triangle, and renders the geometry in real time.

The engine runs in any browser. No dependencies.

---

## Repository Contents

| File | Description |
|------|-------------|
| `README.md` | This file |
| `Symmetric Span Protocol.pdf` | Full paper with proofs and scaling law |
| `SSP_Engine.html` | Interactive SSP Logic Engine |

---

## Citation

```
Johnson, C. (2026). The Symmetric Span Protocol: Completing the Pythagorean Theorem.
Series: Mathematical Foundations for Universal Systems.
SemanticShift. DOI: https://doi.org/10.5281/zenodo.19447063
```

---

## License

© 2026 Carolina Johnson (CJ)
Licensed under Creative Commons Attribution 4.0 International (CC BY 4.0)
Attribution required. https://creativecommons.org/licenses/by/4.0/

> *"The Pythagorean theorem is not wrong. It is incomplete. This paper completes it."* — CJ
