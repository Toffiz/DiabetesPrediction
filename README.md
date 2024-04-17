# DiabetesPrediction
This is jupyter notebook in which the algorithm for diabetes prediction is describen, with the F1-score of 0.8, which is pretty good.

## Demonstration
<!-- Replace these placeholder links with actual links to your project screenshots or live demo if available -->
<img width="992" alt="Screenshot 2024-04-17 at 12 51 31" src="https://github.com/Toffiz/DiabetesPrediction/assets/110736020/8af35729-4b8b-4d33-9172-bd375877924f">
<img width="1048" alt="Screenshot 2024-04-17 at 12 54 21" src="https://github.com/Toffiz/DiabetesPrediction/assets/110736020/9cd69187-7a8c-46a2-8151-bb4b6ea0af8f">
<img width="788" alt="Screenshot 2024-04-17 at 12 54 40" src="https://github.com/Toffiz/DiabetesPrediction/assets/110736020/cf5390f1-ee14-47c3-a775-fa289eeceaf6">
<img width="354" alt="Screenshot 2024-04-17 at 12 52 37" src="https://github.com/Toffiz/DiabetesPrediction/assets/110736020/a902bd07-a89e-4e8b-8c5d-8bcd77f39429">


## Steps

- **Data Cleaning:** Checked for null values, duplicates, whitespace values and got the picture of dataset.
- **Feature Encoding** I used One-Hot Encoding method to categorize the categorical data into numerical for future purposes to work with the model that do not do this work by themself
- **Visualization** Visualized the data, to see any of outliying data or some error in data.
- **Model Training** I decided to use DesicionTreeClassifier and did not use SMOTE as it didn't helped at future results. For hyperparameter training i decided to use Optuna as it was shown as high recommended instrument.

## Technologies Used

- Optuna
- scikit-learn
- numpy
- matplotlib
- pandas
- imblearn
- seaborn

## Getting Started

To set up the project locally on your machine, follow these instructions:

1. You need to upload the .ipynb file into your kaggle or colab or jupyter notebooks to see the context and also to insall the libraries like the given optuna if you don't have any:
   ```bash
   %pip install optuna
   ```

## Usage

1. Just turn on all the cells in notebook one by one in order to see the process of work
