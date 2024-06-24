# Predicting Manufacturing Defects

This project aims to predict manufacturing defects using machine learning techniques. The dataset used in this project is collected from [Kaggle](https://www.kaggle.com/datasets/rabieelkharoua/predicting-manufacturing-defects-dataset).

## Project Structure

The project is structured as follows:

1. **Data Loading**: The dataset is loaded from a CSV file.

2. **Exploratory Data Analysis (EDA)**: Initial exploration of the dataset is performed, including visualizations and correlation analysis.

3. **Data Preprocessing**: The data is preprocessed, including handling of categorical variables, missing values, and feature scaling.

4. **Feature Selection**: The most relevant features are selected using the chi2 statistical test.

5. **Model Building**: Two models, RandomForestClassifier and GradientBoostingClassifier, are built using GridSearchCV for hyperparameter tuning.

6. **Model Evaluation**: The models are evaluated using accuracy, classification report, and confusion matrix.

## Requirements

This project is implemented in Python and uses the following libraries:

- numpy
- pandas
- seaborn
- matplotlib
- scikit-learn

## Usage

To run the project, open the `manufacturing_defect.ipynb` notebook in a Jupyter environment.

## License

This project is open source, under the terms of the [MIT License](https://opensource.org/licenses/MIT).
