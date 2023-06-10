# Multilingual-Abusive-Comment-Detection
Link of Dataset:- https://www.kaggle.com/competitions/multilingualabusivecomment/data

Link of Jupyter Notebook containing code and outputs:- https://github.com/premanshsharma/Multilingual-Abusive-Comment-Detection/blob/main/ANN_ML.ipynb
## Overview
Abusive Comment Detection is a project that focuses on identifying and classifying abusive comments in multiple languages. The dataset used for training and evaluation consists of 1.5 million comments in 16 different languages: Telugu, Tamil, Malayalam, Hindi, Kannada, Bengali, Bhojpuri, English, Odia, Punjabi, Marathi, Gujarati, Rajasthani, Haryanvi, Urdu, and Assamese.

The project achieved an accuracy of 84.9 percent using the Naive Bayes algorithm. The implementation is done in Python, leveraging its rich ecosystem for machine learning and natural language processing tasks. Alongside Naive Bayes, the project utilizes various other machine learning algorithms, including Multinomial Naive Bayes, Logistic Regression with solvers such as lbfgs, liblinear, and newton-cg, k-Nearest Neighbors (KNN) with k values ranging from 1 to 5, Random Forest, and neural network architectures such as LSTM, CNN, Deep Neural Network (DNN), and GRM. This ensemble of algorithms contributes to accurate detection and classification of abusive comments across different languages.

## Word cloud of abusice and non abusive comments
![download](https://github.com/premanshsharma/Multilingual-Abusive-Comment-Detection/assets/71265310/73efd08f-6f1d-4756-912e-d00f52d8aeb8)  ![download](https://github.com/premanshsharma/Multilingual-Abusive-Comment-Detection/assets/71265310/c5ce41b8-9b71-4512-b01d-4c3b7549f26f)


## Outputs:- Best algorithm = Naive Bayes Classifier with an accuracy of 0.8490626671 
### Deep Learning:- Best Architecture = GRM with an accuracy of 0.784
#### GRM
accuracy:  0.784
![download](https://github.com/premanshsharma/Multilingual-Abusive-Comment-Detection/assets/71265310/547832c8-02eb-45a2-aec3-4675399da14d)

#### Deep Neural Network 
accuracy: 0.766
![download](https://github.com/premanshsharma/Multilingual-Abusive-Comment-Detection/assets/71265310/a2986524-6013-4820-a8be-ec2288d9b666)

#### CNN
accuracy: 0.679
![download](https://github.com/premanshsharma/Multilingual-Abusive-Comment-Detection/assets/71265310/94aafabf-4a6e-4db2-b297-c251bca0c88e)

#### LSTM
accuracy: 0.677
![download](https://github.com/premanshsharma/Multilingual-Abusive-Comment-Detection/assets/71265310/fbe57eb6-9edd-4ed5-955e-ac307c6fcefb)

### Machine Learning:- Best Algorithm = Naive Bayes Classifier with an accuracy of 0.8490626671 
#### Combined outputs of all machine learning algorithms

![image](https://github.com/premanshsharma/Multilingual-Abusive-Comment-Detection/assets/71265310/ea3e0b05-a905-4d68-9427-c72892297061)
