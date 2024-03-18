
# IMDb Movie Rating Prediction

This project focuses on predicting IMDb movie ratings based on various features such as genre, director, and actors. It utilizes machine learning algorithms for regression tasks to predict movie ratings accurately.

## Data Preparation

1. **Mount Google Drive**: The project starts by mounting Google Drive to access the dataset stored on it.

2. **Loading and Exploration**: The dataset (`IMDb Movies India.csv`) is loaded using Pandas, and its structure is explored to understand the features and their data types.

3. **Data Cleaning**: Columns like `Name`, `Year`, `Duration`, and `Votes` are dropped as they are not relevant for rating prediction. Missing values are handled, and categorical variables are encoded using LabelEncoder.

4. **Train-Test Split**: The dataset is split into training and testing sets for model evaluation.

## Model Training and Evaluation

1. **Random Forest Regression**: A Random Forest Regressor is trained on the training data to predict movie ratings. The Mean Squared Error (MSE) is calculated to evaluate the model's performance.

2. **Linear Regression**: Another model based on Linear Regression is trained and evaluated using MSE as a metric.

## User Interaction

1. **Input**: Users can interact with the trained Linear Regression model by providing input for movie features such as genre, director, and actors.

2. **Prediction**: The model predicts the movie rating based on the user input and displays the result.

## Requirements

- Pandas
- NumPy
- Scikit-learn

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/keshav-kumar-01/Movie-Rating-Prediction.git
   ```

2. Install the required packages:

   ```bash
   pip install pandas numpy scikit-learn
   ```

3. Run the Jupyter notebook or Python script to train the models and interact with them for movie rating prediction.

## Contributors

- [Keshav Kumar](https://github.com/keshav-kumar-01)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```

Adjust the URLs, file paths, and contributor information according to your project.
