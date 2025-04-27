Crop Recommendation System
This project develops a machine learning model that recommends the best crop to grow based on soil and environmental conditions.
The model uses features like:
Soil nutrients (Nitrogen, Phosphorus, Potassium)
Temperature
Humidity
pH
Rainfall

Steps Performed
Data Inspection:
Checked dataset shape, missing values, duplicates, and identified all unique crop labels.

Data Preprocessing:
Label encoding was applied to the target column.
Feature scaling was not required as Decision Tree models are scale-invariant.

Model Building:
A Decision Tree Classifier was trained after splitting the data into 80% training and 20% testing sets.

Model Evaluation:
Achieved 98% accuracy using metrics like Accuracy Score and Confusion Matrix.

Feature Importance:
Analyzed which features had the most impact on crop prediction.

Conclusion

The model learned the relationship between soil/environment factors and crop selection.
It successfully achieved high accuracy (98%), confirming its effectiveness for crop recommendation.

Technologies Used
Python
scikit-learn
Pandas, NumPy
Matplotlib, Seaborn

