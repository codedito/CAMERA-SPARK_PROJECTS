Overview
🏆 Cardiovascular Disease Prediction Competition
📌 Overview
Cardiovascular diseases (CVDs) are a major health concern worldwide. Early and accurate prediction of heart disease can significantly improve patient outcomes. This competition challenges participants to develop machine learning models that predict the likelihood of heart disease using clinical and demographic data.

📝 Description
Participants will build and optimize predictive models to classify individuals as at risk (1) or not at risk (0) of cardiovascular disease. The goal is to create a robust model that generalizes well to unseen data.

📊 Evaluation
Submissions are evaluated using the F1 score, which balances precision and recall. This metric ensures that both false positives and false negatives are minimized, making the model more reliable in real-world applications.

In this competition, every ground-truth label is either 0 (No Cardiovascular Disease) or 1 (Cardiovascular Disease Present).

📤 Submitting
Participants must submit a CSV file containing two columns:

id: The unique identifier for each instance.
cardio: The predicted label (0 or 1).
The file should be formatted as follows:

```csv id,cardio 1001,0 1002,1 1003,0
