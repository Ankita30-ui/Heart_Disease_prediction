# Report

# Heart_Disease_prediction


# Prerequisites
What things you need to install the software and how to install them:

Python 3.6
This setup requires that your machine has python 3.6 installed on it. you can refer to this url https://www.python.org/downloads/ to download python. Once you have python downloaded and installed, you will need to setup PATH variables (if you want to run python program directly, detail instructions are below in how to run software section). To do that check this: https://www.pythoncentral.io/add-python-to-path-python-is-not-recognized-as-an-internal-or-external-command/.
Setting up PATH variable is optional as you can also run program without it and more instruction are given below on this topic.
Second and easier option is to download anaconda and use its anaconda prompt to run the commands. To install anaconda check this url https://www.anaconda.com/download/
You will also need to download and install below 3 packages after you install either python or anaconda from the steps above
Sklearn (scikit-learn)
numpy
scipy
if you have chosen to install python 3.6 then run below commands in command prompt/terminal to install these packages
pip install -U scikit-learn
pip install numpy
pip install scipy
if you have chosen to install anaconda then run below commands in anaconda prompt to install these packages
conda install -c scikit-learn
conda install -c anaconda numpy
conda install -c anaconda scipy
# Dataset used
The data source used for this project is Heart.csv
The heart.csv Data Set contains attributes like: age, sex, cp, trestbps, chol, fbs, restecg, thalach, exang, oldpeak, slope, ca, thal, target.

# Applying algorithms
K Nearest Neighbors,
Random Forest Classifier,
Decision Tree Classifier,
Support Vector Classifier,
Naive Bayes

# Accuracy comparision
According to the accuracy graph, random forest works the best.
