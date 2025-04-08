# House-Prices-Prediction
House Prices Kaggle Competition

This project is part of the House Prices competition on Kaggle, where the goal is to predict the final price of residential homes in Ames, Iowa. The dataset includes 79 explanatory variables describing aspects of residential homes.

## 📌 Project Structure

The project is developed using PySpark and consists of two main Jupyter notebooks:

🔹 cleaning.ipynb
Loads and inspects the training and test datasets.

Handles missing values.

Encodes categorical features.

Performs feature engineering to enhance model performance.

🔹 ml_models.ipynb
Loads the cleaned data.

Preprocesses the features (standardization, transformation, encoding if needed).

Trains several machine learning models using PySpark MLlib.

Evaluates and compares model performance using appropriate metrics (RMSE in this case).

## 📊 Dataset
The dataset contains comprehensive information on housing attributes in Ames, Iowa. A full description of the variables can be found in the file data_description.txt, which includes the definition of each feature used in the analysis.

## ⚙️ Technologies Used
Python

PySpark

Jupyter Notebook

Pandas / NumPy (for intermediate data manipulation)

PySpark MLlib (for modeling)

