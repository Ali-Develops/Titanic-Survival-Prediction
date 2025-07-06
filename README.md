# 🛳️ Titanic Survival Prediction

This project predicts passenger survival on the Titanic using a logistic regression model. It involves data cleaning, visualization, survival analysis, and model training — all using Python in Google Colab.

> ✅ No Kaggle login required — upload the dataset manually during runtime.

---

## 📁 Dataset

Download the Titanic dataset manually from the following link:

🔗 [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)

- Extract the ZIP (`titanic.zip`) to get:
  - `train.csv`
  - `test.csv`
  - `gender_submission.csv`

> ⚠️ Make sure to **upload all three files** when prompted in the first code cell.

---

## 🚀 How to Use

Open the notebook in Google Colab and follow these steps:

### 🔹 Step 1: Upload Files
Upload the 3 CSV files using:
```python
from google.colab import files
uploaded = files.upload()
## 🔹 Step 2: Import Libraries

Essential Python libraries for data manipulation, visualization, and modeling:

```python
import numpy as np  
import pandas as pd  
import matplotlib.pyplot as plt  
import seaborn as sns  
import warnings  
warnings.simplefilter(action="ignore", category=RuntimeWarning)

# 🛳️ Titanic Survival Prediction

A short and practical notebook to predict survival on the Titanic using logistic regression in Python.

---

## 🔹 Step 3: Load Dataset

Load `train.csv`, `test.csv`, and `gender_submission.csv` using `pandas`.

---

## 🧹 Data Cleaning

- **Test Data**: Drop irrelevant columns, fill missing `Age` with mean  
- **Train Data**: Apply same cleaning; used for training the model

---

## 📊 Visualization (Train & Test)

- **Sex Distribution**: Bar & Pie Charts  
- **Age Distribution**: Histogram  
- **Age vs. Sex**: Violin Plot (Seaborn)

---

## 📈 Survival Analysis

- Compare survival counts and rates by gender  
- Visualize using bar charts

---

## 🤖 Model Training

- **Algorithm**: Logistic Regression  
- **Features**: `PassengerId`, `Pclass`, `Age`  
- **Split**: 75% train / 25% test  
- **Metric**: Accuracy

---

## 🧪 Prediction

- Predict on cleaned test dataset  
- Save results as `results.csv`  
- Show top 5 predictions

---

## 🧾 Accuracy Check (Optional)

- Compare model predictions with `gender_submission.csv`  
- Print accuracy score

---

## 📦 Output

- `results.csv`: Contains `PassengerId` & predicted `Survived` values  
- Combined dataset view (optional)

---

## ✅ Requirements

- Python packages:  
  - `pandas`  
  - `numpy`  
  - `matplotlib`  
  - `seaborn`  
  - `scikit-learn`

> 💡 Best run on **Google Colab** — no installation required.

