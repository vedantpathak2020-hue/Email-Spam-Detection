Spam Email Classification Project

Overview

This project focuses on building a machine learning model to classify emails as spam or ham (non-spam). The model is trained on a dataset containing email messages labeled with their respective categories.

Requirements Python 3.x Libraries: numpy, pandas, scikit-learn Dataset The dataset used in this project is sourced from https://drive.google.com/drive/folders/1r7odqdBT-0fOafjDbflpJHvCt8X5859D?usp=drive_link. It consists of a collection of email messages along with their corresponding categories (spam or ham).

Usage

Clone this repository to your local machine. Download the dataset (mail_data_final.csv) and place it in the project directory. Install the required dependencies using pip:

Copy code

pip install numpy pandas scikit-learn

Run the script

spam_classifier.py

to train the model and make predictions.

Copy code

python Espam detection.py

Approach

Data Preprocessing: The dataset is loaded and preprocessed to handle missing values and convert categorical labels into numerical format. Feature Extraction: Text data is transformed into feature vectors using TF-IDF (Term Frequency-Inverse Document Frequency) vectorization. Model Training: A Logistic Regression model is trained using the TF-IDF features. Evaluation: The model's performance is evaluated using accuracy metrics on both training and test datasets. Prediction: Given a new email message, the trained model predicts whether it is spam or ham.

Results

Accuracy on training data: 0.9676912721561588 Accuracy on test data: 0.9668161434977578 Sample Prediction Input email: "WINNER!! As a valued network customer you have been selected to receivea £900 prize reward! To claim call 09061701461. Claim code KL341." Predicted category: Spam mail

Author

Saurav Dhiani

Feel free to customize and expand upon this template based on the specific details of your project.
