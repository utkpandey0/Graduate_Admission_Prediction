# Graduate_Admission_Prediction
This project aims to predict the likelihood of admission for students applying to graduate programs based on their academic profiles. Using a regression-based Artificial Neural Network (ANN), the model learns from factors such as GRE score, TOEFL score, university rating, statement of purpose (SOP), letter of recommendation (LOR), cumulative GPA (CGPA), and research experience to estimate the chances of admission.

The dataset is preprocessed through scaling and divided into training and testing sets. The neural network is built with Keras and has several dense layers. The model is trained to reduce mean squared error (MSE) and evaluated using R² score for accuracy.

A Gradio interface is included to let users enter student data and receive instant predictions on their admission chances.

Graduate Admission Dataset – Feature Summary

**GRE Score** (out of 340):
Standardized test score for graduate admissions. Higher scores indicate better performance.

**TOEFL Score** (out of 120):
English proficiency test score. Important for non-native speakers.

**University Rating** (1 to 5):
Reputation of the student’s undergraduate institution.

**SOP** (1 to 5):
Strength of the Statement of Purpose. Reflects clarity of goals and motivation.

**LOR** (1 to 5):
Strength of Letters of Recommendation. Higher values suggest better academic/professional support.

**CGPA** (out of 10):
Undergraduate academic performance. A key factor in admissions.

**Research** (0 or 1):
Indicates if the student has prior research experience (1 = Yes, 0 = No).

**Chance of Admit** (0 to 1):
Target variable. Predicted probability of getting admission.

<u> Tools & Libraries Used: </u>

Python

TensorFlow / Keras

Scikit-learn (for preprocessing and evaluation)

Pandas & NumPy

Matplotlib (for visualization)

Gradio (for web-based input form)
