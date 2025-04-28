Titanic Survival Prediction 🛳️
A machine learning project that predicts the survival of Titanic passengers based on features like age, gender, ticket class, and fare using Logistic Regression.

✨ Project Highlights
Dataset: Titanic training data (train.csv)

Problem: Predict if a passenger survived

Approach:
→ Data Cleaning → Feature Engineering → Model Training → Evaluation

Final Accuracy: ~79.89%

📌 Key Steps
Data Loading

Loaded dataset from local CSV file.

Exploratory Data Analysis (EDA)

Visualized missing values.

Plotted correlation heatmap to identify key features.

Data Cleaning

Filled missing Age values with the median.

Dropped features like Deck with too many missing entries.

Feature Engineering

Converted Sex to numerical format (male → 0, female → 1).

Selected important columns for modeling.

Model Building

Split data into train and test sets (80%-20%).

Built a Logistic Regression model.

Model Evaluation

Achieved 79.89% accuracy on the test set.

🛠️ Technologies Used
Python 3

Jupyter Notebook

Pandas and NumPy (data manipulation)

Seaborn and Matplotlib (visualization)

Scikit-learn (machine learning)

📈 Final Results
Accuracy: 79.89%

Model: Logistic Regression

Top Features: Age, Sex, Fare, Pclass
