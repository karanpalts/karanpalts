
<!-- Profile README for @YOUR-USERNAME -->

<h1 align="center">Hi, I'm Karan 👋</h1>

<p align="center">
  <b>Data & Ops professional | MS in AI (UST) | Turning messy data into clean decisions</b>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/karanpatel-/">LinkedIn</a> •
  <a href="mailto:karanpatel435@gmail.com">Email</a> •
  <a href="#projects">Projects</a>
</p>

---

### About me
- 🎓 B.S. in Operations & Supply Chain (Data Analytics minor) — University of St. Thomas
- ⚙️ Gas Operations Intern @ Xcel Energy — data QA, process improvement, SAP Business Client
- 🛒 Former Buyer/Coordinator @ Amba Property Development — Kanban, inventory optimization (–35% surplus)
- 🤝 Web Lead @ Ria Patel Foundation — outreach & fundraising (↑45% funding), safety awareness initiatives
- 🧰 Tools I use: Python (Pandas, NumPy, Matplotlib), SQL, Excel, Power BI, R, SPSS, STATA, Minitab, SAP, Git/GitHub
- 💡 Interests: data prep & quality, bootstrapping/permutation tests, EDA & visualization, supply‑chain analytics

---

### Tech stack
<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-–-?logo=python&logoColor=white" />
  <img alt="Pandas" src="https://img.shields.io/badge/Pandas-–-?logo=pandas&logoColor=white" />
  <img alt="NumPy" src="https://img.shields.io/badge/NumPy-–-?logo=numpy&logoColor=white" />
  <img alt="Matplotlib" src="https://img.shields.io/badge/Matplotlib-–-?" />
  <img alt="Power BI" src="https://img.shields.io/badge/Power%20BI-–-?logo=powerbi&logoColor=white" />
  <img alt="SQL" src="https://img.shields.io/badge/SQL-–-informational" />
  <img alt="Git" src="https://img.shields.io/badge/Git-–-?logo=git&logoColor=white" />
</p>

---

### Highlights
- **SEIS 631 — Data Preparation & Analysis** (UST): EDA, merging/cleaning, missing data, CLT, bootstrapping, permutation & t‑tests, visualization — all with Python.
- **SEIS 603 — Foundations of Python I**: fundamentals, problem solving, clean student‑style code, documentation-first mindset.

---

### Featured projects <a id="projects"></a>

🔹 **SEIS631 – Data Prep & Inference Portfolio**  
End‑to‑end notebooks for EDA, data cleaning/merging, missingness diagnostics (MCAR/MAR/MNAR), bootstrapping & permutation tests, and classic t/χ² tests. Repro‑ready with `environment.yml`, example datasets, and CI to validate notebooks.

🔹 **Supply Chain Ops Mini‑Dash (Power BI)**  
Small KPI dashboard for inventory, stockouts, and anomaly detection; highlights Kanban gains and monthly cost reduction.

---

### How I work
- Clear READMEs, inline comments, and student‑level code that I can explain line‑by‑line
- Reproducible environments (`conda`), tidy project structure, and data ethics in mind

---

### Contact
Let’s connect: [LinkedIn](https://www.linkedin.com/in/karanpatel-/) • [Email](mailto:karanpatel435@gmail.com)
```

---

# 2) `seis631-portfolio` — Repository README + layout

> Create a new public repo named **`seis631-portfolio`** and use the structure + README below. Add your cleaned notebooks & assets.

## Suggested layout

```
seis631-portfolio/
├─ README.md
├─ environment.yml
├─ .gitignore
├─ data/
│  ├─ raw/            # small sample data only (no large/proprietary files)
│  └─ processed/
├─ notebooks/
│  ├─ 01_eda_visualization.ipynb
│  ├─ 02_missing_data_mcar_mar_mnar.ipynb
│  ├─ 03_merging_cleaning_feature_engineering.ipynb
│  ├─ 04_bootstrapping.ipynb
│  ├─ 05_permutation_tests.ipynb
│  ├─ 06_t_tests_and_chi_square.ipynb
│  └─ 99_utils_demo.ipynb
├─ src/
│  ├─ __init__.py
│  ├─ data_prep.py           # clean/merge, type handling, outliers
│  ├─ missingness.py         # MCAR/MAR/MNAR checks + viz helpers
│  ├─ inference.py           # bootstrap/permutation wrappers
│  └─ viz.py                 # plotting helpers
├─ reports/
│  ├─ figures/
│  └─ exports/
└─ .github/
   └─ workflows/
      └─ nb-validate.yml     # CI to smoke-test notebooks
```

## Repo README (drop-in)

````markdown
# SEIS 631 — Data Preparation & Inference (Portfolio)

[![Built with Python](https://img.shields.io/badge/Python-3.11-blue)]()
[![Pandas](https://img.shields.io/badge/Pandas-✓-informational)]()
[![Matplotlib](https://img.shields.io/badge/Matplotlib-✓-informational)]()
[![Open In nbviewer](https://img.shields.io/badge/View-Notebooks-blue)](https://nbviewer.org/github/YOUR-USERNAME/seis631-portfolio/tree/main/notebooks/)

A clean, reproducible set of notebooks and helpers covering the core skills from SEIS 631:

- **Data prep**: cleaning, merging, type fixing, feature engineering
- **EDA & viz**: distributions, correlations, outliers, tidy plots
- **Missingness**: MCAR/MAR/MNAR diagnostics & visualizations
- **Inference**: bootstrapping, permutation tests, t‑tests, χ²

> Built for clarity: student‑style code, line‑by‑line comments, and README‑driven development.

---

## Quickstart

### 1) Clone & create environment
```bash
git clone https://github.com/YOUR-USERNAME/seis631-portfolio.git
cd seis631-portfolio
conda env create -f environment.yml
conda activate seis631
````

### 2) Launch Jupyter

```bash
jupyter lab
```

Open a notebook in `notebooks/` and run cells.

> No conda? Use `pip install -r requirements.txt` (optional), or open in the cloud via nbviewer links above.

---

## Repo tour

* `notebooks/` — Primary deliverables for EDA, missingness, bootstrapping, permutation, and t/χ² tests
* `src/` — Reusable helpers (data cleaning, missingness checks, inference snippets, plotting)
* `data/` — Tiny sample CSVs for demo only; keep large/private data elsewhere
* `reports/` — Figures and exports for write‑ups

---

## Reproducibility & CI

* `environment.yml` pins Python + core libs
* GitHub Actions (see `.github/workflows/nb-validate.yml`) runs `papermill` to smoke‑test notebooks on push
* Notebooks auto‑strip outputs via `nbstripout` (keeps diffs clean)

---

## Highlights

* Robust **missingness analysis**: MCAR vs MAR vs MNAR with visual evidence & narratives
* **Bootstrapping** and **permutation tests** implemented from first principles + library checks
* Clear **t‑test / χ²** examples as “shortcuts to the one big test”

---

## Screenshots

*Add a couple of PNGs from `reports/figures` showing your best visuals*

---

## License

MIT — see `LICENSE`

````

## `environment.yml` (drop-in)

```yaml
name: seis631
channels:
  - conda-forge
dependencies:
  - python=3.11
  - jupyterlab
  - numpy
  - pandas
  - matplotlib
  - scipy
  - scikit-learn
  - seaborn
  - statsmodels
  - pip
  - pip:
      - nbstripout
      - papermill
````

## `.gitignore` (drop-in)

```
# Python
__pycache__/
*.pyc
*.pyo
*.pyd
.ipynb_checkpoints/

# Data
/data/raw/*
/data/processed/*
!data/raw/.gitkeep
!data/processed/.gitkeep

# OS
.DS_Store
```

## CI: `.github/workflows/nb-validate.yml`

```yaml
name: nb-validate
on: [push, pull_request]
jobs:
  run:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: mamba-org/setup-micromamba@v1
        with:
          environment-file: environment.yml
          cache-environment: true
      - name: Strip outputs
        run: |
          micromamba run -n seis631 nbstripout --install --attributes .gitattributes
      - name: Smoke-test notebooks
        run: |
          micromamba run -n seis631 python - << 'PY'
          import os, glob, papermill as pm
          os.makedirs('reports/exec', exist_ok=True)
          for nb in sorted(glob.glob('notebooks/*.ipynb')):
              out = os.path.join('reports/exec', os.path.basename(nb))
              pm.execute_notebook(nb, out, parameters={"CI": True})
          print("✅ Notebooks executed")
          PY
```

---

# Bonus: per‑assignment README skeleton

```markdown
# A0x — Title of assignment

**Goal:** Short, plain‑English goal.

**Data:** Source, shape, key columns, known issues.

**Steps:**
1. Load & preview
2. Clean & transform
3. EDA & visuals
4. Methods (bootstrap / permutation / tests)
5. Findings (1–3 bullets)

**How to run:**
```

conda activate seis631
jupyter lab

```
Open `notebooks/A0x_*.ipynb` and run all cells.
```

**Results:**

* Figure 1 — what it shows
* Stat: estimate ± CI; p‑value; practical takeaway

```

---

# Social preview image tip
Create a 1280×640 image (e.g., a clean chart montage) and upload as the repo’s **Social preview** (Settings → General → Social preview) so links look great on LinkedIn.

```
