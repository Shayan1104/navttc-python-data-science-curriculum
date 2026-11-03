# NAVTTC Python & Data Science Curriculum

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB.svg?logo=python&logoColor=white)](https://www.python.org/)
[![NumPy](https://img.shields.io/badge/NumPy-1.26+-013243.svg?logo=numpy&logoColor=white)](https://numpy.org/)
[![Pandas](https://img.shields.io/badge/Pandas-2.2+-150458.svg?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![SciPy](https://img.shields.io/badge/SciPy-1.12+-8CAAE6.svg?logo=scipy&logoColor=white)](https://scipy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-3.8+-11557c.svg)](https://matplotlib.org/)

A structured 5-week practical curriculum covering Python core concepts, descriptive statistics from first principles, multidimensional computing with NumPy, exploratory data analysis with Pandas, and introductory predictive modeling. Developed as part of the National Vocational and Technical Training Commission (NAVTTC) training initiative.

---

## 📚 Curriculum Structure

```
NAVTTC-Task/
├── Week1/                     # Python Core Programming & Control Flow
├── Week-2/                    # Exception Handling & Foundational Statistics
├── Week-3,4/                  # Vectorized Computing (NumPy) & Data Analysis (Pandas)
│   └── requirements.txt       # Dependencies (numpy, pandas)
└── Week-5/                    # Introduction to Predictive Machine Learning
```

---

## 🗓️ Weekly Modules & Learning Outcomes

### Week 1 — Python Programming Fundamentals & Data Structures
Covers core language syntax, control structures, and essential data types:
- **Conditionals & Flow**: `ifelse.py`, `elseif.py`, `loops.py`, `whileloop.py`, `looptechni.py`
- **Data Structures**: `listdata.py`, `tuple.py`, `setdata.py`, `dictionary.py`, `sqrrlcomp.py`
- **String Manipulation**: `strings.py`, `storeinp.py`
- **Practical Math Scripts**: `addingnum.py`, `kilotomiles.py`, `temp.py`, `triangle.py`, `squareroot.py`, `quadratic.py`

### Week 2 — Robust Error Handling & Descriptive Statistics
Focuses on writing fault-tolerant Python and implementing foundational statistical formulas from scratch without black-box packages:
- **Error Handling**: `exception.py`, `exceptionwith.py` (custom exceptions, try/except/finally patterns)
- **Descriptive Statistics**:
  - `mean.py`: Calculation of central tendency
  - `median.py`: Median computation handling both even and odd length sequences
  - `standarddeviation.py`: Variance and standard deviation implementation

### Week 3 & 4 — Scientific Computing with NumPy & Data Analysis with Pandas
Mastery of high-performance array computing and tabular data manipulation:
- **NumPy Matrix & Vector Operations**:
  - Array initialization, slicing, and multidimensional indexing (`array.py`, `indexing.py`, `numpy_slicing.py`, `numpy_shape.py`)
  - Memory behavior and views (`numpy_copy_view.py`, `numpy_data_types.py`)
  - Dimensionality manipulation (`numpy_reshape.py`, `numpy_joining.py`, `numpy_splitting.py`)
  - Element discovery, filtering, and sorting (`numpy_searching.py`, `numpy_sorting.py`)
  - Random number generators and sampling (`numpy_random.py`, `numpy_iteration.py`)
- **Pandas Data Exploration & Cleaning**:
  - Series & DataFrame foundations (`pandas_basics.py`, `pandas_series.py`, `pandas_dataframes.py`)
  - CSV file I/O and schema inspection (`pandas_csv.py`, `pandas_analyzing.py`)
  - Missing value imputation and null handling (`pandas_cleaning.py`)
  - Statistical correlation matrices (`pandas_correlations.py`)

### Week 5 — Introduction to Machine Learning
Foundations of predictive modeling and trend estimation:
- **Linear Regression (`linear.py`)**: Fit bivariate linear regression models using `scipy.stats.linregress` and visualize scatter points and best-fit trend lines using `matplotlib`.
- **Logistic Regression (`logicalreg.py`)**: Foundational concepts in classification and decision boundary mapping.

---

## 🚀 Getting Started

### 1. Prerequisites
- Python 3.10, 3.11, or 3.12 installed on your machine.

### 2. Environment Setup
```bash
# Clone the repository
git clone https://github.com/Shayan1104/navttc-python-data-science-curriculum.git
cd navttc-python-data-science-curriculum

# Create and activate virtual environment
python -m venv .venv
# On Windows:
.venv\Scripts\activate
# On macOS/Linux:
source .venv/bin/activate

# Install required packages for Weeks 3, 4, and 5
pip install numpy pandas scipy matplotlib
```

### 3. Running Exercises
Each script is completely self-contained and can be executed directly:
```bash
# Example: Run Quadratic Formula Solver (Week 1)
python Week1/quadratic.py

# Example: Run Standard Deviation Calculator (Week 2)
python Week-2/standarddeviation.py

# Example: Run Pandas Data Cleaning (Weeks 3 & 4)
python "Week-3,4/pandas_cleaning.py"

# Example: Run Linear Regression Fit & Plot (Week 5)
python Week-5/linear.py
```
