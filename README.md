# AIML-TASK-5
📌 Objective

This project demonstrates how to apply tree-based machine learning models, specifically Decision Trees and Random Forests, for binary classification using the Heart Disease dataset.

🧰 Tools & Libraries

Python

pandas

scikit-learn

matplotlib

seaborn

graphviz (for decision tree visualization)

🧪 Dataset

The dataset used is heart.csv, which contains patient health records used to predict the presence (1) or absence (0) of heart disease.

https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset

✅ Steps Performed

1️⃣ Data Preprocessing
Loaded the dataset

Handled missing values if any

Split the data into training and test sets

2️⃣ Decision Tree Classifier

Trained using DecisionTreeClassifier

Visualized using graphviz

Controlled overfitting using parameters like max_depth

Accuracy calculated on test set

3️⃣ Random Forest Classifier

Trained with RandomForestClassifier (100 trees)

Compared performance with the Decision Tree

Plotted feature importances

4️⃣ Cross-Validation

Applied 5-fold cross-validation to both models

Evaluated average accuracy and standard deviation

📊 Results

Model	Test Accuracy	Cross-Validation (Mean ± Std)

Decision Tree	97.08%	99.71% ± 0.59%

Random Forest	98.05%	99.41% ± 0.72%

⚠️ Graphviz Setup

To visualize the decision tree:

Download and install Graphviz: https://graphviz.org/download/

Add the path to the dot.exe (e.g., C:\Program Files\Graphviz\bin) in your system PATH

OUTPUT:[Decision_tree_and_random_forest_TASK5.pdf](https://github.com/user-attachments/files/20979867/Decision_tree_and_random_forest_TASK5.pdf)
