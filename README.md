# Breast Cancer Prediction
This project was an attempt to use an CNN model against images to detect the occurence of breast cancer.

## Summary 
It used histopathological images as part of a modified version of the PCam dataset. It was pulled from a Kaggle competition.
 
The model was a CNN that looked for a single pixel of cancer in a 32px x 32px region of the image.

## Notebooks
breast-cancer-eda-gpu.ipynb: Exploratory analysis, attempting to use GPU on Google Colab
breast-cancer-eda.ipynb: Exploratory analysis
breast_cancer_success.ipynb: Full notebook, include some of the EDA from above. Makes use of a GPU on Colab. Also contains the model and the results of the model
