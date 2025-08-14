# Breast Cancer Detection

This project focuses on the detection of breast cancer using various machine learning algorithms. The dataset used is the [Breast Cancer Wisconsin (Diagnostic) Data Set](https://www.kaggle.com/datasets/utkarshx27/breast-cancer-wisconsin-diagnostic-dataset).

## Features

- Data preprocessing (handling missing values, outlier treatment, normalization)
- Exploratory Data Analysis (EDA) and visualization
- Model training and evaluation using:
  - Random Forest
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Decision Tree
  - XGBoost
  - Voting Ensemble
  - Stacking Ensemble (combining all above models)
- Model comparison with accuracy plots

## Project Structure

```
Breast_Cancer_Detection/
│
├── Dataset/
│   └── data.csv
├── NotebookFile/
│   └── BreastcancerDetection.ipynb
├── Readme.MD
```

## How to Run

1. **Install dependencies**  
   Make sure you have Python 3.x installed.  
   Install required packages:
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost
   ```

2. **Dataset**  
   Place the `data.csv` file inside the `Dataset` folder.

3. **Run the Notebook**  
   Open `NotebookFile/BreastcancerDetection.ipynb` in Jupyter Notebook or VS Code and run all cells.

## Results

- The notebook provides accuracy, classification report, and confusion matrix for each model.
- A comparison bar plot shows the performance of all models, including the stacking ensemble.

## References

- [UCI Machine Learning Repository: Breast Cancer Wisconsin (Diagnostic) Data Set](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)
- [Scikit-learn Documentation](https://scikit-learn.org/)
- [XGBoost Documentation](https://xgboost.readthedocs.io/)

---
```<!-- filepath: f:\Research\Breast_Cancer_Detection\Readme.MD -->

# Breast Cancer Detection

This project focuses on the detection of breast cancer using various machine learning algorithms. The dataset used is the [Breast Cancer Wisconsin (Diagnostic) Data Set](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29).

## Features

- Data preprocessing (handling missing values, outlier treatment, normalization)
- Exploratory Data Analysis (EDA) and visualization
- Model training and evaluation using:
  - Random Forest
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Decision Tree
  - XGBoost
  - Voting Ensemble
  - Stacking Ensemble (combining all above models)
- Model comparison with accuracy plots

## Project Structure

```
Breast_Cancer_Detection/
│
├── Dataset/
│   └── data.csv
├── NotebookFile/
│   └── BreastcancerDetection.ipynb
├── Readme.MD
```

## How to Run

1. **Install dependencies**  
   Make sure you have Python 3.x installed.  
   Install required packages:
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost
   ```

2. **Dataset**  
   Place the `data.csv` file inside the `Dataset` folder.

3. **Run the Notebook**  
   Open `NotebookFile/BreastcancerDetection.ipynb` in Jupyter Notebook or VS Code and run all cells.

## Results

- The notebook provides accuracy, classification report, and confusion matrix for each model.
- A comparison bar plot shows the performance of all models, including the stacking ensemble.

## References

- [UCI Machine Learning Repository: Breast Cancer Wisconsin (Diagnostic) Data Set](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)
- [Scikit-learn Documentation](https://scikit-learn.org/)
- [XGBoost Documentation](https://xgboost.readthedocs.io/)

---