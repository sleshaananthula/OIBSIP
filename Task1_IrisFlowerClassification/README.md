<h1 align="center" style="font-size: 42px;">Task 1: Iris Flower Classification </h1>

<h2 style="font-size: 28px;"> Objective</h2>

Build a machine learning model that classifies iris flowers into one of three species — **Setosa**, **Versicolor**, and **Virginica** — based on their measurements.

<h2 style="font-size: 28px;"> Description</h2>

The Iris flower dataset consists of 4 features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Each row represents one flower's measurements along with its species label. The goal is to train a classification model that can learn patterns from these measurements and accurately predict the species of a new, unseen flower.

<h2 style="font-size: 28px;"> Tools & Libraries</h2>

- Python
- Pandas, NumPy
- Matplotlib, Seaborn (for visualization/EDA)
- Scikit-learn (for model building)

<h2 style="font-size: 28px;"> Approach</h2>

1. **Data Loading & Exploration** – Load the dataset and explore its structure, check for null values and class distribution.
2. **Exploratory Data Analysis (EDA)** – Visualize relationships between features using pair plots, box plots, and correlation heatmaps.
3. **Data Preprocessing** – Encode the target labels and split the data into training and testing sets.
4. **Model Building** – Train classification models such as:
   - Logistic Regression
   - K-Nearest Neighbors (KNN)
   - Decision Tree / Random Forest
   - Support Vector Machine (SVM)
5. **Model Evaluation** – Evaluate models using accuracy, confusion matrix, and classification report.
6. **Conclusion** – Select the best-performing model and summarize findings.

<h2 style="font-size: 28px;"> Dataset</h2>

- Source: [Scikit-learn built-in dataset](https://scikit-learn.org/stable/datasets/toy_dataset.html#iris-dataset) or downloaded from the link provided in the task list.

<h2 style="font-size: 28px;"> Results</h2>

- Achieved an accuracy of **XX%** using `<best model>`.
- Add confusion matrix / classification report screenshots here.

<h2 style="font-size: 28px;"> How to Run</h2>

```bash
pip install -r requirements.txt
jupyter notebook iris_classification.ipynb
```


