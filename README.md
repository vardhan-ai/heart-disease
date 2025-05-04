# heart-disease
Data Loading and Exploration:

The script begins by importing essential libraries such as pandas, matplotlib, and scikit-learn. It loads a data file called 'heart.csv' with pandas and does some basic data exploration. It inspects data types, missing values, descriptive statistics, and makes histograms and a correlation matrix to know the structure and relationship of the data. It detects categories columns and prints unique values and count for each. 2. Data Preprocessing

The code treats categorical features by doing one-hot encoding for nominal features and mapping for ordinal features. It converts boolean columns to integers. 3. Model Training and Evaluation (Decision Tree):

It divides the data into training and test sets using train_test_split. It creates and trains a Decision Tree classifier on the training data. It predicts on the test data and checks the performance of the model using metrics such as accuracy, precision, recall, F1-score, and AUC. It plots the results with a confusion matrix. 4. Model Training and Evaluation (Random Forest):

It creates and trains a Random Forest classifier with given hyperparameters. 5. Feature Importance Analysis:

It retrieves and plots feature importances from the trained Random Forest model with a horizontal bar plot. It finds and prints the top 3 most important features. 6. Decision Tree Visualization (Optional):

It tries to plot the Decision Tree with export_graphviz and graphviz, but this section may need extra setup and libraries.
