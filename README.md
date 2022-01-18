# transaction-fraud-detection
Implementation of random forest that predicts its class (fraud or non-fraud) based on feature input

  This project explores a simulated data set of transaction data from kaggle. The jupyter notebook file contains data 
exploration and data visualization methods that help the user view and better understand the data. The data is then balanced
and selected features are converted into numeric values in order to fit the random forest classifier. Once the model is trained,
the user can enter values in the widget to predict the transaction's class.

To view the full notebook, please complete the following steps:
1. Download the data set "fraudTest.csv" from the link on kaggle: https://www.kaggle.com/kartik2112/fraud-detection
2. Download Miniconda from the link: https://docs.conda.io/en/latest/miniconda.html
3. Create a project folder and configure a conda environment
4. Install the following libraries:
  - Jupyter Notebook
  - Matplotlib
  - pandas
  - Numpy
  - Scikit-Learn
  - Plotly
  - Ipywidgets
  - IPython
  - Joblib
5. The files in this repository should then be moved to the root directory of the project folder
6. Open the jupyter notebook file and run all cells
7. Enter values in the input widgets, and press the predict button to view the model's outcome
