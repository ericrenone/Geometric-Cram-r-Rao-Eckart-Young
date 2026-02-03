# Cramér-Rao ↔ Eckart–Young–Mirsky Geometric Unification Demo

**Single-file educational artifact** demonstrating the deep geometric connection between:

- **Cramér-Rao Bound** (fundamental limit on variance in statistical estimation)
- **Eckart–Young–Mirsky theorem** (optimal low-rank matrix approximation error)

This script serves as a compact, reproducible, publication-quality teaching and research tool connecting **information geometry**, **statistical estimation**, and **matrix approximation theory**.

![CRB ellipse example](results/crb_ellipse.png)  
![SVD spectrum example](results/svd_spectrum.png)

## Core Idea in One Sentence

Both the Cramér-Rao bound and the Eckart–Young–Mirsky theorem provide **sharp geometric bounds** on how much information/precision we can lose when projecting onto a lower-dimensional space — one in continuous parameter space, the other in discrete matrix space.

## Features

- Publication-quality plots (300 dpi, clean style, consistent typography)
- Reproducible results via explicit random seed control
- Safe output directory handling
- Input validation with clear error messages
- Rectangular low-rank matrices in SVD example (realistic setting)
- Modern Python 3 (type hints, pathlib, f-strings)
- Quick smoke-test mode (`--test`)
- Mutually exclusive run modes + detailed help

## Visual Outputs

| Command                        | What you get                              |
|--------------------------------|-------------------------------------------|
| `--crb`                        | MLE scatter plot + 95% CRB confidence ellipse |
| `--svd`                        | Singular value spectrum + truncation point    |
| `--run-all`                    | Both plots above                              |

Example images are saved in the `results/` folder (or your chosen `--output-dir`).

## Requirements

- Python 3.8+
- numpy
- matplotlib
- scipy

Install dependencies:

```bash
pip install numpy matplotlib scipy
