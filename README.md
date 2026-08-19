# Machine Learning for Finance

Practical mini-projects applying machine learning to financial markets, portfolio analysis, and risk management.

This repository is designed as a growing learning portfolio. Each project starts with a financial question, builds a reproducible data and modeling workflow, evaluates the model, and translates the output into an economically meaningful conclusion.

## Projects

| # | Project | Models | Key question | Status |
|---:|---|---|---|---|
| 1 | [Stock Clustering](01-stock-clustering/) | DBSCAN, K-Means | Can stocks be grouped by historical risk–return characteristics? | Complete |

## Repository principles

- Real financial data and clearly documented assumptions
- Reproducible Python notebooks
- Proper model selection and evaluation
- Financial interpretation, not only technical output
- Transparent limitations and no investment recommendations

## Technology

Python · pandas · NumPy · scikit-learn · yfinance · Matplotlib · Seaborn · Jupyter

## How to run a project

```bash
git clone <repository-url>
cd machine-learning-for-finance
python -m venv .venv
```

Activate the environment:

```bash
# macOS/Linux
source .venv/bin/activate

# Windows PowerShell
.venv\Scripts\Activate.ps1
```

Install the dependencies and start Jupyter:

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
jupyter lab
```

## Author

**Sofia**  
MSc Quantitative Finance candidate

## Disclaimer

The projects in this repository are for educational and research purposes only. They do not constitute investment advice or a recommendation to buy or sell any security.

