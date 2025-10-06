🧭 Task 6: K-Nearest Neighbors (KNN) Classification

📌 Objective  
The goal of this task is to understand and implement the K-Nearest Neighbors (KNN) algorithm for classification problems.  
This task involves data preprocessing, training the KNN model, evaluating performance, and visualizing decision boundaries.

 🛠 Tools & Libraries 
 
- 🐍 Python  
- 📚 Scikit-learn (sklearn) 
- 📊 Matplotlib 
- 🧾 Pandas
- 🧮 NumPy

 🧪 Steps Performed  

1. ✅ Dataset Selection & Normalization  
   - Used the Iris Dataset 🌸 for classification.  
   - Normalized the numerical features using StandardScaler for better distance calculations.

2. 👩‍🏫 Model Training with KNN  
   - Implemented KNeighborsClassifier from sklearn.neighbors.  
   - Trained multiple models with different values of K (e.g.,6,3,8,9,10).

3. 📈 Accuracy Evaluation
   - Measured model performance using accuracy score on the test data.  
   - Plotted Accuracy vs K to find the best number of neighbors.

4. 🧠 Confusion Matrix  
   - Generated a confusion matrix to analyze class-wise predictions and errors.

5. 🌿 Decision Boundary Visualization 
   - Visualized how KNN separates classes using the first two features of the Iris dataset.  
   - Showed how decision regions change with different K values.

 📈 Results  

- The best K value gave high accuracy on the Iris dataset.  
- Accuracy vs K plot clearly showed that very small or very large K values can reduce performance.  
- The confusion matrix showed good classification results across all three Iris classes.  
- Decision boundary plots helped to understand how KNN makes predictions in feature space.
  
 📝 Key Learnings  

- ✅ KNN is a simple, non-parametric algorithm that works well on clean datasets.  
- ✨ Feature scaling is essential because KNN uses distance-based calculations.  
- 📊 Choosing the right K value is crucial for balancing bias and variance.  
- 🌀 Visualization helps to interpret how KNN classifies points.

# 2️⃣ Run the Python script
python task6_knn_classification.py
