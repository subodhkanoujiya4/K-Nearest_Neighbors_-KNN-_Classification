# 📊 K-Nearest Neighbors (KNN) Classification – Iris Dataset
# 🔍 Objective
To understand and implement the K-Nearest Neighbors (KNN) algorithm for classification using the Iris flower dataset. This project demonstrates preprocessing, model training, evaluation, and visualization of decision boundaries.

# 🧰 Tools & Libraries Used
Python
Pandas
NumPy
Matplotlib
Scikit-learn (sklearn)

# 📁 Dataset
Name: Iris.csv
Attributes:
SepalLengthCm
SepalWidthCm
PetalLengthCm
PetalWidthCm
Species (Target variable)

# 🚀 Features Implemented
Data Preprocessing
Load CSV data using pandas
Remove unnecessary ID column (if present)
Normalize features using StandardScaler
Model Training
Train/Test split (70/30)
Use KNeighborsClassifier from sklearn
Train models for different values of K (1 to 20)
Model Evaluation
Calculate Accuracy for each K
Generate and display Confusion Matrix (for K=5)
Visualization
Accuracy vs. K plot

Decision boundary plot using first 2 features

# 📌 How to Run
Clone the repo or download the script.

Make sure you have Iris.csv in the same directory or update the path.

Install dependencies:

pip install pandas numpy matplotlib scikit-learn
Run the script:
python knn_iris.py

# 📈 Sample Output
Accuracy vs. K Plot
Confusion Matrix
KNN Decision Boundaries (2D)

# ✅ Results
Best accuracy generally achieved around K=5 to 7.
Decision boundaries show clear class separations for iris species.

# 📬 Contact
For questions or suggestions, feel free to contact [Subodh Kanoujiya] – [subodhkanoujiya4@gmail.com or https://github.com/subodhkanoujiya4].

