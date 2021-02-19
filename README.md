## Machine-Learning - Exoplanet Exploration 



Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

Use Jupyter Notebook, Pandas, Matplotlib, and Scikit-Learn to create machine learning models capable of classifying candidate exoplanets from the raw dataset.

Preprocess the Data

 - Preprocess the dataset prior to fitting the model.
 - Perform feature selection and remove unnecessary features.
 - Use MinMaxScaler to scale the numerical data.
 - Separate the data into training and testing data.

Tune Model Parameters

 - Use GridSearch to tune model parameters.
 - Tune and compare at least two different classifiers.


## Analysis
  
Before starting to build models, I cleaned data, removed all null values, and took out any insignificant variables from the dataset.

### First Model - K-Nearest Neighbors Model

For this model, while k is 13, testing accuracy equals to 0.790


### Second Model - Support Vector Machine Linear Classifier Model

Training Data Score: 0.8245204336947456

Testing Data Score: 0.8199099549774888

Test Accuracy: 0.823

### Third Model - Deep Learning Model

Model Loss: 0.29958380257087447 

Model Accuracy: 0.8514257073402405


Among these three models, Deep Learning model has the highest accuracy rate with 0.851425.







