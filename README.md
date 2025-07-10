# ML-Decision_tree_Regression

Decision Tree Regression" contains a basic implementation of decision tree regression using the sklearn.tree.

---

🔹 1. Importing Libraries

numpy: Used for numerical operations.

matplotlib.pyplot: Used for data visualization (plotting).

pandas: For data manipulation and loading.

---

🔹 2. Loading the Dataset

Loads a CSV file called Position_Salaries.csv.

Extracts:

X: Independent variable (position level).

y: Dependent variable (salary).

---

🔹 3. Fitting the Decision Tree Regression Model

Imports and initializes a Decision Tree Regressor.

random_state=0 ensures reproducibility.

Fits the model to the dataset.

---

🔹 4. Making Predictions 

Predicts salary for position level 6.5.

Decision Trees output constant values per interval → the prediction might match an exact salary from the dataset.

---

🔹 5. Visualizing the Decision Tree Regression Results

Plots:

Red dots: Actual data.

Blue line: Predictions (not very accurate unless high-resolution input is used).


---

🔹 6. Higher Resolution & Smoother Curve

Generates a finer input grid to show the decision tree's stepwise prediction behavior more clearly.

Now the blue line appears as horizontal steps, reflecting how the decision tree predicts constant values for ranges of inputs.


---

✅ Summary

This notebook demonstrates:

How to use DecisionTreeRegressor for a simple regression task.

How to visualize the non-continuous nature of decision tree regression.

The use of higher resolution input for better plot clarity.