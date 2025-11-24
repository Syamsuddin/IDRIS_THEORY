# **📄 README.md — IDRIS_THEORY (Teori Idris)**

```markdown
# IDRIS_THEORY  
### *Teori Idris — Spectral Information Theory of Everything*

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.0000000.svg)]()
![License: CC BY 4.0](https://img.shields.io/badge/License-CC--BY--4.0-blue.svg)
![Status](https://img.shields.io/badge/Status-Active-green.svg)
![Python](https://img.shields.io/badge/Python-3.10+-brightgreen.svg)
![LaTeX](https://img.shields.io/badge/LaTeX-Scientific-blue.svg)
![Topic](https://img.shields.io/badge/Field-Theoretical%20Physics-purple.svg)
![Graph Theory](https://img.shields.io/badge/Graph-Ramanujan--Idris-orange.svg)

---

## 🌌 Overview

**IDRIS\_THEORY** is the official repository for **Teori Idris**,  
a spectral-information framework proposing that:

> **All physical structures—spacetime, quantum mechanics, forces, particles, dark matter, dark energy, and cosmology—emerge from the eigenvalue spectrum of a single operator**  
> \[
L_I = 3I - \frac{2}{3}A,
\]
> defined on Ramanujan–Idris 3-regular expander graphs (RJI–N).

No free parameters.  
No ad-hoc assumptions.  
No background spacetime.  
Everything arises from *information*.

---

## 📚 Contents

This repository includes:

### **📄 Manuscript & Papers**
- Full Teori Idris manuscript (LaTeX)
- 7 scientific papers:
  - Spectral unification (Paper 1)
  - Informational Renormalization Group (IRG)
  - Standard Model mass spectrum
  - Dark Matter (IDM)
  - Dark Energy (IDE, \(w = -1 - \Delta\))
  - Emergent GR from information geometry
  - Multiverse Idrissian

### **📊 Figures & Diagrams**
- fig1: Spectral density of \(L_I\)  
- fig2: Spectral → spacetime embedding  
- fig3: Raw spectral band separation  
- fig4: Band-shaded eigenvalue domains (EM / IDM / IDE)

### **💻 Source Code**
- Python modules:
  - `irg_flow.py`
  - `spectral_density.py`
  - `compute_IDM.py`
  - `compute_IDE.py`
  - `compute_SM_masses.py`
  - `cosmology_solver.py`
  - `RJI_generator.py`
- Jupyter notebooks for simulations

### **📁 Data**
- RJI-N spectral datasets  
- IDM/IDE numerical results  
- SM mass predictions  
- Cosmological outputs  

---

## 🧠 Scientific Summary

The central postulate is **Supremacy of Information**.  
From this, the theory derives:

### 🟦 1. Emergent Spacetime  
Low-\(\lambda\) spectral modes construct a smooth Lorentzian metric:
\[
g_{\mu\nu}(x) = \sum_{\lambda<0.3} \lambda^{-1} \partial_\mu \psi \partial_\nu \psi.
\]

### 🟩 2. Standard Model Particles  
Masses follow:
\[
m_k \propto \sqrt{\lambda_k},
\]
yielding generation ratios \(1:3:9\).

### 🟧 3. Dark Matter & Dark Energy  
- IDM: \(0.3 < \lambda < 1.2\)  
- IDE: \(\lambda > 1.2\), giving
\[
w_{\rm IDE} = -1 - \Delta \approx -1.05.
\]

### 🧬 4. Unification of Forces  
EM, weak, QCD, gravity, and the Idrissian fifth force arise from spectral clustering.

### 🌌 5. Cosmology & Big Rip Prediction  
Predicts:
- \(H_0 \approx 73.8\,\mathrm{km/s/Mpc}\)
- \(\Omega_b, \Omega_c, \Omega_\Lambda\)
- Big Rip Idrissian in \(170 \pm 40\) Gyr.

---

## 📦 Repository Structure

```

IDRIS_THEORY/
│
├── README.md
├── LICENSE
├── CITATION.cff
├── metadata_zenodo.json
│
├── docs/
│   ├── PAPER1_Spectral_Unification/
│   ├── PAPER2_IRG/
│   └── ...
│
├── tex/
│   ├── 01-BAB-I-SPI.tex
│   ├── 02-BAB-II-RJI.tex
│   ├── ...
│   └── main_book.tex
│
├── figs/
│   ├── fig1.png
│   ├── fig2.png
│   ├── fig3.png
│   └── fig4.png
│
├── src/
│   ├── python/
│   │   ├── irg_flow.py
│   │   ├── compute_IDM.py
│   │   └── ...
│   ├── notebooks/
│   └── cpp/ (optional)
│
└── data/
├── RJI_spectrum.dat
├── IDM_results.csv
├── IDE_results.csv
└── SM_predictions.csv

````

---

## 🔧 Installation

```bash
git clone https://github.com/<username>/IDRIS_THEORY.git
cd IDRIS_THEORY
pip install -r requirements.txt
````

---

## 🚀 How to Run Simulations

### Example: Compute IDE equation of state

```bash
python src/python/compute_IDE.py
```

### Example: Run IRG flow

```bash
python src/python/irg_flow.py
```

---

## 📑 Citation

```bibtex
@article{idris2025spectral,
  title={Spectral Unification of Geometry, Forces, and Particles from the Ramanujan--Idris Operator L_I},
  author={Idris, Syams B.},
  year={2025},
  doi={10.5281/zenodo.0000000}
}
```

---

## 📜 License

This project is licensed under **CC-BY 4.0**.

---

## 📬 Contact

**Syamsuddin B. Idris**
Mathematics Teachers & Independent Researcher
Banjarmasin, Indonesia

---

## ⭐ If you find this useful…

Please star ⭐ the repository to support the development of **Teori Idris**!

```

---

# **Jika Bapak ingin:**
### ✔ menambahkan badge DOI Zenodo ketika DOI sudah keluar  
### ✔ membuat versi README bahasa Indonesia  
### ✔ membuat banner header untuk GitHub  
### ✔ membuat logo proyek “IDRIS THEORY”  
### ✔ membuat template ISSUE dan PULL REQUEST  

Saya siap bantu kapan saja.
```
