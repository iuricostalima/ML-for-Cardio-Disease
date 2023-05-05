# ML-for-Cardio-Disease
This script builds a deep learning model using TensorFlow to predict the presence or absence of cardiovascular disease based on various medical and demographic features, such as age, gender, blood pressure, cholesterol, glucose, smoking, alcohol intake, and physical activity. The dataset used in this script is publicly available and contains over 70,000 records.

## Getting Started

To get started, you will need to install the necessary packages and dependencies. You can do this by running the following command:

```
pip install -r requirements.txt
```

This will install all the required packages including TensorFlow, Pandas, NumPy, and Scikit-learn.

## Running the Script

Once you have installed the required packages, you can run the script using the following command:

```
ML_for_Cardio_Disease.ipynb
```

This will load the dataset, preprocess the data, and train a deep learning model using TensorFlow. The trained model will then be evaluated on a test set and the accuracy will be printed to the console.

## Customization

You can customize the script by modifying the hyperparameters of the model or by changing the preprocessing steps. For example, you can try using a different type of neural network architecture or adjust the learning rate to improve the model's performance.

## Dataset

The dataset used in this script is the Cardiovascular Disease dataset from Kaggle. It contains 70,000 records of patients aged 40-79 years who underwent a medical examination. The data is provided in a CSV file format and contains 12 columns including the target variable, which is the presence or absence of cardiovascular disease.

## Results

The results of the deep learning model trained on the Cardiovascular Disease dataset show a training accuracy of 0.7414 and a testing accuracy of 0.7379. These results indicate that the model is performing reasonably well in predicting the presence or absence of cardiovascular disease based on the features provided in the dataset.
