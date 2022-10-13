# breast_cancer_prediction
Predicts whether the type of breast cancer is Malignant or Benign

About Project:

Breast cancer is the most common type of cancer in women. When cancers are found early, they can often be cured. There are some devices that detect the breast cancer but many times they lead to false positives, which results is patients undergoing painful, expensive surgeries that were not even necessary. These type of cancers are called benign which do not require surgeries and we can reduce these unnecessary surgeries by using Machine Learning. We take a dataset of the previous breast cancer patients and train the model to predict whether the cancer is benign or malignant. These predictions will help doctors to do surgeries only when the cancer is malignant, thus reducing the unnecessary surgeries for woman.

For building the project we have used Wisconsin Breast cancer data which has 569 rows of which 357 are benign and 212 are malignant. The data is prepossessed and scaled. We have trained seven different algorithms among which SVM(rbf) gives best accuracy of 98.6% and recall score of 0.9894. To provide the easy to use interface to doctors we have developed a website that will take the data and display the output with accuracy and time taken to predict.


Languages or Frameworks Used

Python: language
NumPy: library for numerical calculations
Pandas: library for data manipulation and analysis
SkLearn: library which features various classification, regression and clustering algorithms
Flask: microframework for building web applications using Python.

Summary of results:
![image](https://user-images.githubusercontent.com/107847530/195638562-21730760-a479-4ff6-98e1-ed22f5ba1bbb.png)
