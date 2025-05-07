<p align="center">
  <img src="https://via.placeholder.com/150" alt="SSTAF Logo" width="150"/>
</p>

<h1 align="center">SSTAF Riemann Hypothesis Visualization 📊</h1>

<p align="center">
  <a href="https://github.com/your_username/sstaf-riemann-mobile/actions"><img src="https://img.shields.io/github/workflow/status/YYurq/sstaf-riemann-mobile/CI?label=CI" alt="CI Status"></a>
  <a href="https://github.com/your_username/sstaf-riemann-mobile/blob/main/LICENSE"><img src="https://img.shields.io/github/license/YYurq/sstaf-riemann-mobile" alt="License"></a>
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3.10+-blue" alt="Python Version"></a>
</p>

<p align="center">
  A Jupyter Notebook for visualizing the regularization of the Riemann zeta function (ℜζ(s)) on the critical line (Re(s) = ½) using the <strong>Spectral-Symmetric Theory of Analytic Functions (SSTAF)</strong>. This project demonstrates symmetry, singularity suppression, and supports the Riemann Hypothesis by excluding zeros off the critical line.
</p>

## 🌟 Features

- **Regularization**: Implements ℜζ(s) = exp(−∫ ψ(s, u, ε) |ζ(u)|² du) · ζ(s) with ε = 10⁻⁵ (see Section 3.1 of the referenced paper).
- **Visualization Steps**:
  1. 📈 Plot of |ℜζ(s)| showing symmetry about t = 0.
  2. 🌡️ Heatmap and 3D plot of the operator kernel |K(t, t')|.
  3. 🔢 Eigenvalues of Ĥ.
  4. ✅ Spectral symmetry confirming zeros on Re(s) = ½.
  5. 📊 Trace analysis.
- **Mobile-Friendly**: Optimized for smartphones (width: 300px, height: 400px).
- **Annotations**: Highlights symmetry, singularity suppression, and key points (t = −20, −10, 0, 10, 20).

## 📋 Prerequisites

| Requirement         | Version/Description          |
|---------------------|-----------------------------|
| **Python**          | 3.10+                      |
| **Jupyter Notebook**| Latest                     |
| **Libraries**       | `numpy`, `matplotlib`, `mpmath`, `scipy`, `plotly`, `nbformat` |

## 🚀 Setup and Running

### Local Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your_username/sstaf-riemann-mobile.git
   cd sstaf-riemann-mobile

pip install -r requirements.txt

jupyter notebook sstaf_riemann_proof.ipynb

Example Output

<p align="center">
  <img src="https://via.placeholder.com/600x300.png?text=Sample+Visualization" alt="Sample Visualization" width="600"/>
</p>

 Documentation

Theory: Based on the Spectral-Symmetric Theory of Analytic Functions (SSTAF). For details, refer to the original paper (#) (replace with actual link if available).



Notebook: The sstaf_riemann_proof.ipynb file contains detailed comments and step-by-step visualizations.


 Contributing

We welcome contributions! To get started:

Fork the repository.



Create a feature branch (git checkout -b feature-name).



Commit your changes (git commit -m 'Add feature').



Push to the branch (git push origin feature-name).



Open a Pull Request.


Please read our Contributing Guidelines (CONTRIBUTING.md) for more details.

 License

This project is licensed under the MIT License - see the LICENSE file for details.

 Acknowledgments

Inspired by the Spectral-Symmetric Theory of Analytic Functions (SSTAF).


Thanks to the open-source community for tools like numpy, matplotlib, and plotly.


 Contact

Have questions? Reach out via GitHub Issues or connect on X

.

<p align="center">
  <a href="https://x.com/YURQ"><img src="https://img.shields.io/badge/Follow%20on%20X-1DA1F2?logo=x" alt="Follow on X"></a>
</p>

