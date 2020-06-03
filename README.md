# ML-models-for-predicting-partition-coefficients
Various Machile Learning Models are trained using **scikit-learn** on the dataset provided by <a href="http://https://pubs.acs.org/doi/10.1021/acs.jcim.6b00778"
    title="With a Title">this</a> paper to predict partition coefficients logP<sub>(oct/water)</sub>. 
## Features:
RDkit was used to extract feature from SMILES string. There are total of 13 features.
## Different Models Trained:
There are 6 models in total trained using scikit-learn module: KNN, Ridge, Lasso, Kernelized SVM, Random Forests and MLP.
The MLP model with a 1000 neurons layer has the highest score with minimal variance.
