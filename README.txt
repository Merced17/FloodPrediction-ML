Flood Prediction Using K-Nearest Neighbors (KNN) classifier
This project demonstrates the use of Machine Learning techniques, specifically KNN classifier, to predict flood occurrences based on environmental and social data.

Files in the Repository
Flood_SLP_KNN.ipynb

A Jupyter Notebook containing the code for data preprocessing, model training, evaluation, and prediction.
Training.csv

A dataset used for training the models.
DataPred.csv

A dataset used for making predictions.
Requirements
To run the code, ensure you have the following Python libraries installed:

numpy
pandas
matplotlib
seaborn
scikit-learn

How to Use
1. Download the repository and open the Flood_SLP_KNN.ipynb file in a Jupyter Notebook environment (e.g., JupyterLab, Google Colab).
2. Ensure Training.csv and DataPred.csv are in the same directory as the notebook.
3. Follow the steps in the notebook:
* Load and preprocess the data.
* Train the machine learning models.
* Evaluate their performance.
* Use DataPred.csv to generate predictions.

Outputs
1. The notebook generates a feature importance chart, confusion matrix, classification metrics, ROC curve, and predictions for the dataset in DataPred.csv.
2. Outputs include a CSV file with predicted flood occurrences and probabilities:
* Flood1_Predictions2.csv
* probabilities.csv

Acknowledgments
This project is part of a study on urban flood exposure in San Luis Potosí (SLP), Mexico using machine learning techniques.
