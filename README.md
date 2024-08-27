# Predictive Modeling using Logistic Regression: A Data-Driven Approach to Classification
This project demonstrates the end-to-end process of building, converting, and deploying a machine learning model using Logistic Regression. The model is developed with Scikit-Learn, converted to ONNX format, and validated for deployment on edge devices. The focus is on achieving accurate and reliable predictions while ensuring efficient deployment across different platforms.

## Problem Statement
The goal of this project is to train a Logistic Regression model using Scikit-Learn, convert the trained model to ONNX format, and validate its performance for deployment purposes. This conversion is essential for ensuring interoperability and optimizing the model's performance in low-latency environments.

## Methodology
1. Data Preprocessing: The dataset was preprocessed using a pipeline that included standardizing numeric features and encoding categorical features. This step ensured that the data was in a suitable format for training the Logistic Regression model.

2. Model Training: The Logistic Regression model was trained using the preprocessed data. Hyperparameter tuning was performed to optimize the model's performance.

3. Model Conversion: The trained model was converted to ONNX format using conversion tools like onnxmltools and skl2onnx. The conversion was validated by comparing the predictions and probabilities of the ONNX model with those of the original Scikit-Learn model.

4. Model Evaluation: The model's performance was evaluated using various metrics, including accuracy, precision, recall, F1-score, and ROC-AUC.

## Results
Confusion Matrix: The confusion matrix shows the distribution of correct and incorrect predictions across different classes.

ROC Curve: The ROC curve indicates the model's performance in distinguishing between classes, with the area under the curve (AUC) values demonstrating the model's effectiveness.

Feature Importance: The bar chart shows the importance of different features in the Logistic Regression model, highlighting which features contribute most to the predictions.

Correlation Heatmap: The heatmap illustrates the correlation between different features, aiding in understanding feature relationships and potential multicollinearity issues.

## Conclusion
The project successfully demonstrates the conversion of a Scikit-Learn-based Logistic Regression model to ONNX format, enabling deployment in edge devices with consistent performance. While the conversion process introduced minor differences in probability outputs, the overall predictive performance of the model was maintained.
