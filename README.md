# ROCK-VS-MINE-PREDICTION
This project uses machine learning algorithms to classify whether a given sample is a rock or a mine based on sonar data. The model is trained to distinguish between rocks and mines using supervised learning technique as Logistic Regression, and it is applied to achieve optimal accuracy.

Dataset: Sonar dataset.

Modeling: For the Rock vs Mine Prediction project, I used Logistic Regression as one of the primary machine learning algorithms to classify the sonar data. Logistic Regression is a simple yet powerful algorithm for binary classification problems. It works by modeling the probability that a given input belongs to a particular class, in this case, whether the sample is a rock or a mine.

In this project, I trained the Logistic Regression model using the sonar dataset, where each instance consists of 60 features representing energy values. The model attempts to find a linear relationship between the features and the target class (rock or mine) by applying a logistic function to the weighted sum of the input features.

Key points about Logistic Regression in this project:

Binary Classification: Logistic Regression is well-suited for the binary nature of the problem (rock vs mine).
Feature Weights: The algorithm assigns weights to each feature to determine its importance in predicting the class label.
Output Probability: The model provides a probability score between 0 and 1 for each class, with a threshold (usually 0.5) to make the final prediction.
Training: The model was trained using a portion of the dataset, with performance evaluated on a test set to measure accuracy, precision, and recall.
Overall, Logistic Regression proved to be effective in this task due to its simplicity, interpretability, and reasonable performance on the sonar dataset.

How to Use:
Clone the repository:
git clone https://github.com/anshu2803/rock-vs-mine-prediction.git
cd rock-vs-mine-prediction

Install dependencies:
pip install -r requirements.txt

Run the model:
Open the src/predict.py file (or relevant script).
In the Predictive System section, update the input data with your sample values:

input_data = [0.02, 0.15, 0.10, ..., 0.23]  # Replace with actual values
Execute the script to get the prediction (rock or mine):

python src/predict.py
View Results:
The prediction result (rock or mine) will be displayed in the terminal.

Results: The Logistic Regression model performed well in distinguishing between rocks and mines based on sonar data. Here are the accuracy results:

Accuracy on Training Data: 83.42%
Accuracy on Test Data: 76.19%
These results indicate that the model generalizes well to unseen data, making reliable predictions about whether a sample is a rock or a mine.As i used a small dataset it does not contain more feature but on based on that it is predicting well, the overall performance is strong, reflecting that the model is effective for this classification task.

