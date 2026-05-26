# India Job Market Analysis 2025

Exploratory data analysis of the **Indian job market** using a real-world dataset. Covers data cleaning, grouping, slicing, and visualisation using Python in a Jupyter Notebook.

## Repository structure

```
job-market-analysis/
├── india job market 2025.ipynb   ← main analysis notebook
├── india_job_market.csv          ← source dataset
├── india_job_market.pdf          ← project report
├── india_job_market.pptx         ← presentation slides
├── ABSTRACT.docx                 ← project abstract
├── requirements.txt
└── README.md
```

## What's covered

- **Data loading & inspection** — reading the CSV with `pandas`, checking shape, dtypes, and nulls
- **Data cleaning** — handling missing values, standardising columns
- **Grouping & aggregation** — job counts by industry, location, experience level
- **Slicing & filtering** — isolating roles by skill, salary range, and city
- **Visualisation** — bar charts, histograms, and trend plots via `matplotlib`
- **Model preparation** — train/test splitting with `sklearn.model_selection`

## Setup

### 1. Clone the repo

```bash
git clone https://github.com/Sai-manoj-ranga/job-market-analysis.git
cd job-market-analysis
```

### 2. Create a virtual environment (recommended)

```bash
python -m venv venv
source venv/bin/activate        # macOS / Linux
venv\Scripts\activate           # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch the notebook

```bash
jupyter notebook "india job market 2025.ipynb"
```

## Dataset

**File:** `india_job_market.csv`
Indian job postings for 2025 — fields include job title, company, location, required skills, experience level, and salary range.

## Tech stack

| Library | Purpose |
|---|---|
| `pandas` | Data manipulation & analysis |
| `numpy` | Numerical operations |
| `matplotlib` | Visualisation |
| `scikit-learn` | Train/test split & ML prep |
| `jupyter` | Interactive notebook environment |

## Author

**Sai Manoj Ranga** — [GitHub](https://github.com/Sai-manoj-ranga)
