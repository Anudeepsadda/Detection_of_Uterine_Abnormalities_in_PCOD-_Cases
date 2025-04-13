# Detection_of_Uterine_Abnormalities_in_PCOD-_Cases
#  Description
This project addresses the rising concern of infertility among women, particularly those affected by Polycystic Ovarian Syndrome (PCOS), a hormonal disorder that impacts nearly 10% of women of childbearing age. The condition not only leads to reproductive issues but also increases the risk of type 2 diabetes, endometrial cancer, obesity, and psychological problems. Despite its prevalence, PCOS often remains underdiagnosed due to the lack of early detection tools and clinical expertise.

To bridge this gap, the project proposes an automated framework powered by Machine Learning (ML) to detect PCOD/PCOS in its early stages and help prevent complications such as infertility. The system utilizes both textual questionnaire data and medical imaging data for accurate and timely diagnosis.

The core methodology involves the following steps:

Data Collection: A combination of structured textual data via Google Forms (covering demographics, lifestyle, and health symptoms) was collected.

Data Preprocessing: Involves removal of null values, normalization, and label encoding.

Feature Selection: Key features were selected using Rotterdam Criteria, which include anovulation, hyperandrogenism, and presence of polycystic ovaries.

Model Implementation: Multiple machine learning models including Support Vector Machine (SVM), Logistic Regression, Random Forest, and Decision Tree classifiers were evaluated. SVM outperformed others in terms of accuracy, especially when optimized using GridSearchCV.

Model Evaluation: The models were assessed using performance metrics like accuracy, precision, recall, confusion matrix, and ROC curve analysis.

The SVM model achieved an accuracy of 81% in the initial screening and up to 87% in the second stage with optimized hyperparameters, demonstrating the robustness of the approach.

# Why it is Useful?
This project is useful because it enhances IoT security by detecting and preventing malware attacks using machine learning. With the increasing adoption of IoT devices, they have become prime targets for cyber threats due to weak security measures. Traditional security approaches struggle to keep up with evolving malware, making automated detection systems essential. By leveraging machine learning, this project efficiently identifies malicious activities, reducing the risk of data breaches, unauthorized access, and network disruptions. It provides a scalable and intelligent solution for securing IoT ecosystems, helping researchers, cybersecurity professionals, and organizations build proactive defense mechanisms against emerging cyber threats.

# How it Works?
**Data Collection**
1) Textual Data: Gathered through a Google Forms questionnaire, which includes:

2) Demographics (age, weight, occupation)

3) Menstrual health (cycle regularity, period frequency)

4) Symptoms (acne, facial hair, stress, sleep patterns, etc.)

5) Lifestyle habits (exercise, food intake, stress relief practices)

6) Self-reported diagnosis of PCOD/PCOS

**Data Preprocessing**

1) Remove null values

2) Normalize numerical values (scaling between 0 and 1)

3) Convert categorical data to numerical format using Label Encoding

4) Split the dataset into training and testing sets

**Machine Learning Model – SVM Classifier**

The Support Vector Machine (SVM) model is trained on the processed text dataset.

Steps involved:

1) Apply Logistic Regression for classification (binary: PCOS vs. non-PCOS)

2) Tune hyperparameters (C, gamma, kernel) using GridSearchCV

Evaluate using:

- Confusion Matrix

- Accuracy, Precision, Recall

- ROC Curve

- Loss and Validation Accuracy Graphs

SVM achieved up to 87% accuracy with optimized parameters.

# 🛠️ Tech Stack

**📊 Data Collection & Management**

Google Forms: For creating and distributing health questionnaires

CSV/Excel: For storing and managing structured data

Image Repository: For collecting and categorizing ultrasound images of cysts

**🧹 Data Preprocessing**

Python: Core language used for scripting and data manipulation

Libraries:

Pandas – Data handling and cleaning

NumPy – Numerical computations

Sklearn.preprocessing – Label encoding, normalization, train-test split

**🤖 Machine Learning**

Scikit-learn (sklearn): For building and training traditional ML models

Algorithms used:

Support Vector Machine (SVM)

Random Forest

Decision Tree

Tools:

GridSearchCV – Hyperparameter tuning

Confusion Matrix, Classification Report – Model evaluation

ROC Curve, Accuracy Score, Loss Functions

**💻 IDE / Platform**

Google Colab: For coding, training, and testing ML/DL models in the cloud

# Datasets
[PCOD Dataset](https://drive.google.com/drive/folders/1kjTR8V-2uAH5nI4dDJU3phjYjRAjiDUl?usp=sharing)
