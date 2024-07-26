## Dataset Description
We will use a synthetic dataset for this exercise. The dataset contains the following columns:

`CustomerID`: A unique identifier for each customer.

`Age`: The age of the customer.

`MonthlyCharge`: The monthly bill amount for the customer.

`CustomerServiceCalls`: The number of times the customer contacted   customer service.
        
Churn: This is our target variable, indicating whether the customer churned (Yes) or not (No).

### Step-by-Step Instructions

`Setup the Environment`:

Import necessary libraries: Pandas for data manipulation, Scikit-learn for machine learning, and Matplotlib for visualization.

`Create the Dataset`:

Use Python to create a synthetic dataset. We'll make a small dataset for simplicity.

`Data Preparation`:

Split the data into features (X) and the target variable (y).
Further split the dataset into training and testing sets.

`Build the Decision Tree Model`:

Use Scikit-learn to create a DecisionTreeClassifier.
Train the model on the training data.

`Evaluate the Model`:

Make predictions on the test set.
Calculate the accuracy of the model.

`Visualize the Decision Tree`:

Use Matplotlib to visualize how the decision tree makes decisions.

`Discuss the Results`:

Interpret the decision tree.

Discuss how it can be used by the company to reduce customer churn.
