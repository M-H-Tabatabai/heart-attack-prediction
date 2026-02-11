 Decision Tree Analysis
In the first phase of our project, we implemented a Decision Tree Classifier to establish a baseline for our heart attack prediction system.

🧠 Model Logic
We used the Entropy criterion to ensure the model makes splits based on the maximum information gain. To prevent overfitting and maintain a balance between accuracy and interpretability, the tree depth was capped at 4 levels.

📊 Performance Summary
Our Decision Tree achieved a solid performance, effectively identifying both high-risk and low-risk patients with balanced precision.

Metric	Result
Total Accuracy	88.52%
Precision (High Risk)	90%
Recall (High Risk)	88%
F1-Score (Weighted)	89%

📈 Confusion Matrix Insights
The confusion matrix revealed that the model is particularly strong at identifying Low Risk patients (Recall: 90%), which is vital for reducing false alarms in medical screening.
