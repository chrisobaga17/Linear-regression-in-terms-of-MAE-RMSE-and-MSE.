# LINEAR REGRESSION ANALYSIS
Prerequisites
The script requires the following Python packages to be installed:

pandas
numpy
scikit-learn
matplotlib
Installing
Use the package manager pip to install the required packages:

Copy code
pip install pandas numpy scikit-learn matplotlib
Usage
Run the Python script "insurance_linear_regression.py" to load the dataset, perform data preprocessing, train the model and evaluate its performance.

The script first imports necessary packages, reads the dataset and displays its histogram. It then performs a scatter plot of BMI vs. charges and a residuals plot to check the linearity assumption of the model.

After that, the script performs data preprocessing by separating the features and target variable, and converting categorical features to numerical using one-hot encoding. The data is split into training and testing sets with a test size of 20%.

A Linear Regression model is then trained on the training set and used to predict insurance charges on the testing set. The script evaluates the model's performance using Mean Absolute Error, Mean Squared Error, and R^2 Score, which are displayed on the console.

Dataset
The "insurance.csv" dataset used for this project contains 1338 instances with the following columns:

age: age of the primary beneficiary
sex: gender of the primary beneficiary (male or female)
bmi: Body Mass Index (BMI) of the primary beneficiary
children: number of children covered by the health insurance
smoker: smoking status of the primary beneficiary (yes or no)
region: the beneficiary's residential area in the US (northeast, northwest, southeast, southwest)
charges: medical insurance costs billed to the beneficiary
