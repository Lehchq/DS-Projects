# Project for "Wikishop"

## Project Description
The online store "Wikishop" is launching a new feature allowing users to edit and enhance product descriptions, similar to wiki communities. Customers can propose edits and comment on changes made by others. The store requires a tool to detect toxic comments and flag them for moderation. 

Your task is to train a model to classify comments as positive or negative. You have a dataset labeled for comment toxicity. The model should achieve an F1 score of at least 0.75.

## Project Instructions

### Steps:
1. **Data Loading and Preparation:**
   - Load the dataset.
   - Preprocess the data to make it suitable for model training.

2. **Model Training:**
   - Train multiple models to classify the comments.
   - Optimize the models to achieve the best performance.

3. **Conclusions:**
   - Evaluate the models based on their performance.
   - Select the best model and summarize the results.

## Data Description
The dataset is located in the file `/datasets/toxic_comments.csv`. It contains the following columns:
- `text`: The comment text.
- `toxic`: The target label indicating whether the comment is toxic (1) or non-toxic (0).