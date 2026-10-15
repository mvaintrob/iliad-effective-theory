# Effective theory for singular learning — problem sets

Problem sets for the two effective-theory lectures on the SLT day of the Iliad Intensive 2026.

- **Notebook 5** goes with Lecture 1 (SLT at finite $n$, the Hermite basis, Newton polygons).
- **Notebook 6** goes with Lecture 2 (learning zero at all widths).

They assume Notebooks 2 and 3 from the SLT day (free energy as a volume; the effective exponent), which are in the [SLT day notebooks](https://github.com/CharlesR-W/crw-iliad-intensive-oct-2026/tree/main/slt).

## Where to start

Do the two **core** exercises first. Everything else is there for whoever wants more.

### Notebook 5 — Effective theory

| | Exercise | Priority |
|---|---|---|
| **5.2a** | The cosine integral, and the truncation theorem it gives | **core** |
| **5.3a** | Newton polygons in one parameter | **core** |
| 5.3b | Two parameters, and where counting by sizes fails (cancellation) | further |
| 5.3c | Furman's cubic model at finite $n$ | further |
| 5.1b | A small target looks like learning zero until $n\approx\varepsilon^{-2}$ (the two-plateau picture) | lower priority |
| 5.2b | Other activations: decay set by the nearest complex pole | optional |
| 5.1a | Why generic losses are non-singular (tilting and Sard's theorem) | optional |
| 5.4a–d | Tropical arithmetic: the algebra behind Newton polygons | optional sheet |
| 5.2c–d | A function space that keeps growing; upper bounds from a submersion point | low priority |

### Notebook 6 — Learning zero at all widths (challenge)

| | Exercise | Priority |
|---|---|---|
| 6.1a | Only $H$ moments matter | core |
| 6.1b | The upper bound $\lambda_H\lesssim\tfrac12\sqrt H$, by construction | core |
| 6.1c | The Fourier dual: $H$ neurons become the $H$-th power of one neuron's function | core |
| 6.1d | One neuron, by sizes; staircases | core |
| 6.1e | The linear program | further |
| 6.1g | A truncated model sees only its dimension | further |
| 6.1f* | The missing step: cancellation inside one neuron | open-ended |

## Files

- `notebooks/*.html` — read in a browser. Solutions are folded under *Solution*, and every code cell's output is shown.
- `notebooks/*.ipynb` — run in Jupyter (CPU only; numpy, scipy, matplotlib).
- `slides/lecture1_effective_theory.pdf` — Lecture 1.

GitHub shows `.html` files as source. To read them as pages, download them, or turn on GitHub Pages for this repository.
