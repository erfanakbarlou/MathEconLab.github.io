# MathLab — Interactive Mathematical Economics

Browser-based interactive app based on the uploaded `L0.ipynb`.

## Run
Extract the ZIP and open `index.html` in a modern browser. An internet connection is required for Plotly.js and MathJax CDNs. No Python/Jupyter/backend is needed.

## Function families
- Cobb–Douglas
- CES (including the Cobb–Douglas limit as rho approaches zero)
- Perfect Substitutes
- Perfect Complements (non-smooth kink handled explicitly)
- General Quadratic

## Analysis panel
- Jacobian / gradient row vector at the selected point
- Hessian matrix at the selected point
- Bordered Hessian at the selected point
- Numerical diagnostics for convexity, concavity, quasi-convexity and quasi-concavity across the displayed positive-input domain

Important: matrix entries are evaluated numerically at the selected point. Curvature classifications are numerical sign scans on a finite grid, not formal symbolic proofs. The perfect-complements function is non-differentiable on its kink set, where classical Jacobian and Hessian are not defined.
