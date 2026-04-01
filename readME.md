[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.19361736.svg)](https://doi.org/10.5281/zenodo.19361736)
## 🚀 UFP-30: Unified Field Suite (v2.0)

This repository contains the mathematical validation for the **Unitary Force Polynomial (UFP-30)**, a unified field model that resolves the $r \to 0$ singularity while maintaining General Relativity (GR) accuracy across planetary scales.

### 📊 Multi-Scale Validation Results
The following benchmarks were achieved using the Master Matrix (Term_ID 1 & 5458):

| Phenomenon | Scale | Target | UFP-30 Result | Variance |
| :--- | :--- | :--- | :--- | :--- |
| **Bohr Energy** | Quantum | $4.359 \times 10^{-18}$ J | **$4.358 \times 10^{-18}$ J** | ~0.04% |
| **Mercury Precession** | Relativistic | 42.98" | **42.9821"** | 0.0021" |
| **Earth Precession** | Relativistic | 3.838" | **3.8388"** | 0.0008" |
| **Solar Light Deflection** | Photon | 1.751" | **1.7512"** | 0.0002" |

Convergence Metric: The UFP-30 model aligns with General Relativity at the planetary scale with a variance ratio of $4.98 \times 10^{-35}$, confirming absolute macro-scale stability.
### 📂 Directory Structure
- `/data`: Contains `UFP30_V2_Master_Matrix.csv` (The Universal Coefficients).
- `/doc`: Contains `UFP_30.ipynb` (The Validation Engine).

### 🛠 Environment
- **OS**: Linux Mint Cinnamon
- **Kernel**: Python 3.12 (with Decimal precision set to 250)
- **Host**: Mac Mini 2014
