# student performance analysis

## Overview

This repository contains a machine learning project focused on student performance analysis and prediction. The project utilizes various data science and machine learning techniques to process student-related data, identify key factors influencing academic outcomes, and build predictive models.

## Project Structure

The project is organized into two main Jupyter notebooks:

- `PR_ML_idea1.ipynb`: This notebook focuses on data loading, initial exploration, and preprocessing steps. It includes data inspection, handling missing values, and preparing the dataset for model training.
- `PR_ML_idea2.ipynb`: This notebook builds upon the preprocessed data to implement and evaluate machine learning models. It demonstrates the application of various classification algorithms for predicting student performance.

## Features

- **Data Loading and Exploration**: Efficient loading of student datasets and initial data exploration to understand its structure and content.
- **Data Preprocessing**: Comprehensive steps for handling missing values, converting data types, and outlier removal to ensure data quality.
- **Feature Engineering**: Selection of relevant features for predicting student performance.
- **Machine Learning Models**: Implementation and evaluation of classification models, including Random Forest and Support Vector Machines (SVM).
- **Performance Evaluation**: Assessment of model performance using appropriate metrics.

## Technologies Used

This project is developed using Python and leverages the following key libraries:

- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations and array handling.
- **Matplotlib**: For data visualization.
- **Seaborn**: For enhanced statistical data visualization.
- **Scikit-learn**: For machine learning algorithms, including `RandomForestClassifier` and `SVC` (Support Vector Classifier).

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_name>
   ```
2. Create a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```
3. Install the required Python packages:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

## Usage

To run the notebooks and reproduce the analysis:

1. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Open `PR_ML_idea1.ipynb` to explore data preprocessing steps.
3. Open `PR_ML_idea2.ipynb` to run the machine learning models and evaluate their performance.

## Data

The project expects an `enhanced_dataset.csv` file. The path to this file is currently hardcoded in the notebooks (e.g., `E:\amr\Pr_ML\enhanced_dataset.csv`). Please update this path to reflect the actual location of your dataset on your system before running the notebooks.

## Contributing

Contributions are welcome! Please feel free to open issues or submit pull requests.

## License

This project is open-source and available under the [MIT License](LICENSE).

