# Predicting-churn-rate-using-Deep-Learning-Alogorithm

The main aim of the project is to predict the churn rate using deep learning models. Here are the steps taken to complete the project: Importing the data, Feature Engineering, Graphs for visualization to know the spread of 
churn rates, Converting character to Integer features using one hot encoding, Scaling the values to [0,1] for easy calculations in Ml algorithms, Train_Test split, Identifying the Imbalance in dataset and used smote to 
balance the data, Created ANN algorithm to find the churn rate.

### Importing the data:
The dataset is collected from kaggle. This step involves loading the dataset into the environment. The dataset likely contains information about customers, Monthly billing, services used, type of service and other features.

### Feature Engineering:
Feature engineering in the project involves creating new features or modifying existing ones to improve the performance of machine learning models. This includes creating new variables from existing ones, handling missing values, transforming variables to better represent the underlying relationships in the data.

### Handling Missing Values: 
Rows with missing values in the "TotalCharges" column are dropped, and the column is converted to numeric using pd.to_numeric.

### Visualizations: 
Histograms are plotted to visualize the distribution of "tenure" and "MonthlyCharges" for customers with churn labeled as 'Yes' and 'No'. These visualizations help in understanding the relationship between these variables and customer churn.

### Handling Categorical Variables: 
The categorical variables with values 'No internet service' and 'No phone service' are replaced with 'No'. Then, the categorical variables are encoded using one-hot encoding 
to convert them into numerical format.
