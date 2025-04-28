# ANN-based-Diagnosis-of-Breast-Cancer-Malignant-vs-Benign-
"A neural network-based binary classification model to predict breast cancer malignancy using the Breast Cancer Wisconsin dataset."
📄 Project Structure
•	Data Source: Breast Cancer Wisconsin (Diagnostic) Dataset

•	Preprocessing:

o	Dropping irrelevant columns (id, Unnamed: 32)

o	Converting labels ('M', 'B') to binary values (1, 0)

o	Feature scaling using StandardScaler

•	Model:

o	Built using Keras Sequential API

o	Layers:

	Dense(32) → ReLU Activation

	Dense(16) → ReLU Activation

	Dense(1) → Sigmoid Activation (for binary output)

•	Training:

o	Optimizer: Adam

o	Loss Function: Binary Crossentropy

o	Metrics: Accuracy

o	Trained for 100 epochs

•	Evaluation:

o	Confusion Matrix

o	Classification Report

o	Accuracy and Loss Visualization
________________________________________

🎯 Custom Prediction

You can provide your own input (30 numerical features) and predict if the tumor is malignant or benign.

If the prediction probability > 0.5 → Malignant
•	Else → Benign
________________________________________
📊 Results

•	Achieved high accuracy (~97%+) on test data.

•	Strong generalization with no major overfitting.

•	Clear distinction between benign and malignant cases observed in confusion matrix.
________________________________________
📚 Technologies Used
•	Python
•	TensorFlow 2.x / Keras
•	Scikit-learn
•	Pandas
•	Matplotlib
•	Google Colab
________________________________________
📌 Dataset Reference
•	Breast Cancer Wisconsin Diagnostic Dataset on Kaggle

