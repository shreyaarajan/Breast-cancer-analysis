# Breast-cancer-analysis

Breast cancer occurs when a malignant (cancerous) tumor originates in the breast. As breast cancer tumors mature, they may metastasize (spread) to other parts of the body. The primary route of metastasis is the lymphatic system which, ironically enough, is also the body's primary system for producing and transporting white blood cells and other cancer-fighting immune system cells throughout the body. Metastasized cancer cells that aren't destroyed by the lymphatic system's white blood cells move through the lymphatic vessels and settle in remote body locations, forming new tumors and perpetuating the disease process.

Breast cancer is not just a woman's disease. It is quite possible for men to get breast cancer, although it occurs less frequently in men than in women. Our discussion will focus primarily on breast cancer as it relates to women but it should be noted that much of the information is also applicable for men.

# Role of ML in detecting Breast Cancer
A mammogram is an x-ray picture of the breast. It can be used to check for breast cancer in women who have no signs or symptoms of the disease. It can also be used if you have a lump or other sign of breast cancer.

Machine learning is widely used in bio informatics and particularly in breast cancer diagnosis. In this project, we have used certain classification methods such as K-nearest neighbors (K-NN) and Support Vector Machine (SVM) which is a supervised learning method to detect breast cancer. Cancer diagnosis is one of the most studied problems in the medical domain. Several researchers have focused in order to improve performance and achieved to obtain satisfactory results. Early detection of cancer is essential for a rapid response and better chances of cure. Unfortunately, early detection of cancer is often difﬁcult because the symptoms of the disease at the beginning are absent. Thus, it is necessary to discover and interpret new knowledge to prevent and minimize the risk adverse consequences.

To understand this problem more precisely, tools are needed to help oncologists to choose the treatment required for healing or prevention of recurrence by reducing the harmful effects of certain treatments and their costs. In artiﬁcial intelligent, machine learning is a discipline which allows the machine to evolve through a process. Wisconsin Diagnostic Breast Cancer (WDBC) dataset obtained by the university of Wisconsin Hospital is used to classify tumors as benign or malignant.

So with the help of Machine learning if we can classify the patient having which type of cancer, then it will be easy for doctors to provide timely treatment to patients and improve the chance of survival.

# Variables in the dataset:

So there are 10 columns that are:

Id 

Diagnosis

Radius mean 

Texture mean

Perimeter mean

Area mean

Smoothness mean

Compactness mean

Concavity mean

Concave points


To check the correct prediction we have to check confusion matrix object and add the predicted results diagonally which will be number of correct prediction and then divide by total number of predictions.

After applying the different classification models, we have got below accuracies with different models:

1. Logistic Regression — 95.1%
2. Decision Tree Algorithm - 93.7% 
3. Random Forest Classsification - 96.5%

## Conclusion

From the accuracy and metrics above, the model that performed the best on the test data was the Random Forest Classifier with an accuracy score of about 96.5%. So I will choose that model to detect cancer cells in patients. Make the prediction/classification on the test data and show both the Random Forest Classifier model classification/prediction and the actual values of the patient that shows rather or not they have cancer.

I notice in the model that has misdiagnosed a few patients as having cancer when they didn’t and it misdiagnosed patients that did have cancer as not having cancer. Although this model is good, when dealing with the lives of others I want this model to be better and get it’s accuracy as close to 100% as possible or at least as good as if not better than doctors. So a little more tuning of each of the models is necessary.
