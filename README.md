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
