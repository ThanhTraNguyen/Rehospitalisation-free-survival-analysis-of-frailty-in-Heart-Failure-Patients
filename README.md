# Rehospitalisation-free survival analysis of frailty in Heart Failure Patients

This repository contains the rehospitalisation-free survival analysis and statistical models evaluating the prognostic value of physical frailty (measured by the Fried Frailty phenotype) in patients with Heart Failure (HF).

---

##  Getting Started & Installation

### 1. Clone the repository
```bash
git clone git@github.com:ThanhTraNguyen/Rehospitalisation-free-survival-analysis-of-frailty-in-Heart-Failure-Patients.git
cd Fried_frailty_python
```

### 2. Create and activate a virtual environment
```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install packages
```bash
pip install pandas numpy matplotlib seaborn pyreadstat scipy lifelines ipykernel
```

### 4. Run the notebook
Launch Jupyter Notebook or VS Code to run `analysis.ipynb`:
```bash
jupyter notebook analysis.ipynb
```

---

##  Dependencies
* **Python** $\ge 3.8$
* **pandas** (Data manipulation)
* **numpy** (Numerical operations)
* **matplotlib** & **seaborn** (Statistical visualizations)
* **pyreadstat** (Reading SPSS `.sav` files)
* **scipy** (Statistical tests)
* **lifelines** (Survival analysis framework: KM curves, Cox PH, LRT, Lasso, GT tests)
