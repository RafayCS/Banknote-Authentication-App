# Banknote-Authentication-App
This project uses a Support Vector Machine (SVM) model to tell if a banknote is real or fake using numbers taken from images.

Files:
1) banknote_authentication.ipynb – Main code in a Jupyter Notebook
2) BankNote_Authentication.csv – The dataset with the banknote details

Data is composed of the following:
Each banknote has:
i) variance
ii) skewness
iii) curtosis
iv) entropy
v) class – 1 = genuine, 0 = counterfeit

What the project does:
1) Looks at the data to understand it
2) Splits the data into training and testing sets
3) Trains an SVM model
4) Checks how well the model works using:
i) Accuracy
ii) Confusion matrix
iii) A report that shows precision, recall, and F1-score

To run:
1) Install the needed Python libraries: pip install pandas numpy matplotlib seaborn scikit-learn
2) Open the notebook in Jupyter

Data source:
https://archive.ics.uci.edu/ml/datasets/banknote+authentication

About me:
Author: Rafay Abubakar
Email: rafayabubakar456@gmail.com
Github: github.com/RafayCS
