# Student Performance ML

Predicting student academic performance using classic machine learning models. This project explores how features such as study habits, demographics, and prior scores relate to student outcomes, and trains several models to predict performance.

## Overview

Using a tabular dataset of student records, the notebook walks through data loading, exploratory analysis, preprocessing, model training, and evaluation. Multiple machine learning algorithms are compared to see which best predicts student performance.

## Repository Structure

| File | Description |
|------|-------------|
| `Sudent Perfomance/Student_perfomance.ipynb` | Main notebook: EDA, preprocessing, model training and evaluation |
| `Sudent Perfomance/student_data.csv` | Dataset of student records used for training |

## Workflow

1. **Load data** from `student_data.csv`
2. **Explore** the data (distributions, correlations, missing values)
3. **Preprocess** features (encoding categorical variables, scaling)
4. **Train** several ML models
5. **Evaluate** and compare model performance

## Getting Started

```bash
# Clone the repository
git clone https://github.com/Nithindesu/Student-Performance-ML.git
cd Student-Performance-ML

# Install dependencies
pip install numpy pandas scikit-learn matplotlib seaborn jupyter

# Launch the notebook
jupyter notebook "Sudent Perfomance/Student_perfomance.ipynb"
```

## Tech Stack

- Python
- scikit-learn
- pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook
