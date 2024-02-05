
# Diabetes Prediction

Diabetes is a debilitating disease. Diagnosing it early can prevent onset of complications such as loss of eyesight and nerve damage. This repository supplies the code of developing an ML model that predicts whether an adult woman, of Pima Indian heritage residing in the US, will get Type 2 Diabetes. The prediction is made based on information about certain biochemical markers and aspects of family history.

## Implementation 

**ML Model Type**: Supervised 

**Algorithms**: 
- Logistic Regression      (81.3% AUC)
- Support Vector Machine   (75.9% AUC)
- Random Forest            (80.9% AUC)
- Multi-layer Perceptron   (60.9% AUC)

**Hyperparameter Tuning Tool**: Optuna 

Except Logistic Regression: Grid Search used.

## Requirements 

Python version 3.10.7 

Python libraries: pandas, numpy, sklearn, matplotlib, seaborn 

## Data 

All necessary data can be found in the "Files" folder of the repository or on Kaggle [https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database].

## Quick Start 

To reproduce the results, download the relevant script and load the corresponding data into a jupyter notebook; running the script will generate all relevant figures and tables. 

## Additional Information

The dataset comprises of 768 patient records collected from a sub-population residing near Phoenix, Arizona in the United States. The original dataset was first created by Smith et al. (1988) to predict diabetes in the high risk community.

It consists of 268 patients who have been diagnosed with diabetes along with 500 patients who are free of diabetes. This information is contained in the class label named 'Outcome'. Only participants whose age was at least 21 years were included. 

## Citation 

Smith JW, Everhart JE, Dickson WC, Knowler WC, Johannes RS. Using the ADAP learning algorithm to forecast the onset of diabetes mellitus. InProceedings of the annual symposium on computer application in medical care 1988 Nov 11 (p. 261). American Medical Informatics Association.

