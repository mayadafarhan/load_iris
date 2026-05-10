🌸 Iris Dataset – Machine Learning Basics

A simple and clean Machine Learning project using the famous Iris dataset, demonstrating how to load data using load_iris() from Scikit-learn and perform basic exploratory analysis and classification.

This project is ideal for understanding the fundamentals of supervised learning.

📌 Project Overview

The Iris dataset is one of the most widely used datasets in machine learning. It is used to demonstrate how classification algorithms work in a simple but effective way.

In this project, we:

Load the Iris dataset using Scikit-learn Explore dataset structure and features Perform basic data analysis Apply machine learning models for classification Evaluate model performance 🌼 About the Dataset

The dataset contains 150 samples of iris flowers with 4 features:

🌿 Sepal length 🌿 Sepal width 🌸 Petal length 🌸 Petal width

And 3 target classes:

Setosa Versicolor Virginica 🧠 Key Concepts Covered Loading datasets using sklearn.datasets.load_iris() Understanding feature vs target variables Train/test split Classification basics Model evaluation 🛠️ Technologies Used Python 🐍 Scikit-learn Pandas NumPy Matplotlib Jupyter Notebook 📂 Project Structure load_iris/ │ ├── load_iris.ipynb # Main notebook ├── data/ # (optional dataset exploration) └── README.md 🚀 How to Run

Clone the repository git clone https://github.com/amirafarhan/load_iris.git
Install dependencies pip install numpy pandas matplotlib scikit-learn
Run Jupyter Notebook jupyter notebook
Open the file load_iris.ipynb 📊 Example Code from sklearn.datasets import load_iris
iris = load_iris()

X = iris.data y = iris.target

print(iris.feature_names) print(iris.target_names) 📈 What You Learn How datasets are structured in ML How to work with features and labels Basic classification pipeline Introduction to Scikit-learn workflow 🔮 Future Improvements Apply ML models (KNN, SVM, Decision Tree) Add confusion matrix visualization Build interactive dashboard Compare multiple classifiers Add PCA visualization 👨‍💻 Author

Amira Farhan Machine Learning & Computer Vision Engineer

⭐ Support

If you like this project:

⭐ Star the repository 🍴 Fork it 🚀 Share it
