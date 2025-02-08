# Student Loan Risk Prediction with Deep Learning

This project uses a deep learning model to predict the risk of student loan default. The model is trained on a dataset of student loan applications and aims to classify applicants into high-risk and low-risk categories.

## Project Overview

The notebook explores the following steps:

1. **Data Preparation:**
    - Reads and preprocesses the student loan dataset.
    - Creates features and target variables.
    - Splits data into training and testing sets.
    - Scales features using StandardScaler.

2. **Model Building:**
    - Defines a deep neural network using Keras.
    - Compiles the model with appropriate loss function, optimizer, and metrics.
    - Trains the model on the training data.

3. **Model Evaluation:**
    - Evaluates the model's performance on the testing data.
    - Prints classification report with key metrics like accuracy, precision, and recall.

4. **Model Saving:**
    - Saves the trained model as a Keras file for future use.

5. **Prediction:**
    - Loads the saved model.
    - Makes predictions on the testing data.
    - Saves predictions to a DataFrame.

6. **Recommendation System Discussion:**
    - Discusses the potential of building a recommendation system for student loan options.
    - Explores data requirements, filtering methods, and real-world challenges.


## Requirements

- Python 3.x
- TensorFlow
- Keras
- Pandas
- Scikit-learn
- Pathlib

## Usage

1. Open the notebook in Google Colab.
2. Run all the code cells sequentially.
3. Review the model's performance metrics.
4. Optionally, adjust model parameters and retrain for better results.

## Contributing

Feel free to contribute to this project by:

- Suggesting improvements to the model or data preprocessing steps.
- Implementing new features or functionalities.
- Reporting any issues or bugs you encounter.

## License

This project is licensed under the MIT License.

## Author

[Your Name]
