# Student Exam Score Prediction

## Project Overview

This project demonstrates how Machine Learning can be used to predict student exam scores based on study hours using a Linear Regression model.

## Technologies Used

- Python
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab
- Jupyter Notebook

## Dataset

The project uses a synthetic dataset containing 10 students with the following variables:

- Student Name
- Study Hours
- Exam Score

## Project Workflow

1. Data creation and preparation
2. Exploratory data analysis
3. Data visualization
4. Linear Regression model training
5. Exam score prediction
6. Model performance evaluation
7. Visualization of actual and predicted scores

## Key Findings

- Average exam score: 71.9 points
- Average study time: 5.5 hours
- Strong positive relationship between study hours and exam scores
- Each additional study hour is associated with an increase of approximately 6.43 points in the predicted exam score

## Model Performance

| Metric | Result |
|--------|--------|
| MAE | 1.08 |
| MSE | 1.76 |
| R² Score | 0.9949 |

The model explains approximately 99.49% of the variation in exam scores in the training dataset.

## Prediction Results

| Study Hours | Predicted Exam Score |
|-------------|----------------------|
| 2.5 | 52.61 |
| 5.5 | 71.90 |
| 8.5 | 91.19 |

## Limitations

- The dataset contains only 10 fictional students.
- The model uses only one input feature.
- The model was evaluated on its training data.
- Linear Regression may predict scores outside the valid range of 0 to 100.

## Future Improvements

- Use a larger, real-world dataset.
- Include additional features such as attendance and sleep hours.
- Implement a train-test split.
- Compare different Machine Learning algorithms.

## How to Run

Open the `student_exam_prediction.ipynb` notebook in Google Colab or Jupyter Notebook and run all cells.

## Conclusion

This project demonstrates fundamental skills in data analysis, data visualization, predictive modeling, and Machine Learning model evaluation.
