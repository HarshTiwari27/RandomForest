# RandomForest Project

This repository contains implementations of Random Forest models for classification, regression, and hyperparameter tuning using Jupyter Notebooks.

## Project Structure
```
RandomForest-main/
│── requirements.txt  # General dependencies
│── classification/
│   ├── exampleClassification.ipynb  # Classification example
│   ├── requirements.txt  # Dependencies for classification
│── regression/
│   ├── exampleRegression.ipynb  # Regression example
│   ├── requirements.txt  # Dependencies for regression
│── tuning/
│   ├── exampleTuning.ipynb  # Hyperparameter tuning example
│   ├── requirements.txt  # Dependencies for tuning
```

## Installation
1. Clone the repository:
   ```sh
   git clone <repo_url>
   cd RandomForest-main
   ```
2. Install general dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Install additional dependencies as needed from the subdirectories (`classification/`, `regression/`, `tuning/`).

## Usage
- Open Jupyter Notebook:
  ```sh
  jupyter notebook
  ```
- Navigate to the desired notebook in the `classification/`, `regression/`, or `tuning/` folder.
- Run the notebook cells to execute the Random Forest models.

## License
This project is licensed under the MIT License.
