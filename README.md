# General Health Prediction Using Machine Learning

## About the Project
This project uses machine learning classification algorithms to predict general health categories using the `CVD_cleaned.csv` dataset.

## Objectives
- Explore and preprocess the dataset.
- Train and test machine learning models.
- Compare model performance.
- Tune model hyperparameters.
- Demonstrate a prediction for a single input record.

## Machine Learning Algorithms
- Support Vector Machine (SVM)
- Random Forest Classifier
- Logistic Regression

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Google Colab

## Project Workflow
1. Load and explore the dataset.
2. Prepare the data and split it into 80% training and 20% testing.
3. Train the three classification models.
4. Evaluate accuracy, classification reports, and confusion matrices.
5. Visualize and compare model accuracies.
6. Tune Random Forest using `RandomizedSearchCV`.
7. Predict a general health category for a single input record.

## Results
The recorded test accuracies were:
- SVM (LinearSVC): 41.60%
- Random Forest: 40.31%
- Logistic Regression: 32.60%
- Tuned Random Forest: 40.48%

The results show that model performance is limited and that hyperparameter tuning produced only a small improvement in Random Forest accuracy.

## How to Run
1. Open [Google Colab](https://colab.research.google.com/).
2. Upload the notebook from this repository.
3. Upload `CVD_cleaned.csv` to the Colab session, or update the dataset path.
4. Run the notebook cells from top to bottom.

## Disclaimer
This project is for educational purposes only. Its predictions are not medical diagnoses and should not be used as a substitute for professional medical advice.
