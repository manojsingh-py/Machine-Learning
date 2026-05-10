# Machine Learning Project

A comprehensive machine learning project that explores various data preprocessing techniques, feature scaling methods, exploratory data analysis, and model development using scikit-learn pipelines.

## Project Structure

### Root Files
- **abc.py** - Utility script
- **main.py** - Main entry point
- **basic.ipynb** - Basic machine learning concepts notebook
- **placement_project_logistic_regression.ipynb** - Logistic regression example on placement data

### Data Directory (`data/`)
Contains various CSV datasets used in the project:
- `cars.csv` - Cars dataset
- `concrete_data.csv` - Concrete strength data
- `covid_toy.csv` - COVID-19 toy dataset
- `customer.csv` - Customer data
- `data_science_job.csv` - Data science job listings
- `flights.csv` - Flights data
- `house_price.csv` - House price predictions
- `Iris.csv` - Classic Iris dataset
- `placement.csv` - Placement/job data
- `Social_Network_Ads.csv` - Social network advertising data
- `tips.csv` - Restaurant tips dataset
- `titanic_toy.csv` - Titanic dataset
- `train.csv` - Training dataset
- `wine_data.csv` - Wine quality data

### Feature Scaling (`feature_scaling/`)
Jupyter notebooks demonstrating various feature scaling techniques:
- **normalization.ipynb** - Min-Max normalization
- **standardization.ipynb** - Standardization (Z-score normalization)
- **binarization.ipynb** - Converting features to binary values
- **binning_and_binarization.ipynb** - Binning continuous variables
- **one_hot_encoding.ipynb** - One-hot encoding for categorical variables
- **ordinal_encoding.ipynb** - Ordinal encoding for categorical variables
- **power_transformer.ipynb** - Power transformations (Box-Cox, Yeo-Johnson)
- **function_transformer.ipynb** - Custom function-based transformations
- **column_transformer.ipynb** - Using ColumnTransformer for multiple transformations

### Handling Missing Data (`handling_missing_data/`)
Notebooks for various missing data imputation strategies:
- **complete_case_analysis.ipynb** - Removing rows/columns with missing values
- **mean_median_imputation.ipynb** - Statistical imputation
- **arbitrary_value_imputation.ipynb** - User-defined value imputation
- **missing_category_imputation.ipynb** - Category imputation for categorical features

### Exploratory Data Analysis (`EDA_using_Univariate_Analysis/`)
Notebooks for data exploration and analysis:
- **eda_using_univariate_analysis.ipynb** - Single variable analysis
- **eda_bivariate_analysis.ipynb** - Two-variable relationship analysis
- **pandas_profiling.ipynb** - Automated EDA using pandas profiling
- **output.html** - Generated profiling report

### Scikit-Learn Pipelines (`sklearn_pipeline/`)
Examples of building machine learning pipelines:
- **titanic_using_pipeline.ipynb** - Titanic dataset with pipelines
- **titanic-without-using-pipeline.ipynb** - Titanic dataset without pipelines (comparison)
- **predict_using_pipeline.ipynb** - Making predictions with pipelines
- **predict_without_pipeline.ipynb** - Making predictions without pipelines

### Models Directory (`models/`)
Contains saved trained models:
- `model.pkl` - Trained model
- `pipe_model.pkl` - Pipeline model
- `clf.pkl` - Classifier model
- `ohe_sex.pkl` - One-hot encoder for sex feature
- `ohe_embarked.pkl` - One-hot encoder for embarked feature

## Prerequisites

- Python 3.7+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- jupyter

## Installation

1. Clone the repository
2. Install dependencies:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

## Usage

Run Jupyter notebooks:
```bash
jupyter notebook
```

Navigate to the desired notebook files to explore different machine learning concepts and techniques.

## Key Topics Covered

- **Exploratory Data Analysis (EDA)** - Understanding data through univariate and bivariate analysis
- **Missing Data Handling** - Various imputation strategies
- **Feature Scaling** - Normalization, standardization, and encoding techniques
- **Model Development** - Building and training machine learning models
- **Scikit-Learn Pipelines** - Creating reproducible and maintainable workflows

## Notes

- All notebooks are interactive and include detailed explanations
- The project demonstrates both manual and pipeline-based approaches
- Sample datasets are provided for learning and experimentation
- Trained models are saved in the `models/` directory for reuse

## Author Notes

This project serves as a comprehensive learning resource for machine learning fundamentals, focusing on practical implementation using scikit-learn and popular Python data science libraries.

