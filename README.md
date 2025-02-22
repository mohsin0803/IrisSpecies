# Iris Flower Classification Project

This project demonstrates the use of various machine learning algorithms to classify the species of Iris flowers based on their physical features. The Iris dataset is used as a classification problem where the objective is to predict the species of the Iris flower given the measurements of the sepal and petal lengths and widths.

## Dataset
The dataset contains 150 entries with 5 features:
- **Id**: Unique identifier for each sample.
- **SepalLengthCm**: Sepal length in centimeters.
- **SepalWidthCm**: Sepal width in centimeters.
- **PetalLengthCm**: Petal length in centimeters.
- **PetalWidthCm**: Petal width in centimeters.
- **Species**: The class label representing the species of the flower (Iris-setosa, Iris-versicolor, Iris-virginica).

The dataset is available in `datasets/iris/Iris.csv`.

## Objective
The goal of this project is to predict the species of an Iris flower based on its sepal and petal measurements using different machine learning algorithms. The following models are evaluated:
- **Logistic Regression**
- **Support Vector Machine (SVM)**
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **K-Nearest Neighbors (KNN)**

## Technologies and Libraries Used
- **Python 3.x**
- **Libraries**:
  - `pandas`: Data manipulation and analysis.
  - `numpy`: Numerical computations.
  - `matplotlib`: Data visualization.
  - `seaborn`: Statistical data visualization.
  - `scikit-learn`: Machine learning algorithms and utilities.

## Project Structure
Iris-Classification/ │ ├── datasets/ │ └── iris/ │ └── Iris.csv │ ├── Iris_Classification.ipynb # Jupyter notebook for analysis and model training ├── requirements.txt

## Model Results

| Model                   | Accuracy (%) | Score (%) | Precision (%) |
|-------------------------|--------------|-----------|---------------|
| Logistic Regression      | 100.0        | 100.0     | 100.0         |
| Support Vector Machine   | 100.0        | 100.0     | 100.0         |
| Decision Tree            | 97.78        | 97.78     | 98.15         |
| Random Forest            | 100.0        | 100.0     | 100.0         |
| K-Nearest Neighbors      | 97.78        | 97.78     | 97.78         |

## Conclusion
In this project, various machine learning algorithms were implemented to classify the species of Iris flowers. While most models achieved very high accuracy and precision, the **Logistic Regression** and **SVM** models provided perfect predictions for this particular dataset. However, in real-world scenarios, further tuning and data preprocessing might be required for achieving optimal performance.
