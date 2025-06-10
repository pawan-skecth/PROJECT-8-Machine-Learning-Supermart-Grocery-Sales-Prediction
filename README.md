# PROJECT-7-Machine-Learning-Supermart-Grocery-Sales-Prediction

This project is based on Supermart Grocery Sales, and it focuses on using machine learning to predict either sales or profit from a retail dataset.

We started by using popular Python libraries like pandas and numpy for data handling, and matplotlib and seaborn for visualizing trends and patterns. For the machine learning part, we used scikit-learn, especially tools like LinearRegression, train_test_split, and components like Pipeline and ColumnTransformer for building and organizing our model workflow.

The dataset we used is called "Supermart Grocery Sales - Retail Analytics Dataset.csv", which contains various details like:

Order ID, Customer Name, City, State, Region, and Order Date

Product-related fields like Category and Sub Category

Numerical fields like Sales, Discount, and Profit

This dataset mainly includes grocery sales data from different parts of Tamil Nadu.

Since the project uses linear regression, the goal is to predict a continuous value—most likely sales or profit—based on the other features in the dataset.

Before building the model, we handled categorical data using OneHotEncoder and scaled the numerical data using StandardScaler. All of this was neatly managed using ColumnTransformer and Pipeline, ensuring a clean and efficient preprocessing and modeling process.

In summary, the aim of this project is to apply machine learning to understand and predict business performance in the retail grocery sector using real sales data.
