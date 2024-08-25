# Mobile Price Prediction

This repository contains code for predicting the price range of mobile phones based on their features using machine learning algorithms. It includes data exploration, feature selection, model training, and evaluation.

## Dataset

The dataset used in this project contains various features of mobile phones, such as battery power, RAM, camera features, display resolution, etc. The target variable is the price range of the mobile phone, categorized into four classes. The dataset is available in two formats: `cleaned_data` and `data`.

## Contents

- `data_analysis.ipynb`: Jupyter Notebook containing data exploration, visualization, and correlation analysis.
- `model_training.ipynb`: Jupyter Notebook for training machine learning models (Logistic Regression and K-Nearest Neighbors).
- `requirements.txt`: File specifying the dependencies required to run the code.
- `README.md`: Readme file providing an overview of the project.

## Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/mobile-price-prediction.git
    ```

2. Navigate to the project directory:

    ```bash
    cd mobile-price-prediction
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the Jupyter Notebooks `data_analysis.ipynb` and `model_training.ipynb` to explore the data, analyze correlations, train machine learning models, and evaluate their performance.

2. Modify the code as needed for further analysis or experimentation with different models and parameters.

## Results

- Logistic Regression Model:
  - Achieved an accuracy of approximately 96.25% on the training set and 97.25% on the test set.
  - Identified top five features positively correlated with price range: RAM, battery power, display width, display height, and internal memory.

- K-Nearest Neighbors (KNN) Model:
  - Achieved an accuracy of approximately 95.44% on the training set and 94.50% on the test set.
  - Grid search identified the optimal value of K (number of neighbors) as 11 with a corresponding accuracy of 93.12%.

## Future Improvements

- Explore additional features or transformations for better capturing the underlying patterns in the data.
- Experiment with other machine learning algorithms or more complex models to potentially improve predictive performance.
- Fine-tune hyperparameters of models for optimization.
- Handle imbalanced classes if significant class imbalance is present in the target variable.
- Evaluate additional evaluation metrics such as precision, recall, F1-score, or ROC-AUC for a more comprehensive assessment of model performance.

## Contributors

- [Muntasir Md Nafis](https://github.com/nafis2508)

## License

This project is licensed under the [MIT License](LICENSE).
