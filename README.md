## JSON-Based Machine Learning Pipeline

This project automates the machine learning process using a JSON configuration file (`algoparams_from_ui`). Here's what it does:

1. **Data Setup**: Creates a DataFrame from the provided data file and identifies the target variable and problem type.

2. **Feature Selection**: Reads selected features based on the JSON flags.

3. **Data Splitting**: Splits the data into training and validation sets.

4. **Model Building**: Identifies the selected algorithm and hyperparameters from the JSON and builds models using GridSearchCV.

5. **Evaluation**: Evaluates models with appropriate metrics (confusion matrix, classification report for classification; R-squared, RMSE for regression).

### How to Use:

Simply provide your JSON file and run the script. The pipeline automates everything from data handling to model evaluation, making it easy to compare and choose the best model.



