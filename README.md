## Breast Cancer Detection using Machine Learning

![](https://github.com/addy-analytics/Breast-Cancer-Detection/blob/main/images/breast_cancer.gif)

### Abstract
The aim of this project is to create a machine-learning model capable of detecting breast cancer in mammograms obtained during routine screening examinations. The dataset encompasses radiographic breast images from approximately 20,000 female subjects, accompanied by metadata such as patient age, breast density, malignant cancer status, and additional follow-up details. The model will undergo training using the provided training set and subsequently be assessed using a concealed test set. The primary objective is to enhance the precision and efficiency of breast cancer detection, thereby reducing costs and unnecessary medical interventions. The overarching goal is to extend the benefits of early detection to a wider population. The current benchmark for the state-of-the-art probabilistic F1 score (pF1) stands at 55%.

### What is Breast Cancer
Cancer is a group of diseases characterized by the uncontrolled growth and spread of abnormal cells. These cells can invade and destroy surrounding tissues and can also spread to other parts of the body through the blood and lymph systems. There are many types of cancer, each with its own characteristics and treatment options. Breast cancer specifically refers to cancer that starts in the cells of the breast. It can occur in both men and women, but it is far more common in women. Breast cancer can begin in different parts of the breast, such as the ducts, lobules, or the connective tissue. It can also be invasive or non-invasive.
  
Some common risk factors for breast cancer include age, gender, family history, certain gene mutations (such as BRCA1 and BRCA2), hormonal factors, reproductive history, and lifestyle factors such as diet and physical activity. Globally, breast cancer is one of the most common cancers among women. 

According to data from the World Health Organization (WHO) and other sources, as of my knowledge cutoff in January 2022, here are some global statistics:
  
  - Incidence: In 2020, there were an estimated 2.3 million new cases of breast cancer worldwide.
  - Mortality: Breast cancer is a leading cause of cancer death in women globally. In 2020, there were an estimated 685,000 deaths from breast cancer.
 
It's important to note that these numbers are subject to change as new data becomes available, and regional variations exist. Additionally, advancements in early detection and treatment have contributed to improved survival rates for breast cancer.
  For the most current and region-specific statistics, it's recommended to refer to reputable sources such as the World Health Organization, national cancer registries, or cancer research organizations.
  
Breast cancer affects men as well as women. Although it affects women more frequently than men, breast cancer can still strike men. However, the primary goal of this project will be to examine breast cancer in women. Still, a good deal of this material also applies to men.
  
### Types of Breast Cancer Screening 
![](https://github.com/addy-analytics/Breast-Cancer-Detection/blob/main/images/breast_cancer_testing_screening.gif)

  - Screening tests for breast cancer are crucial instruments for early diagnosis, which raises the likelihood of a successful outcome considerably. The following are a few typical forms of breast cancer screening tests.
  - Mammography is the most popular technique for screening for breast cancer. It consists of X-ray images of the breast tissue.
  - Clinical Breast Examination (CBE): this is done by a medical professional by physically examine the breasts to feel for lumps or other abnormalities.
  - Breast Self-Examination (BSE): By regularly self-examining their breasts, women can become more familiar with how their breasts should feel and look, which will make it easier to notice changes.
  - Breast Ultrasound: this produces images of the breast tissue by using sound waves. It is frequently used as a follow-up test in women or if a mammography reveals an abnormality.
  - Breast MRIs (Magnetic Resonance Imaging): this produces fine detailed images of the breast by using radio waves and magnetic fields. It frequently works in tandem with mammography in specific circumstances, like screening high-risk people.
  - Breast Biopsy: A biopsy may be necessary to obtain a sample of tissue for microscopic inspection if an anomaly is found using alternative screening techniques. This aids in identifying cancerous cells in the cells.
-   Genetic testing: this might be advised for people who have specific risk factors or a family history of breast cancer. It can recognise particular genetic mutations that raise the likelihood of breast cancer development.

### Facts and Figures
## Project Description
  - Objective:
  The primary goal of this project is to develop a machine learning model for the early detection of breast cancer using the Wisconsin breast cancer dataset. Early detection is crucial for improving patient outcomes, and machine learning algorithms can assist in automating the analysis of medical data for timely diagnosis.
The dataset used in this project is from Breast Cancer Wisconsin (Diagnostic) Data Set, however it can be directly accessed from Scikit learn library's collection of datasets as `sklearn.datasets.load_breast_cancer` or as  csv file of data has been externally loaded in the repository
Extensive testing revealed that among various machine learning models(Random Forest, Logistic Regression, Decision Tree) emploted, the Support Vector Machine (SVM) stands out with the highest reported accuracy, reaching approximately 97%, for the detection of breast cancer.

 -  Dataset:
  The project will utilize the Wisconsin Breast Cancer dataset [Link Here](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data/data), which contains features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. These features include measures related to the cell nuclei present in the images. 
  
### Role of Machine Learning in Detecting Breast Cancer
Machine learning plays a crucial role in detecting breast cancer by leveraging advanced computational techniques to analyse and interpret complex data. Here are key aspects of the role of machine learning in breast cancer detection:
- Radiomics and Texture Analysis: In this project we focus on analyzing radiomic features extracted from medical images, such as texture and shape characteristics, using machine learning algorithms. These features provide valuable information about tissue properties and contribute to more accurate cancer detection. 
- Early Detection: machine learning models can analyze mammography images to identify patterns and anomalies indicative of early-stage breast cancer.
- Image Classification: algorithms can be trained to classify breast cancer images into categories such as benign or malignant. Convolutional Neural Networks (CNNs) are commonly used for image classification tasks, providing high accuracy in distinguishing between different tissue types.
- Risk Prediction: machine learning models can assess a patient's risk of developing breast cancer based on various factors such as genetic markers, family history, and lifestyle. Predictive models help identify individuals who may benefit from more frequent screening or preventive measures.

In summary, amongst many others, machine learning plays a pivotal role in breast cancer detection by combining advanced algorithms with diverse datasets, ultimately contributing to early diagnosis, personalized treatment, and improved patient outcomes.

## Results

The SVM model initially attained an accuracy of 97%. However, following the application of a normalization technique and optimization of C and Gamma parameters, the accuracy experienced a slight reduction to 96%.

## References
