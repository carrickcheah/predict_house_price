## Predict housing price with Decision Forest<br>
Using Decision Forests to predict housing prices helps in accurately estimating property values, aiding people in making informed decisions based on comprehensive data analysis.<br>
<br>
Libaries: TensorFlow, Matplotlib, Seaborn<br>
Dataset: Acknowledgments, The Ames Housing dataset was compiled by Dean De Cock for use in data science education.  <br>

<br>
* Step 1: Import the necessary libraries.<br>
* Step 2: Load the training data from the specified file path.<br>
* Step 3: Preprocess the data by dropping rows with missing values and separating the label (SalePrice).<br>
* Step 4: Convert the preprocessed pandas DataFrame into a TensorFlow dataset suitable for training.<br>
* Step 5: Initialize and compile a RandomForest model for regression.<br>
* Step 6: Train the model using the training dataset.<br>
* Step 7: Load the test data from the specified file path and separate the 'Id' column.<br>
* Step 8: Convert the test data into a TensorFlow dataset.<br>
* Step 9: Use the trained model to predict house prices on the test dataset.<br>
* Step 10: Create a submission DataFrame with the 'Id' and predicted 'SalePrice' values and save it to a CSV file.<br>
* Step 11: Display the first few rows of the submission DataFrame.<br>
