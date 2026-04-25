# Wine Quality Assessment Using Data Mining Techniques

## Project Overview

This project builds multi-class classification models for predicting wine quality using the UCI Wine Quality dataset. The original wine quality score is converted into three categories:

- Low quality: quality < 5
- Medium quality: 5 <= quality <= 6
- High quality: quality > 6

The red and white wine datasets are modeled separately. The project compares Logistic Regression, Support Vector Machine, Random Forest, Gradient Boosting, and XGBoost. Class imbalance is handled using stratified train-test splitting and SMOTE.

## Files Included

- `RamitaRathore_Project_Phase3.ipynb` - Main Jupyter Notebook containing preprocessing, modeling, SMOTE experiments, evaluation, and visualizations.
- `RamitaRathore_FinalReport.pdf.pdf`- Final project report.
- `DataMining_Project_README.md` - Instructions for running the project.
- `RamitaRathore_Project_Demo` - Project demo.

## Required Software

The project was developed using Python and Jupyter Notebook.

All the libraries that need to be imported are in the seconc cell of the notebook provided. Please install the required libraries using command '!pip {library}' inside the jupyter notebook. A CPU runtime is sufficient to run the notebook.

## How to Run the Project

1. Download the dataset files from: https://archive.ics.uci.edu/dataset/186/wine+quality
3. Upload and open Jupyter Notebook in Google Colab or desired IDE.
2. Make sure the following dataset files are in the same folder as the notebook:
   - `winequality-red.csv`
   - `winequality-white.csv`
4. Open `RamitaRathore_Project_Phase3.ipynb`.
5. Run the notebook from top to bottom.
6. The notebook will:
   - Load the red and white wine datasets.
   - Convert original quality scores into Low, Medium, and High classes.
   - Perform preprocessing and feature scaling.
   - Train multiple machine learning models.
   - Apply SMOTE for class imbalance handling.
   - Generate evaluation metrics and confusion matrices.

## Expected Outputs

The notebook produces:

- Class distribution plots
- PCA heatmaps / feature-loading visualizations
- Model performance metrics
- Confusion matrices for red and white wine models
- Comparisons before and after SMOTE

## Notes

- The red and white wine datasets are evaluated separately.
- Accuracy should not be interpreted alone because the dataset is imbalanced.
- Balanced accuracy and macro F1-score are especially important because they better reflect model performance on minority classes.

## Dataset Source

UCI Machine Learning Repository: Wine Quality Dataset  
https://doi.org/10.24432/C56S3T

## Reference

P. Cortez, A. L. Cerdeira, F. Almeida, T. Matos, and J. Reis, “Modeling
wine preferences by data mining from physicochemical properties,”
Decis. Support Syst., vol. 47, pp. 547–553, 2009. [Online]. Available:
https://api.semanticscholar.org/CorpusID:2996254