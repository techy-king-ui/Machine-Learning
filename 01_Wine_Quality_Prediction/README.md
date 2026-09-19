# 🍷 Wine Quality Prediction

## 📌 Project Overview

This project uses Machine Learning to predict the quality of wine based on its physicochemical properties.

The dataset contains different chemical properties of wine such as acidity, sugar, chlorides, sulfur dioxide, density, pH, sulphates, and alcohol content. A machine learning model is trained to understand the relationship between these features and wine quality.

📦 Dataset

The dataset is provided as archive.zip.

Extract the ZIP file before running the notebook. It contains the wine quality dataset used in this project.

🚀 How to Run
Clone or download this repository.
Extract archive.zip.
Open wine_quality_predictor.ipynb in Google Colab or Jupyter Notebook.
Update the dataset path if necessary and run all cells.

## 📊 Dataset

The dataset contains the following features:

* Fixed Acidity
* Volatile Acidity
* Citric Acid
* Residual Sugar
* Chlorides
* Free Sulfur Dioxide
* Total Sulfur Dioxide
* Density
* pH
* Sulphates
* Alcohol
* Quality — Target Variable

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook / Google Colab

## 🔍 Project Workflow

1. Load the dataset
2. Perform Exploratory Data Analysis (EDA)
3. Check missing values and duplicate records
4. Analyze correlations between features
5. Visualize important patterns
6. Prepare the data for Machine Learning
7. Split the data into training and testing sets
8. Train Machine Learning models
9. Evaluate model performance
10. Compare the results

## 🤖 Machine Learning

The project uses supervised machine learning to predict wine quality.

The target variable is:

```text
quality
```

The remaining physicochemical properties are used as input features.

## 📈 Results

The performance of the trained models is evaluated using appropriate classification/regression metrics depending on the prediction setup.

Detailed analysis, visualizations, and model results can be found in:

`wine_quality_predictor.ipynb`

## 📁 Project Structure

```text
01_Wine_Quality_Prediction/
│
├── wine_quality_predictor.ipynb
├── archive.zip
└── README.md
```

## 🚀 How to Run

### Using Google Colab

Open:

`wine_quality_predictor.ipynb`

in Google Colab and run the cells sequ

