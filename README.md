# Solubility
 Solubility is a fundamental concept in chemistry, referring to the ability of a substance to dissolve
 in a solvent. It plays a crucial role in various scientific disciplines and industrial applications. This
 project focuses on predicting the solubility of substances based on certain attributes of the compound such
 as the smiles, number of rings, molecular weight and so on and so forth.

 # Features
 The smiles categorical values were converted into numerical values in order to aid on the quality of the model
 and the important EDA techniques were explored to gauge the state of the data. Most values were dominant
 over the other so the implementation of normalization in all features was implemented using MinMaxScaler. The
 dataset was split into 80% of training data and 20% of testing data. Linear regression was utilized to construct
 this model.

 The features of the dataset included:
 - **Minimum_Degree**
 - **Molecular_Weight**
 - **Number_of_H_Bond_Donors**
 - **Number_of_Rings**
 - **Number_of_Rotatable_Bonds**
 - **Polar_Surface_Area**
 - **Smiles**

### Requirements
To run the project, ensure you have the following installed:

- **Python 3.8+**
- **Libraries**
  - **pandas**
  - **numpy**
  - **matplotlib**
  - **seaborn**
  - **scikit-learn**
  - **rdkit**

### Results
Below is the evaluation performance of the model through the analysis of the Coefficients, Intercepts, Mean squared error,
Root mean squared error (RMSE) and the Coefficient of determination (R^2). As can be seen below, the model achieved an accuracy of
73% with reference being Coefficient of determination (R^2):

- **Coefficients** : [[-1.20011985 -5.16810746  1.24094493 -3.11844323 -3.24734142  7.99989535   -5.16810746]]
- **Intercepts**   : [-0.16525597]
- **Mean squared error** : 1.202
- **Root mean squared error (RMSE)** : 1.096
- **Coefficient of determination (R^2)** : 0.734

### Future Work
  - Explore other machine learning techniques for better performance.
  - Integrate the model into a web application for real-time predictions and live solubility examples.
