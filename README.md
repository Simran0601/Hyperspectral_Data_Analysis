# Hyperspectral Data Analysis for Vomitoxin Prediction

## 📜 Project Overview
This project aims to predict vomitoxin levels in corn samples using hyperspectral imaging (HSI) data. The analysis involves data preprocessing, dimensionality reduction, and training machine learning models (Random Forest and LSTM) to achieve accurate predictions. The results are compiled in a PDF report.

---

## 📁 Repository Structure
- **analysis.ipynb** - The main Jupyter Notebook for data analysis and model training.
- **report.pdf** - The detailed report with data insights, model performance, and conclusions.
- **requirements.txt** - List of Python dependencies to run the notebook.
- **TASK-ML-INTERN.csv** - Contains the data.

---

## 💻 How to Run the Notebook
1. **Clone the repository**:  
```shell
git clone <repository-url>
cd <repository-folder>
```

2. **Create a virtual environment (optional but recommended)**:  
```shell
python -m venv venv
source venv/bin/activate    # On MacOS/Linux
venv\Scripts\activate      # On Windows
```

3. **Install dependencies**:  
```shell
pip install -r requirements.txt
```

4. **Open the notebook**:  
```shell
jupyter notebook analysis.ipynb
```

5. Run all cells in the notebook to perform data preprocessing, model training, and evaluation.

---

## 📊 Results
- The Random Forest model with PCA (50 components) performed the best with an **R2 score of 0.74** and an **MAE of 2685.54**.
- The LSTM model showed poor performance, indicating the need for further feature engineering.

