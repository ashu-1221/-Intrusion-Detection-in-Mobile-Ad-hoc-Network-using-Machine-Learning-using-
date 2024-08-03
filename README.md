## Blackhole Intrusion Detection in Mobile-Ad-hoc Network using Machine Learning
## Introduction
MANETs (Mobile Ad hoc NETworks) are a very unique type of wireless communication as they are highly dynamic & unpredictable in nature. We can not easily identify the topology in a MANET due to the unavailability of central authority & the variable nature of nodes. Due to the ease of deployment and the rise in demand & popularity of mobile devices, these networks have recently become much more common and crucial to wireless communications. MANETs developed into a desirable technology for various applications. However, this flexibility introduces security threats. Additionally,these networks are not directly covered by the conventional infrastructure-based approach. The adoption of an IntrusionDetection System (IDS) is quite crucial for MANET protection because preventative measures are never sufficient. A short description of blackhole attack is given in the following figure.

![blackhole](https://github.com/user-attachments/assets/795cd794-a622-40dd-b99b-1d995fa9d37c)


## Dataset
The dataset used in this project consists of training and testing data files:
- `Train_data.csv`
- `Test_data.csv`

-  There are a total of 25192 entries of the dataset in which normal data has 13449 & anomaly data has 11743 entries. The total dataset is splitted into training & testing phases by the ratio of 70 to 30. As a result, the training phase contains 17634 data entries & testing phase contains 7585 entries.


## Worflow for this project has been given beloew
![Model Flowchart](https://github.com/user-attachments/assets/302e8bd4-a36a-4c7c-9e2e-adffe5d26ecb)


## Models
The project uses the following machine learning Classification algorithms for intrusion detection:
- K-Nearest Neighbors (KNN)
- Logistic Regression
- Decision Tree Classifier
- Support Vector Machine (SVM)

The notebook includes steps for data preprocessing, training the models, and evaluating their performance.

## Results
The models are evaluated based on precision, recall, and F1-score. The evaluation metrics are visualized using bar plots for comparison.

Results are shown below.




![accuracy](https://github.com/user-attachments/assets/6ec35627-a485-4e91-8321-0ab8bbf78e9a)
![f1 score](https://github.com/user-attachments/assets/86c6855c-af60-4850-b0bd-7acb4535f76b)
![precision_recall](https://github.com/user-attachments/assets/a9ea2dea-977d-4358-915e-5615ba3ab177)
![train_test_comparison](https://github.com/user-attachments/assets/ca7ecdb7-9ad4-4c20-a512-7bfc983d8b77)

