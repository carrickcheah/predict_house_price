## Predict housing price with Decision Forest<br>
Using Decision Forests to predict housing prices helps in accurately estimating property values, aiding people in making informed decisions based on comprehensive data analysis.<br>
<br>
<br>
Abstract<br>
Using TensorFlow Decision Forests, we predict housing prices by training a Random Forest model on a dataset. This process involves data preprocessing, model training, and evaluation.
<br>
<br>
Introduction<br>
This notebook demonstrates the use of TensorFlow Decision Forests to predict housing prices, showcasing the entire workflow from data preprocessing to model evaluation.
<br>
<br>
Libraries Used<br>
We utilize several libraries including TensorFlow, TensorFlow Decision Forests, pandas, NumPy, seaborn, and matplotlib for data handling, model training, and visualization.
<br>
<br>
Role of Decision Forests<br>
TensorFlow Decision Forests plays a crucial role by providing a robust Random Forest model, which is trained on housing data to predict sale prices.
<br>
<br>
Performance Metrics<br>
The model’s performance is evaluated using Mean Squared Error (MSE), providing insights into the accuracy and reliability of the predictions. The model achieved an MSE of 1173813248.0000 on the validation set.
<br>
<br>




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
<br>
Acknowledgments: Dataset, The Ames Housing dataset was compiled by Dean De Cock for use in data science education.  <br>
