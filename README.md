# Titanic Survival Analysis with YData Profiling

This repository provides an exploratory data analysis and survival prediction for the Titanic dataset using Python and Jupyter Notebook. At the end of the notebook, a comprehensive data profiling report is generated and exported as an HTML document using `ydata_profiling`.

## Overview

- **Exploratory Data Analysis (EDA):** Detailed exploration of the Titanic passenger dataset.
- **Data Cleaning:** Handling missing values, dropping non-essential columns, and preparing data for analysis.
- **Feature Engineering:** Creation of new features and transformation of existing ones to improve model prediction.
- **Machine Learning:** Building and evaluating models to predict passenger survival.
- **Data Profiling:** Automatic generation of an interactive HTML data profiling report using YData Profiling for full insight into the dataset.

## Getting Started

### Requirements

- Python 3.x
- Jupyter Notebook or JupyterLab
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- ydata_profiling

You can install the required libraries with:

`pip install pandas numpy matplotlib seaborn scikit-learn ydata-profiling`

### Running the Notebook

1. Clone this repository:
    ```
    git clone https://github.com/uppadadhiraj/Titanic_Ship_Survival.git
    ```
2. Open `Titanic_Ship_Survival.ipynb` in Jupyter Notebook or JupyterLab.
3. Run cells sequentially to perform EDA, model building, and generate the profiling report.

### Generating and Exporting the Data Profiling Report

At the end of the notebook, the following code exports an HTML report:

`from ydata_profiling import ProfileReport`

`profile = ProfileReport(df, title="Titanic Data Profiling Report")`

`profile.to_file("titanic_report.html")`

This will create `titanic_report.html` in your working directory, which can be opened in your web browser for interactive exploration.

## Data

The Titanic dataset used includes passenger information such as age, gender, ticket class, and survival status.  
It is available for download from [Kaggle](https://www.kaggle.com/c/titanic/data).

## Results

Machine learning models are evaluated using accuracy metrics, and insights are provided regarding the most important features affecting survival.

## License

This project is open-sourced under the MIT License.

## Contributing

Contributions and suggestions are welcome! Please open an issue or submit a pull request for improvements.

## Author

[uppadadhiraj](https://github.com/uppadadhiraj)
