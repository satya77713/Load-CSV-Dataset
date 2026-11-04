# Load a CSV Dataset Using Pandas

## 📌 Overview

This project demonstrates how to load a CSV dataset using Python and Pandas. The notebook uses the Iris dataset to practice importing tabular data and viewing its first and last five records.

This project was completed as part of the **AI & ML Internship at Veda Technology** using Google Colab.

## 🎯 Objective

Learn how to import a real-world dataset into Python using Pandas and display records to verify that the dataset has loaded correctly.

## 🛠️ Tools and Technologies

- Python
- Pandas
- NumPy
- Google Colab
- CSV dataset

## 📊 Dataset

The project uses the **Iris dataset**, a commonly used dataset for learning data analysis and machine learning.

The notebook loads the CSV file from:

```python
/content/Iris.csv
```

Make sure the file is uploaded to the correct location in Google Colab before running the notebook.

## 💻 Implementation

### 1. Import the libraries

```python
import numpy as np
import pandas as pd
```

### 2. Load the CSV dataset

```python
df = pd.read_csv("/content/Iris.csv")
```

### 3. Display the first five records

```python
df.head()
```

### 4. Display the last five records

```python
df.tail()
```

## ▶️ How to Run

1. Open [Google Colab](https://colab.research.google.com/).
2. Upload `Load_CSV_Dataset.ipynb` to Google Colab.
3. Upload `Iris.csv` to the Colab environment.
4. Confirm that the dataset is available at `/content/Iris.csv`.
5. Run each notebook cell.
6. Review the first and last five records displayed by Pandas.

## 📚 Learning Outcomes

- Learned how to import NumPy and Pandas.
- Practiced loading CSV files using `pd.read_csv()`.
- Learned to display the first five records using `head()`.
- Learned to display the last five records using `tail()`.
- Gained practical experience working with tabular data in Google Colab.

## 🏁 Conclusion

This project provides hands-on practice in loading a CSV dataset and exploring its records using Pandas. These are fundamental steps in data analysis and machine learning workflows.

## 👨‍💻 Internship Details

- **Organization:** Veda Technology
- **Track:** AI & ML
- **Project:** Load a CSV Dataset
- **Dataset:** Iris
- **Platform:** Google Colab
