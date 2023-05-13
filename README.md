# Artificial_Intelligence_Basics

**Label encoding & Ordinal Encoding**

The file "Label encoding & Ordinal Encoding.ipynb" is another Jupyter notebook that demonstrates two techniques for encoding categorical variables: label encoding and ordinal encoding.

Label encoding is a technique that assigns a unique numerical value to each category in a categorical variable. For example, if a variable has three categories (A, B, and C), label encoding would assign the values 0, 1, and 2 to each category, respectively.

Ordinal encoding is a similar technique, but it takes into account the order or hierarchy of the categories. For example, if a variable has the categories "low," "medium," and "high," ordinal encoding would assign the values 0, 1, and 2, respectively, because "low" is considered less than "medium," and "medium" is less than "high."

The notebook starts by importing the necessary libraries and loading a dataset that includes categorical variables. The dataset used in this notebook is the "Titanic Dataset," which includes information about passengers on the Titanic, such as their age, gender, and class.

Next, the notebook explores the different categorical variables in the dataset and shows how to encode them using label encoding and ordinal encoding. The notebook compares the results obtained with these two methods and discusses the pros and cons of each technique.

Finally, the notebook shows how to use the encoded dataset in a logistic regression model to predict the survival of passengers based on their characteristics. The notebook also discusses some potential issues with encoding categorical variables, such as the risk of introducing bias or false correlations.

Overall, this notebook is a great resource for anyone who wants to learn about the different techniques for encoding categorical variables and how to use them in machine learning models. It also provides a practical example using a real-world dataset, which can be useful for those who are just starting with data science.


**One Hot Encoding & Dummy Variables**

The file "One Hot Encoding & Dummy Variables.ipynb" is a Jupyter notebook that demonstrates the process of encoding categorical variables using one-hot encoding and dummy variables.

In machine learning, most algorithms require that the input data be numerical. However, many datasets include categorical variables, such as gender, color, or country of origin, which cannot be directly used in most models. One solution to this problem is to convert categorical variables into numerical ones, and one popular technique to achieve this is one-hot encoding.

The notebook starts by importing the necessary libraries and loading a dataset that includes categorical variables. The dataset used in this notebook is the "Car Evaluation Dataset," which includes different characteristics of cars, such as "buying price," "maintenance price," and "number of doors," among others.

Next, the notebook explores the different categorical variables in the dataset and shows how to encode them using one-hot encoding and dummy variables. One-hot encoding creates a binary variable for each unique category in the dataset, and dummy variables create a binary variable for each category minus one. The notebook compares the results obtained with these two methods.

Finally, the notebook shows how to use the encoded dataset in a logistic regression model to predict the acceptability of a car based on its characteristics. The notebook also discusses the limitations of one-hot encoding, such as the "curse of dimensionality," and suggests alternatives, such as feature hashing.

Overall, this notebook is a great resource for anyone who wants to learn how to encode categorical variables and use them in machine learning models.


**Train test split, ML models, PCA**

The file "Train test split, ML models, PCA.ipynb" is a Jupyter notebook that covers several important topics in machine learning, including data preparation, model training, evaluation, and dimensionality reduction using principal component analysis (PCA).

The notebook starts by importing the necessary libraries and loading a dataset that includes information about breast cancer patients. The dataset contains different features such as the radius, texture, and perimeter of the tumor, among others. The goal of the notebook is to predict whether the tumor is benign or malignant based on these features.

Next, the notebook explores the dataset and performs some data preprocessing steps, such as checking for missing values and scaling the data using the StandardScaler function. The notebook also splits the dataset into training and testing sets using the train_test_split function from the scikit-learn library.

After that, the notebook trains several machine learning models, including logistic regression, support vector machines (SVM), decision trees, and random forests, and evaluates their performance using metrics such as accuracy, precision, recall, and F1 score. The notebook also discusses the pros and cons of each model and provides some tips for improving their performance.

Finally, the notebook applies PCA to the dataset to reduce its dimensionality and visualizes the results using a scatter plot. PCA is a technique that can be used to identify the most important features in a dataset and reduce its dimensionality while retaining most of the information. The notebook discusses the benefits of using PCA and provides some tips for choosing the optimal number of principal components.

Overall, this notebook is a great resource for anyone who wants to learn about data preparation, model training, and evaluation in machine learning. It also provides a practical example using a real-world dataset and demonstrates how to apply PCA to reduce the dimensionality of the data.
