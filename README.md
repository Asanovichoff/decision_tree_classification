# Decision Tree Classification

This project demonstrates how to use a Decision Tree Classifier to predict whether a traveler will visit Kyrgyzstan again based on their age and estimated salary. The project includes data preprocessing, model training, evaluation, and visualization of results.

## Project Structure

- `decision_tree_classification.py`: Main Python script for data processing, model training, prediction, and visualization.
- `travelers_data.csv`: Dataset used for training and testing the model.
- `Color Blind Friendly Images/`: Contains visualizations of the decision boundaries (if available).

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn

You can install the required packages using:

```bash
pip install numpy pandas matplotlib scikit-learn
```

## How to Run

1. Make sure `travelers_data.csv` is in the same directory as the Python script.
2. Run the script:

```bash
python decision_tree_classification.py
```

The script will:
- Load and preprocess the data
- Train a Decision Tree Classifier
- Output predictions and accuracy
- Visualize the decision boundaries for both training and test sets

## Output

- Console output: Model predictions, confusion matrix, and accuracy score
- Plots: Visualizations of the decision boundaries for training and test sets

## License

This project is for educational purposes. 