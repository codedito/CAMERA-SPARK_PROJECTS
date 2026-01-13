Overview

🏆 Cardiovascular Disease Prediction Competition

📌 Overview

Cardiovascular diseases (CVDs) remain one of the leading causes of death globally. Early and accurate prediction is critical for effective prevention and treatment strategies. This week's challenge builds on your previous work, where you developed machine learning models for heart disease prediction. Now, you will implement an Artificial Neural Network (ANN) model using the same clinical and demographic dataset to predict the likelihood of heart disease.

📝 Description

Participants are required to design, implement, and optimize an ANN-based predictive model to classify individuals as either at risk (1) or not at risk (0) of cardiovascular disease. The objective is to build a model that not only achieves high performance but also generalizes well to unseen data.

📊 Evaluation

Submissions will be evaluated using the F1 score, a metric that balances precision and recall. This ensures that both false positives and false negatives are minimized—crucial for real-world clinical applications.

Each ground-truth label is either:

0 – No Cardiovascular Disease
1 – Cardiovascular Disease Present

📤 Submitting

Participants must submit a CSV file containing two columns:
id: Unique identifier for each instance
cardio: Predicted label (0 or 1)
Format example:
```csv id,cardio 1001,0 1002,1 1003,0

⏳ Timeline
April 5, 2025 – Competition Starts
April 11, 2025 – Submission Deadline (11:59 PM WAT)
💾 Code Requirements
All teams must submit their notebooks to their team's GitHub repository for verification.
📤 Submitting
Participants must submit a CSV file containing two columns:

id: The unique identifier for each instance.
cardio: The predicted label (0 or 1).
The file should be formatted as follows:

```csv id,cardio 1001,0 1002,1 1003,0
