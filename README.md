# Netflix Analysis 🔍

**Project:** Netflix Data Analysis

**Notebook:** `DynamixNetworks_Netflix_Ananlysis.ipynb`

---

## 📌 Overview
This repository contains an exploratory data analysis (EDA) and visualization notebook focused on Netflix titles and related viewer/content patterns. The primary goal is to load Netflix dataset(s), clean and explore the data, produce charts and insights, and run basic modeling or recommendations experiments as needed.

## 🚀 Features
- Data cleaning and preprocessing
- Exploratory visualizations (genre, release year, country, rating distributions)
- Time series and trend analysis
- Basic modeling experiments (optional)
- Reproducible analyses in a single Jupyter notebook

## 🧰 Prerequisites
- Python 3.8+ recommended
- Jupyter Notebook or JupyterLab

Install typical packages (if you don't have a `requirements.txt`):

```bash
python -m venv .venv
source .venv/bin/activate    # Windows: .venv\Scripts\activate
pip install pandas numpy matplotlib seaborn plotly scikit-learn jupyter
```

Or create and install from `requirements.txt`:

```bash
pip install -r requirements.txt
```

## 📁 Data
Place the dataset(s) in a `data/` directory at the project root (create the folder if it doesn't exist). Typical sources:
- Kaggle: "Netflix Movies and TV Shows"
- Your own exported CSV(s)

> Note: Adjust paths in the notebook if your data is stored elsewhere.

## ▶️ How to run
1. Clone the repository.
2. Ensure dependencies are installed (see Prerequisites).
3. Launch the notebook:

```bash
jupyter notebook DynamixNetworks_Netflix_Ananlysis.ipynb
# or
jupyter lab
```

4. Run cells sequentially or use "Run All" to reproduce the analysis.

## 📊 Notebook structure
- Data loading and overview
- Cleaning & feature engineering
- Exploratory visualizations
- Time-series & seasonal analysis
- (Optional) Modeling / recommendation prototypes
- Summary of key insights and discussion

## ✅ Reproducibility & Tips
- Keep data files under `data/` and avoid committing large raw datasets to git.
- Use a virtual environment for package management.
- If you want, I can generate a `requirements.txt` for the current notebook.

## 🤝 Contributing
Contributions and improvements are welcome. Open an issue or submit a pull request with a clear description of your change.

