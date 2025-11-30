# Maths for Data Science

A work‑in‑progress learning project that builds practical intuition for core linear algebra topics used in data science and machine learning. The notebook(s) illustrate concepts with small, concrete examples and simple applications (including fraud/AML scenarios).

## Roadmap (Planned Topics)
- Vectors
- Matrices / Linear Algebra
- Matrices / Linear Mapping
- Eigenvalues and Eigenvectors / Data Problems

## What’s Covered So Far
- Vector basics with NumPy: creation, addition, subtraction, and magnitude (norm).
- Linear combinations: building weighted sums `a*v1 + b*v2` and interpreting weights as importance.
- Distance-based anomaly detection: using Euclidean distance to quantify deviation from a normal pattern.
- Fraud/AML mini-scenarios:
	- Simple transaction deviation and anomaly scoring
	- Feature weighting with scalars to change sensitivity
	- Scenario multipliers (e.g., international, late-night) to adjust risk
	- Threshold tuning for conservative/balanced/permissive decisions
- Dot product fundamentals and properties:
	- Distributive over addition: `u·(v + w) = u·v + u·w`
	- Associative with scalars: `(c·u)·v = c·(u·v) = u·(c·v)`
	- Practical examples (shopping cart costs, investment returns)
	- AML/Fraud applications: portfolio risk, regulatory sensitivity adjustments

## Repository Contents
- `Vector.ipynb` — Main notebook with examples and scenarios.
- `README.MD` — This document.

## How to Run
1. Ensure Python and Jupyter are installed.
2. Install dependencies (NumPy and Pandas). For a quick start:

```powershell
pip install numpy pandas
```

3. Open `Vector.ipynb` in VS Code (or Jupyter) and run cells sequentially.

## Goals
- Keep the math concrete and explain “why” through relatable examples.
- Connect linear algebra operations to real data science decisions.
- Provide small, modifiable code blocks you can tweak to build intuition.

## Status
Project is still in progress. Additional sections on matrices, linear mappings, and eigen-analysis will be added next.

## Next Steps
- Introduce matrix operations (multiplication, transpose, inverse) with practical use cases.
- Demonstrate linear mappings: transformations, feature engineering, dimensionality changes.
- Explore eigenvalues/eigenvectors: variance directions, stability, and risk factors.

## Feedback & Contributions
If you spot typos or want specific examples, feel free to open an issue or suggest a scenario to model.
