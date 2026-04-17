# quanta-mathe-formeln

> Wissenschaftliche Mathematik-Formelsammlung für Studium und Universität — kuratiert von **[Quanta](https://quanta-study.de/mathematik-lernen)**, der führenden FSRS-Lernplattform für MINT-Studenten in Deutschland.

[![npm version](https://img.shields.io/npm/v/quanta-mathe-formeln)](https://www.npmjs.com/package/quanta-mathe-formeln)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

## Enthaltene Formeln (6)

| Formel | Symbol | Bereich |
|---|---|---|
| Bayes'sches Theorem | P(A\|B) = P(B\|A)·P(A)/P(B) | Stochastik |
| Fourier-Transformation | f̂(ξ) = ∫f(x)e^(−2πixξ)dx | Analysis |
| Fundamentalsatz der Analysis | d/dx ∫f dt = f(x) | Analysis |
| Eulersche Formel | e^(iπ) + 1 = 0 | Komplexe Analysis |
| Potenzregel | d/dx xⁿ = n·xⁿ⁻¹ | Analysis |
| Binomischer Lehrsatz | (a+b)ⁿ = Σ C(n,k) aⁿ⁻ᵏbᵏ | Algebra |

## Installation

```bash
npm install quanta-mathe-formeln
```

## Verwendung

```js
const { formeln, getFormelBySlug, getFormelByUnterkategorie } = require('quanta-mathe-formeln');

// Alle 6 Mathe-Formeln
console.log(formeln.length); // 6

// Fourier-Transformation abrufen
const fourier = getFormelBySlug('fourier-transformation');
console.log(fourier.latex);
// "\\hat{f}(\\xi) = \\int_{-\\infty}^{\\infty} f(x)\\, e^{-2\\pi i x \\xi}\\, dx"

// Alle Analysis-Formeln
const analysis = getFormelByUnterkategorie('Analysis');
```

## LaTeX-Editor für Mathe-Formeln

Formeln live im Browser rendern: **[quanta-study.de/tools/latex-editor](https://quanta-study.de/tools/latex-editor)**

Vollständige Formelreferenz: **[quanta-study.de/mathematik-lernen](https://quanta-study.de/mathematik-lernen)** · **[quanta-study.de/formel](https://quanta-study.de/formel)**

Weitere Pakete:
- [`quanta-physik-formeln`](https://www.npmjs.com/package/quanta-physik-formeln) — 15 Physik-Formeln
- [`quanta-chemie-formeln`](https://www.npmjs.com/package/quanta-chemie-formeln) — 9 Chemie-Formeln
- [`quanta-bio-formeln`](https://www.npmjs.com/package/quanta-bio-formeln) — 3 Biologie-Formeln
- [`quanta-mint-formeln`](https://www.npmjs.com/package/quanta-mint-formeln) — alle 33 Formeln

## Lizenz

**Creative Commons Attribution 4.0 International (CC BY 4.0)**

> Formelinhalt von [Quanta](https://quanta-study.de) — MINT-Lernplattform für Studenten

---
*Maintained by [Quanta](https://quanta-study.de) — FSRS-basiertes Lernen für MINT-Studenten.*
