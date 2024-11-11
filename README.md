# Anoma
<b>Predicting the Machine failure
<b>Load and Explore Data: Import required libraries and read the dataset from an Excel file to understand data structure and check for missing values.
Handle Missing Values: Calculate and print the proportion of missing values in each column to assess data quality.
Data Cleaning: Drop unnecessary columns (e.g., 'time' and 'y.1') to streamline the dataset for analysis.
Visualize Data: Use a histogram plot to examine the distribution of 'x19' with respect to the target variable 'y', helping to understand its relationship with the target class.
Separate Features and Target: Define X as the feature set and y as the target variable.
Scale Features: Apply standard scaling to the features using StandardScaler to normalize data and improve model performance.
Split Dataset: Divide the data into training and testing sets (80/20 split) to enable evaluation on unseen data.
Save Processed Data: Save the training and testing data splits to CSV files for future use.
Define Model: Initialize a RandomForestClassifier for classification tasks.
Hyperparameter Tuning: Define a parameter grid and use RandomizedSearchCV to perform hyperparameter tuning on the Random Forest model with 3-fold cross-validation.
Train the Model: Train the model using the best parameters found in the randomized search.
Evaluate Model Performance: Predict and calculate accuracy on both training and testing sets to assess the model's performance.
Save the Model: Save the trained model using joblib for future deployment or further analysis.
Result Interpretation: Print out the best hyperparameters and accuracy scores on the training and testing sets to document model performance.
