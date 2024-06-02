##Predict housing price with Decision forest


*Step 1: Import the necessary libraries.
*Step 2: Load the training data from the specified file path.
*Step 3: Preprocess the data by dropping rows with missing values and separating the label (SalePrice).
*Step 4: Convert the preprocessed pandas DataFrame into a TensorFlow dataset suitable for training.
*Step 5: Initialize and compile a RandomForest model for regression.
*Step 6: Train the model using the training dataset.
*Step 7: Load the test data from the specified file path and separate the 'Id' column.
*Step 8: Convert the test data into a TensorFlow dataset.
*Step 9: Use the trained model to predict house prices on the test dataset.
*Step 10: Create a submission DataFrame with the 'Id' and predicted 'SalePrice' values and save it to a CSV file.
*Step 11: Display the first few rows of the submission DataFrame.
