
# 22CDL72 - Statistical Machine Learning for Data Science Lab

This repository contains all experiments for the VTU 22CDL72 lab course.  
The programs are written in Python and can be run in Jupyter Notebook or Google Colab.

---

## Experiments Included
1. Percentile and Interquartile Range (IQR)  
2. Housing Price Visualization  
3. Smartphone Dataset Correlation  
4. Sampling Distribution of Mean  
5. Weight of Evidence (WOE) Encoding  
6. Bag of Words and TF-IDF Encoding  

---

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/naman-upreti/22cds72_lab_experiment.git

2. Open any experiment file in **Jupyter Notebook** or **Google Colab**.
3. Run each cell step by step.

---

## Using Kaggle Datasets with KaggleHub

KaggleHub is a Python library that helps you download datasets directly from Kaggle.

### Installation

```bash
pip install kagglehub
```

### Usage

```python
import kagglehub
import pandas as pd

# Download dataset from Kaggle
path = kagglehub.dataset_download("sonialikhan/titanic-data-set")

# Load dataset
df = pd.read_csv(f"{path}/titanic.csv")
print(df.head())
```

### Explanation

* `dataset_download("owner/dataset-name")` downloads the dataset and returns the path.
* You can load the CSV file from that path using `pandas.read_csv()`.

---

## Requirements

* Python 3.8 or higher
* pandas
* numpy
* seaborn
* matplotlib
* scikit-learn
* kagglehub

Install all using:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn kagglehub
```

---

## Author

Naman Upreti
B.E. CSE (Data Science)

```

---

Would you like me to make this version automatically include your **experiment notebook file names** (from your repo) in the README too?
```
