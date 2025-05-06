# SSTAF Riemann Hypothesis Visualization

This repository contains a Jupyter Notebook that visualizes the regularization of the Riemann zeta function \( \mathcal{R}\zeta(s) \) on the critical line (\( \text{Re}(s) = \frac{1}{2} \)) using the Spectral-Symmetric Theory of Analytic Functions (SSTAF). The visualization demonstrates the symmetry of \( |\mathcal{R}\zeta(s)| \), suppression of singularities, and supports the Riemann Hypothesis by excluding zeros off the critical line.

## Features
- **Regularization**: Implements \( \mathcal{R}\zeta(s) = \exp\left(-\int \psi(s, u, \varepsilon) |\zeta(u)|^2 du\right) \cdot \zeta(s) \) with \( \varepsilon = 10^{-5} \) (see Section 3.1 of the referenced paper).
- **Visualization**:
  - Step 1: Plot of \( |\mathcal{R}\zeta(s)| \) showing symmetry about \( t = 0 \).
  - Step 2: Heatmap and 3D plot of the operator kernel \( |K(t, t')| \).
  - Step 3: Eigenvalues of \( \hat{H} \).
  - Step 4: Spectral symmetry confirming zeros on \( \text{Re}(s) = \frac{1}{2} \).
  - Step 5: Trace analysis.
- **Mobile-Friendly**: Optimized for smartphones (width: 300px, height: 400px).
- **Annotations**: Highlights symmetry, singularity suppression, and key points (\( t = -20, -10, 0, 10, 20 \)).

## Prerequisites
- Python 3.10+
- Jupyter Notebook
- Libraries: `numpy`, `matplotlib`, `mpmath`, `scipy`, `plotly`, `nbformat`

## Setup and Running
### Local Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/sstaf-riemann-mobile.git
   cd sstaf-riemann-mobile

pip install -r requirements.txt

jupyter notebook sstaf_riemann_proof.ipynb
