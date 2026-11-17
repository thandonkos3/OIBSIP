# Iris Flower Classification

## 1. Project Overview

The Iris Flower Classification project is a supervised machine learning project developed as part of the **Oasis Infobyte (OIBSIP) Data Science Internship – Task 1**.

The objective is to develop machine learning models that can accurately classify iris flowers into three species based on their physical measurements: Setosa, Versicolor, and Virginica.

The project uses the well-known Iris dataset and applies data analysis, exploratory data analysis (EDA), feature selection, model development, and performance evaluation.

## 2. Project Objectives

The main objectives are to:

- Explore and understand the Iris dataset.
- Perform data quality checks and descriptive statistical analysis.
- Conduct exploratory data analysis using visualisations.
- Identify important features for classification.
- Prepare the dataset for machine learning.
- Train and evaluate multiple classification algorithms.
- Compare model performance and identify the most effective classifier.

## 3. Dataset Description

The project uses the Iris dataset available through Scikit-learn.

The dataset contains **150 observations**, representing three iris flower species, with 50 observations per species.

### Target Classes

- Iris Setosa
- Iris Versicolor
- Iris Virginica

### Dataset Features

| Feature | Description |
|---|---|
| Sepal Length (cm) | Length of the flower's sepal |
| Sepal Width (cm) | Width of the flower's sepal |
| Petal Length (cm) | Length of the flower's petal |
| Petal Width (cm) | Width of the flower's petal |
| Species | Target classification label |

## 4. Technologies Used

The project uses the following tools and technologies:

- **Python:** Main programming language.
- **Jupyter Notebook:** Interactive development and documentation environment.
- **Pandas:** Data manipulation and analysis.
- **NumPy:** Numerical computing.
- **Matplotlib:** Data visualisation.
- **Seaborn:** Statistical data visualisation.
- **Scikit-learn:** Machine learning algorithms, preprocessing, dataset loading, and evaluation.
- **Git and GitHub:** Version control and project hosting.

## 5. Project Methodology

The project follows a structured machine learning workflow:

1. **Data Loading:** Load the Iris dataset using Scikit-learn and convert it into a Pandas DataFrame.
2. **Dataset Inspection:** Examine the dataset structure, columns, dimensions, data types, and species distribution.
3. **Data Quality Assessment:** Check for missing values and duplicate records.
4. **Descriptive Statistical Analysis:** Calculate statistical measurements to understand the dataset.
5. **Exploratory Data Analysis:** Use visualisations to identify patterns and relationships between features.
6. **Feature Selection:** Examine the relationships and correlations between flower measurements.
7. **Data Preprocessing:** Separate features and target labels, then divide the data into training and testing sets.
8. **Model Development:** Train four supervised machine learning classification algorithms.
9. **Model Evaluation:** Compare model performance using classification metrics and visual evaluation techniques.

## 6. Machine Learning Algorithms

Four classification algorithms are developed and compared:

### Logistic Regression
A supervised classification algorithm used to predict the probability of a flower belonging to one of the three species.

### K-Nearest Neighbors (KNN)
A distance-based classification algorithm that predicts a class based on the nearest observations in the training dataset.

### Decision Tree
A tree-based algorithm that makes classification decisions using a sequence of feature-based conditions.

### Random Forest
An ensemble learning algorithm that combines multiple decision trees to improve classification performance and reliability.

## 7. Model Evaluation Approach

The dataset is divided into:

- **80% Training Data:** Used to train the machine learning models.
- **20% Testing Data:** Used to evaluate model performance on unseen observations.

The models are evaluated using the following metrics:

- **Accuracy:** Measures the proportion of correctly classified observations.
- **Precision:** Measures the proportion of correct positive predictions.
- **Recall:** Measures how effectively the model identifies actual observations of each class.
- **F1-score:** Represents the balance between precision and recall.
- **Confusion Matrix:** Shows correct and incorrect classifications for each species.

The evaluation results will be compared to identify the strongest-performing classification model.

## 8. Installation and Execution Instructions

Follow these steps to run the project locally.

### Prerequisites

- Python 3.10 or later.
- Git.
- Jupyter Notebook.

### Step 1: Clone the repository

```bash
git clone <YOUR-GITHUB-REPOSITORY-URL>
```

### Step 2: Navigate to the project directory

```bash
cd DataScience-Task1-IrisFlowerClassification
```

### Step 3: Create a virtual environment

```bash
python -m venv .venv
```

### Step 4: Activate the virtual environment

**Windows PowerShell:**

```powershell
.\.venv\Scripts\Activate.ps1
```

### Step 5: Install the dependencies

```bash
python -m pip install -r requirements.txt
```

### Step 6: Start Jupyter Notebook

```bash
python -m notebook
```

### Step 7: Open the project notebook

Open `iris_classification.ipynb` in Jupyter Notebook and execute the cells in sequence.

## 9. Project Structure

```text
DataScience-Task1-IrisFlowerClassification/
│
├── images/
│
├── iris_classification.ipynb
│
├── requirements.txt
│
├── README.md
│
└── .gitignore
```

## 10. Expected Project Outcome

The project aims to develop and compare multiple machine learning classification models capable of identifying iris flower species using their physical measurements.

The final outcome will include data analysis, visualisations, trained classification models, evaluation metrics, and a comparison of model performance.

## 11. Author

**Data Science Internship Participant**

**Organisation:** Oasis Infobyte (OIBSIP)

**Project:** Data Science Task 1 – Iris Flower Classification