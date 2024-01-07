# PredictingSchizophrenia
The objective of this project is to utilize grey matter measurements obtained from structural MRI brain scans to create a predictor that can differentiate between schizophrenic patients and healthy controls. This project is part of a [UCL RAMP](https://ramp.studio/problems/brain_anatomy_schizophrenia) challenge. 

I am comparing three models: 
- Logistic Regression
- Random Forrest
- MultiLayerPerceptron

The repository contains a Jupyter Notebook (as ipynb and HTML) and a Report. Please find all details in the report :)

## Getting Started

To run the notebook locally just install all required packages.

`pip install -r requirements.txt`

Since Github blocks large files please download the high dimensional VBM data (`train_vbm.npz` and `test_vbm.npz`) from the starting kit on the [challenge website](https://ramp.studio/problems/brain_anatomy_schizophrenia). Find all details on how to get started with the code on the website as well.
