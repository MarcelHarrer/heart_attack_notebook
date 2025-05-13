# Heart Attack Dataset Analysis

This project demonstrates how to:

- Download a heart attack dataset from Kaggle using `kagglehub`
- Load and explore the dataset with pandas
- Select features interactively using Jupyter widgets
- Train and evaluate a Random Forest classifier to predict heart attack risk
- Visualize feature importance

## Usage

1. Open the notebook (`kaggle_heartattack.ipynb`) in Jupyter.
2. Run all cells to download the dataset, select features, train the model, and view results.
3. Use the interactive widget to choose which features to include in the model.

## Running on Google Colab

To run this notebook on [Google Colab](https://colab.research.google.com):

1. Upload the notebook file to Colab.
2. Make sure to run the first cell to install all required packages (including `kagglehub`, `ipywidgets`, etc.).
3. If you want to use widgets, run:
   ```python
   !pip install ipywidgets
   from google.colab import output
   output.enable_custom_widget_manager()
   ```
4. Proceed with the rest of the notebook as usual.

## Requirements

- Python 3.x
- Jupyter Notebook

## Notes

- The dataset is automatically downloaded from Kaggle.
- Feature selection is interactive; results update based on your selection.
- The notebooks include explanations and visualizations for easy understanding.
