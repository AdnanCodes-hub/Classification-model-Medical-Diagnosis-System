🩺 Logistic Regression with Polynomial Features (Degree 2)
A logistic regression model implemented from scratch in Python, using polynomial feature mapping (degree 2) to separate non-linearly distributed data. This project simulates a Medical Diagnosis System where two health features are used to predict whether a patient is Healthy (Class 0) or Diseased (Class 1).

🔍 Overview
This repository demonstrates how to:

Generate a synthetic dataset with non-linear class boundaries.

Implement logistic regression manually using:

Sigmoid activation

Cost function

Gradient computation

Gradient descent optimization

Use polynomial feature expansion to capture complex patterns.

Visualize both:

Original dataset

Learned curved decision boundary

📊 Dataset
Class 0 (Healthy): Clustered around the origin (inner circle)

Class 1 (Diseased): Spread around the periphery (outer ring)

Each sample has two features: Symptom Feature 1 and Symptom Feature 2.

🧠 Model Details
Feature	Description
Algorithm	Logistic Regression
Feature Mapping	Polynomial (Degree 2)
Optimization Technique	Gradient Descent
Decision Boundary Shape	Curved (Non-linear)
Accuracy Achieved	~90%–100% (depends on seed & config)

📦 Dependencies
bash
Copy
Edit
pip install numpy matplotlib
▶️ How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/logistic-regression-polynomial.git
cd logistic-regression-polynomial
Run the script:

bash
Copy
Edit
python logistic_diagnosis.py
Output:

Console will show training cost and final accuracy.

Two visual plots will appear:

Original Dataset

Dataset with Learned Decision Boundary

📌 Real-World Analogy
Imagine a medical system that determines whether a patient has a disease based on two symptom scores. These scores may not follow a linear separation, so a curved decision boundary is needed.
This project simulates that using a logistic regression model enhanced with polynomial features.

📁 File Structure
bash
Copy
Edit
📦 logistic-regression-polynomial
 ┣ logistic_diagnosis.py       # Main script
 ┣ README.md                   # Project readme (this file)
📈 Example Output

Curved boundary separating healthy vs diseased patients.

💡 Future Work
Add regularization (L2) to avoid overfitting on complex data.

Extend to multi-class classification using softmax regression.

Build a GUI for doctors to enter scores and get predictions.
