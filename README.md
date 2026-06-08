# 🚀 ML Learning Journey

> A structured repository documenting my self-driven learning journey in Python, Statistics, and Machine Learning.

---

## 👩‍💻 About Me

**Amruta Dabholkar** — 3rd Year Computer Engineering Student passionate about Data Science & AI.
I believe in learning by doing — every concept I study gets coded, committed, and pushed here.

🌍 Building in public, one commit at a time.

---

## 📁 Repository Structure

```
ml-journey/
│
├── PYTHON REVISION/          # Python fundamentals & examples
│   ├── PYTHON_EXAMPLES_PART1.ipynb
│   ├── PYTHON_EXAMPLES_PART2.ipynb
│   ├── PYTHON_EXAMPLES_PART3.ipynb
│   └── PYTHON_EXAMPLES_PART4.ipynb
│
├── Stats/                    # Statistical tests & analysis
│   ├── t_test.ipynb
│   ├── two_sample_test.ipynb
│   ├── Z-TEST.ipynb
│   ├── annova_test.ipynb
│   ├── chi_square_test.ipynb
│   └── outliers.ipynb
│
├── numpy/                    # NumPy practice
│
├── Pandas/                   # Pandas practice
│   ├── DataFrames.ipynb
│   ├── series.ipynb
│   ├── Operations.ipynb
│   ├── Missing_Data.ipynb
│   ├── GroupBy_Aggregate.ipynb
│   ├── Merging_Joining_Concatenation.ipynb
│   ├── pivot_table.ipynb
│   ├── Countries.ipynb
│   └── Feature_Extraction_Project.ipynb
│
├── Data Visualization/       # Matplotlib, Seaborn, Plotly
│   ├── matplotlib.ipynb
│   ├── Categorical.ipynb
│   ├── Distribution.ipynb
│   ├── Matrixplot.ipynb
│   ├── Regressionplot.ipynb
│   ├── plotlyandcufflinks.ipynb
│   └── IPL_Project.ipynb
│
├── ML PART 1/                # ML Part 1 - EDA & Preprocessing
│   ├── heart.ipynb
│   ├── heart.csv
│   ├── Insurance.ipynb
│   └── insurance.csv
│
├── ML PART 2/                # ML Part 2 - EDA & Preprocessing
│   ├── insurance_eda.ipynb
│   └── insurance.csv
│
├── data/
│   └── IPL.csv
│
└── README.md
```

---

## 🐍 Python Revision

**Files:** `PYTHON REVISION/`

Topics covered:
- Variables, data types (int, float, bool, None, complex)
- Type conversion & string methods
- f-strings
- Arithmetic, comparison, logical & assignment operators
- Identity and membership operators
- Input / Output
- If-else, elif chains, nested if, ternary operator
- Practical examples: BMI calculator, login system, calculator
- While loops, mini-game logic
- Dictionaries — key-value pairs, methods, iteration
- OOP — classes, objects, `__init__`, `self`, inheritance, encapsulation

---

## 📊 Statistics

**Files:** `Stats/`

| File | Topic | Dataset | Result |
|------|-------|---------|--------|
| `t_test.ipynb` | One Sample T-Test | Custom height data | Accept H₀ |
| `two_sample_test.ipynb` | Two Sample T-Test | Group A vs B scores | Reject H₀ |
| `Z-TEST.ipynb` | Z-Test | Custom height data | Accept H₀ |
| `annova_test.ipynb` | ANOVA Test | Titanic (age vs pclass) | Reject H₀ — significant age difference across classes |
| `chi_square_test.ipynb` | Chi-Square Test | Titanic (gender vs survival) | Reject H₀ — gender significantly affects survival |
| `outliers.ipynb` | Outlier Detection | Custom dataset | IQR & Z-score methods |

**Key concepts practiced:** Null hypothesis, p-value, alpha = 0.05, degrees of freedom, f-statistic, chi2 statistic, contingency tables.

---

## 🔢 NumPy

**Files:** `numpy/`

Topics covered:
- Array creation, reshaping, indexing, slicing
- Broadcasting
- Mathematical operations
- Statistical functions (mean, std, var)

---

## 🐼 Pandas

**Files:** `Pandas/`

Topics covered:
- DataFrame creation, reading CSV files
- Indexing & slicing — loc, iloc
- Filtering & conditional selection
- Handling missing values — dropna, fillna
- GroupBy — aggregation, sorting
- Merging, joining & concatenation
- Pivot tables
- Apply & lambda functions
- Feature extraction project
- Countries dataset analysis

---

## 📈 Data Visualization

**Files:** `Data Visualization/`

| File | Library | Charts Covered |
|------|---------|----------------|
| `matplotlib.ipynb` | Matplotlib | Line plot, bar chart, scatter plot, basic customization |
| `Categorical.ipynb` | Seaborn | Countplot, barplot, boxplot, violinplot, stripplot |
| `Distribution.ipynb` | Seaborn | Histplot, KDE plot, distplot, rugplot |
| `Matrixplot.ipynb` | Seaborn | Heatmap, clustermap, correlation matrix |
| `Regressionplot.ipynb` | Seaborn | Regplot, lmplot, residual plots |
| `plotlyandcufflinks.ipynb` | Plotly & Cufflinks | Interactive charts, iplot |
| `IPL_Project.ipynb` | Pandas + Seaborn | IPL cricket data analysis |

**Key concepts practiced:** Figure & axes, subplots, color palettes, annotations, interactive visualizations.

---

## 🏏 IPL Data Analysis Project

**File:** `Data Visualization/IPL_Project.ipynb`
**Dataset:** `data/IPL.csv`

A real-world data analysis project on Indian Premier League (IPL) cricket data.

Topics covered:
- Data loading & exploration
- Cleaning & preprocessing IPL dataset
- Visualizing team performance, top run scorers, wicket takers
- Match result analysis
- Season-wise trends using Pandas + Matplotlib + Seaborn

---

## 🤖 Machine Learning

### ML Part 1 — Heart Disease EDA & Preprocessing

**File:** `ML PART 1/heart.ipynb`
**Dataset:** `ML PART 1/heart.csv`

Topics covered:
- Exploratory Data Analysis on heart disease dataset
- Data cleaning — handling nulls, duplicates, data types
- Visualization — histplots, boxplots, countplots, correlation heatmap
- Encoding categorical features
- Feature scaling & selection
- Identifying key predictors of heart disease

### ML Part 1 — Insurance EDA & Preprocessing

**File:** `ML PART 1/Insurance.ipynb`
**Dataset:** `ML PART 1/insurance.csv`

Topics covered:
- Exploratory Data Analysis on insurance dataset
- Data cleaning — removing duplicates, checking nulls
- Encoding — binary mapping, one-hot encoding
- Feature engineering — BMI categories using `pd.cut()`
- Feature scaling — StandardScaler on numeric columns
- Feature selection — Pearson Correlation & Chi-Squared Test

### ML Part 2 — Insurance EDA Deep Dive

**File:** `ML PART 2/insurance_eda.ipynb`
**Dataset:** `ML PART 2/insurance.csv`

Topics covered:
- Advanced EDA techniques
- In-depth feature analysis
- Model preparation & pipeline

---

## 📈 Progress Tracker

| Topic | Status |
|-------|--------|
| Python Basics | ✅ Done |
| Python Conditionals | ✅ Done |
| While Loop & Mini Game | ✅ Done |
| Dictionary | ✅ Done |
| OOP | ✅ Done |
| Basic Probability | ✅ Done |
| Two Sample Test | ✅ Done |
| Covariance & Correlation | ✅ Done |
| Statistical Tests (T, Z, ANOVA, Chi-Square) | ✅ Done |
| Outlier Detection | ✅ Done |
| Pandas | ✅ Done |
| NumPy | ✅ Done |
| Data Visualization | ✅ Done |
| IPL Data Analysis Project | ✅ Done |
| ML Part 1 — Heart Disease EDA | ✅ Done |
| ML Part 1 — Insurance EDA | ✅ Done |
| ML Part 2 — Insurance EDA Deep Dive | ✅ Done |
| ML Part 3 | 🔜 Upcoming |
| ML Part 4 | 🔜 Upcoming |

---

## 🏆 Certificates

| Certificate | Issuer | Date |
|-------------|--------|------|
| Data Analytics Job Simulation | Deloitte × Forage | June 2026 |
| Claude 101 | Anthropic | 2026 |
| Fundamentals of Drone Systems & AI/ML for Drone Vision | IIT Goa × MeitY | Jan 2026 |
| Data Science & Analytics | HP LIFE × HP Foundation | June 2025 |
| Develop Your Brand Using Social Media | IBM SkillsBuild | Dec 2024 |

---

## 🛠️ Libraries Used

```python
numpy       pandas      matplotlib
seaborn     plotly      scipy
sklearn     cufflinks
```

---

## 🌱 Daily Habit

- 📝 Study 2 topics daily (2 hrs each)
- 💻 Code every concept, don't just read
- 🟩 Push to GitHub every single day
- 🔗 Document progress on LinkedIn

---

## 🔗 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Amruta_Dabholkar-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/amruta-dabholkar-2a51a4378/)
[![GitHub](https://img.shields.io/badge/GitHub-Amruta--Dabholkar-black?style=flat&logo=github)](https://github.com/Amruta-Dabholkar)

---

*"Consistency beats intensity. 2 hours daily beats 10 hours once a week."* 🔥
