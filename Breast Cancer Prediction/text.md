# Breast Cancer Prediction

**CodersCave Verified Project** - [**Credentials**](https://drive.google.com/drive/folders/1Jw4gKMAb6iRmJnuVExpo05nt_rFfUrM0)

![MasterHead](https://miro.medium.com/v2/resize:fit:800/1*rQzG9B2w01YpBxpph3YTaw.png)

<font size="1">Image Courtesy: https://miro.medium.com/v2/resize:fit:800/1*rQzG9B2w01YpBxpph3YTaw.png</font>

Click on the following link to checkout the colab file.
- [Colab](https://colab.research.google.com/drive/1JkZSOMZzigfR7J5w49QrO4lTdNtX4J4-?usp=sharing)


---

## Problem Statement

Breast cancer is a significant health concern, affecting a substantial number of individuals worldwide. Early diagnosis of breast cancer is crucial for improving patient outcomes and reducing the impact of this disease. The problem at hand is the development of an accurate and reliable predictive model for breast cancer detection, which can assist medical professionals in making timely and informed decisions regarding patient care.

The primary issues to address in this project include:

1. **Early Detection:** Breast cancer often presents no noticeable symptoms in its early stages. The absence of early diagnosis can lead to advanced stages of the disease, making treatment less effective. Developing a model that can identify potential cases of breast cancer at an early stage is essential.

2. **Data Complexity:** Medical data used for breast cancer prediction is diverse and multi-dimensional, encompassing various attributes related to patient profiles and tumor characteristics. The challenge lies in effectively leveraging this complex data to create a predictive model.

3. **Accuracy and Reliability:** The predictive model needs to be highly accurate and reliable to ensure that benign and malignant tumors are correctly classified. Any misclassification could have severe consequences for patients.

4. **Generalizability:** The developed model should not be limited to a specific dataset or region. It should be applicable to a broader population and capable of generalizing to new data.

5. **Real-World Application:** The predictive model should be practical and accessible for use by medical professionals, allowing them to incorporate it into their diagnostic processes.

Overall, the problem statement addresses the need to develop a robust, accurate, and generalizable predictive model for breast cancer detection, with the ultimate goal of contributing to early diagnosis and improved patient care.

---

## Project Summary

Breast cancer is a prominent health concern with the potential to be life-threatening. This project focuses on creating a predictive model to aid in the early diagnosis of breast cancer. Early detection is vital for effective treatment and improving patient outcomes.

**Project Objective:**

Our objective is to develop an accurate predictive model that classifies breast tumors as benign or malignant. By analyzing patient data and tumor characteristics, we aim to assist medical professionals in making informed decisions about patient care.

**Dataset:**

We use a comprehensive dataset containing medical features extracted from breast cancer biopsies. These features include tumor size, cell shape, and mitotic count. Each record is labeled as benign or malignant.

**Methodology:**

1. Data Preprocessing: We perform data preprocessing, handling missing values, scaling, and encoding categorical variables.

2. Model Development: Various machine learning algorithms are used to create and train predictive models.

3. Model Evaluation: Models are evaluated using accuracy, precision, recall, and F1-score.

**Results and Significance:**

The successful development of our breast cancer prediction model has the potential to revolutionize healthcare. Early diagnosis can lead to better treatments and patient outcomes. This project contributes to medical data analysis and underscores the value of data-driven healthcare.

Our project, focusing on early breast cancer diagnosis, demonstrates the power of data-driven approaches in healthcare. By aiding in timely and accurate breast cancer diagnoses, our work can save lives and enhance patient care. This project is a testament to the impact of data-driven solutions in addressing real-world health challenges.

---

## Results

I have selected recall as the primary evaluation metric for our Breast Cancer Prediction model. And after removing the overfitted models which have recall, ROC-AUC, f1 scores for train as 100%, we get the final list:

| Sl. No. | Classification Model      |   Recall Train (%) |   Recall Test (%) |
|:--------|:--------------------------|---------------:|--------------:|
|    1    | Logistic regression       |       98.68  |      97.37 |
|    2    | Logistic regression tuned |       98.24  |      99.12 |
|    3    | Decision Tree tuned       |       95.82 |      94.74 |
|    4    | Random Forest tuned       |       98.68 |      96.49 |
|    5    | SVM                       |       98.68 |      95.61 |
|    6    | SVM tuned                 |       99.34 |      96.49 |
|    7    | Naive Bayes               |       93.63 |      96.49 |
|    8    | Naive Bayes tuned         |       94.50 |      95.61 |
|    9    | Neural Network            |       99.34 |      97.37 |
|    10    | Neural Network tuned      |       99.34 |      97.37 |

## Conclusion

In the Breast Cancer Prediction Project, we have arrived at key insights and conclusions:

- **Optimal Model Selection:** After a comprehensive evaluation of various machine learning models, the Tuned Logistic Regression model has emerged as the top performer.

- **Robust Model Comparison:** Our analysis considered a range of models, including SVM, Decision Tree, Random Forest, Naive Bayes, Neural Network, and XGBoost, highlighting the superiority of the Logistic Regression model.

- **Recall as the Primary Metric:** We selected recall as the primary evaluation metric for our breast cancer prediction model. A higher recall score indicates the model's ability to effectively identify malignant cases, emphasizing the importance of early detection and treatment.

- **Healthcare Impact:** Our project prioritizes the early and accurate identification of malignant breast cancer cases, which can have a significant impact on saving lives and enhancing patient care.

- **Data-Driven Solutions:** This project exemplifies the potential of data-driven approaches in addressing real-world health challenges and reinforces the value of selecting the right model and evaluation metric in healthcare applications.

In conclusion, our project underscores the critical role of model selection and evaluation metrics in healthcare. It demonstrates our commitment to early and accurate malignant breast cancer detection, contributing to better patient outcomes and healthcare practices.

---

## Author

- [Arindam Paul](https://www.linkedin.com/in/arindam-paul-19a085187/)

---

## Reference
 - [CodersCave Data Science Internship](https://www.linkedin.com/company/codersscave/)
