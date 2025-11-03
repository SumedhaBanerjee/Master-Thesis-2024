# Deep Learning-Based Detection of Diabetic Retinopathy Using ResNet (Residual Network) Architecture

<img width="843" height="337" alt="PNG" src="https://github.com/user-attachments/assets/a8d87d87-0583-4896-baf6-e54951f38001" />


#### Submitted by,
Sumedha Banerjee (19458122001)

#### Degree Programme:
Master of Sceince 

#### Batch: 
2022-2024

#### Year:
2023-2024

#### Under the Supervision of:
Prof. Mithun Mazumdar (HOD, Data Analytics Department)

#### Submitted to, 
Data Analytics

#### at
Institute of Management Study


<img width="608" height="266" alt="Capture 1" src="https://github.com/user-attachments/assets/4e9146b9-00e7-4a71-9a19-f72057e3c53c" />


### Abstract:

Diabetic Retinopathy (DR) is a medical condition that 
affects the eye for people who are diabetic. It weakens and 
damages the blood vessels in tissues of the retina. This 
condition highly affects people who do not manage their 
blood sugar and pressure level properly. The damaged 
blood vessels leak and cause dark spots in the vision of 
those who are affected. Early detection and timely 
intervention are crucial to prevent severe vision loss. So, this 
is done manually by the doctor by placing drops in the 
patient’s eyes to dilate the pupil so that they get a better 
view of the inside and it will help them take a better look. 
This is where Deep Learning comes into play. This report 
presents a deep learning-based model for the automated 
detection and classification of diabetic retinopathy from 
retinal images. Leveraging convolutional neural networks 
(CNNs), the proposed model analyses fundus photographs 
to identify the presence and absence of DR. One thousand 
Healthy retinal images and another 1000 of DR-affected 
images taken from the dataset of Kaggle are utilized for this 
project. The model achieves high accuracy in distinguishing 
between the Healthy retinal images and the DR affected 
ones, demonstrating its potential as a reliable assistive tool 
for ophthalmologists in screening and diagnosis. The 
proposed method also uses ResNet50 (Residual Network 
that is 50 layers deep) model. Due to its depth and better 
transfer learning capabilities, the proposed model with 
ResNet50 achieved 97.16% classification accuracy. 
Performance metrics such as accuracy, sensitivity, 
specificity, and the area under the receiver operating 
characteristic curve (AUC-ROC) are discussed to evaluate 
the model's efficacy. The implementation details, data 
preprocessing techniques, and model architecture are 
elaborated upon, highlighting the advancements in deep 
learning that enable improved diagnostic capabilities for 
diabetic retinopathy.  
Keywords: Diabetic Retinopathy, Deep Learning, 
Convolutional Neural Networks, Retinal Images, Transfer 
Learning, ResNet50.


<img width="947" height="309" alt="Capture 2" src="https://github.com/user-attachments/assets/8ba3b356-2e00-4512-86eb-a704d00ef4cc" />


### Problem Statement:

1) Challenges in Manual Testing: Diabetic retinopathy (DR) is a leading cause of vision impairment and blindness among diabetic patients, requiring timely and accurate detection for effective treatment. However, the current diagnosis largely depends on manual examination of retinal images by ophthalmologists. This process is time-consuming, labor-intensive, and subject to human error and variability in interpretation. Additionally, there is a significant shortage of eye care specialists, especially in remote and underserved areas, leading to delays in diagnosis and treatment. 
2) Need for an Automated, Accurate Solution: Given the limitations of manual testing, there is an urgent need for an automated, reliable, and efficient solution to detect diabetic retinopathy. A deep learning-based model can offer high accuracy and consistency in identifying DR from retinal images, reducing the burden on healthcare professionals and increasing access to early diagnosis and intervention. Such a solution would improve patient outcomes, prevent vision loss, and enhance the overall efficiency of healthcare systems.

### Aim:
- To create a deep learning-based model capable of analyzing retinal images and accurately detecting signs of diabetic retinopathy. 
- Enhance early detection rates of diabetic retinopathy, enabling timely intervention and treatment.


### Research Questions:

1. Can a deep learning-based model accurately detect diabetic retinopathy from retinal images?

2. How does the performance of the proposed model compare to traditional manual screening methods in terms of accuracy, speed, and scalability?

3. What are the critical features and patterns in retinal images that the model uses to identify diabetic retinopathy?

4. What are various model used in Diabetic Retinopathy?

5. Which type of datasets has been used for Diabetic Retinopathy?


### Literature Review: 
Many conventional methods, Machine Learning techniques and few Deep Learning approaches have been attempted for Diabetic Retinopathy detection.

- Review on Conventional Methods: Argade et al. proposed Image Processing and Data Mining Techniques for automatic detection of Diabetic Retinopathy (1).
Mukherjee et al. proposed another conventional technique. The methodology followed by them included Image Processing which involves background normalization and contrast enhancement using histogram equalization. It is followed by Optical Disk Detection, Blood Vessel Extraction and Exudate Detection (2).

- Review on Machine Learning Techniques: Bhatia et al. proposed a Machine Learning Model for diagnosis of Diabetic Retinopathy using ensemble of classification algorithms, alternating decision tree, AdaBoost, Naive Bayes, Random Forest and SVM and achieved a maximum accuracy of 90 %, sensitivity of 94 % and F1-score of 90 % (3). Labhade et al. applied soft computing techniques for Diabetic Retinopathy Detection in which they used different classifiers like SVM, Random Forests, Gradient boost, AdaBoost, Gaussian Naive Bayes (4). Mohammadian et al. proposed a comparative analysis of 9 common Machine Learning Classification Algorithms for Diabetic Retinopathy Detection (5).

- Review on Deep Learning Approaches: Doshi et al. proposed a Deep Learning Approach involving a Deep Convolutional Neural Network with a specific Network Architecture obtaining a Quadratic Kappa Score of 0.3996 (6). Xu et al. applied Deep Convolutional Neural Networks for early automated detection of Diabetic Retinopathy and achieved a highest accuracy of 94.5% (7). Gargeya et al. proposed a Deep Learning Model for identification of Diabetic Retinopathy and achieved a Sensitivity of 0.93, Specificity of 0.87 and Area Under the Receiver Operating Characteristic Curve of 0.94 (8).


### Methodology:

<img width="689" height="322" alt="Capture 3" src="https://github.com/user-attachments/assets/073e678c-60c7-4cdd-9a60-588bf123c424" />


### Tools Used:

<img width="938" height="420" alt="Capture 5" src="https://github.com/user-attachments/assets/7c3706fc-6b7f-46cf-b51f-1e9e3fc0a3d2" />

### Dataset Description:

The dataset consists of retinal fundus images used for detecting diabetic retinopathy. A large dataset of retinal images was collected from Kaggle. The dataset 
consists of 2000 retinal images out of which, 1000 images are labelled as 1(Healthy folder) and 1000 images are labelled as 0 (DR_presence folder). 


### Train-Test Split:

- 70% Training Set (1400 images)
- 30% Test Set (600 images)


### ResNet50 model summary:

<img width="785" height="487" alt="Capture 6" src="https://github.com/user-attachments/assets/910991e4-6cdb-4caa-bfac-a0c3091cf149" />


### Model Training Loss and Training Accuracy Graph:

<img width="846" height="260" alt="Capture 7" src="https://github.com/user-attachments/assets/90bdccda-48f1-4f91-a59f-583f3a01c8d9" />


### Model Evaluation:

<img width="778" height="276" alt="Capture 8" src="https://github.com/user-attachments/assets/6c1bb251-318d-4382-8e85-0d73bc7c1a83" />


### Confusion Matrix:

<img width="642" height="383" alt="Capture 9" src="https://github.com/user-attachments/assets/a114f9f5-7661-4a42-a108-27e6220a220a" />


### AUC-ROC Curve:

<img width="878" height="469" alt="Capture 10" src="https://github.com/user-attachments/assets/032d28b1-2f98-4bd5-b4d9-5c76494856c0" />


### Model Deployment:

- Healthy image prediction


<img width="785" height="330" alt="Capture 11" src="https://github.com/user-attachments/assets/1245c85c-af11-4cdf-978f-fe41ec971746" />




- Diabetic Retinopathy image prediction


<img width="787" height="345" alt="Capture 12" src="https://github.com/user-attachments/assets/bc392971-a7c2-4c61-ba0a-fdbd874ead0b" />


### Limitations:

Here are several key limitations to consider: 

1) Data Limitations-

- Insufficient Training Data: Deep learning models require large amounts of labelled data to perform effectively. Insufficient data can lead to poor model performance and overfitting. 
- Quality of Annotations: The accuracy of the model heavily depends on the quality of the annotations. Inconsistent or incorrect labelling by human experts can introduce noise and affect the model’s performance.
- Imbalanced Datasets: If the dataset is imbalanced (e.g., significantly more healthy images than diseased ones), the model may become biased towards the majority class, reducing its ability to detect diabetic retinopathy accurately.
- Lack of Diversity: A dataset that lacks diversity in terms of patient demographics, imaging conditions, and disease stages may not generalize well to real-world scenarios.
- Source Variability: Images from different devices or clinical settings can have varying qualities, which can affect the model’s performance if not properly addressed. 

2) Model Limitations-

- Overfitting: The model may perform well on the training data but fail to generalize to new, unseen data due to overfitting.
- Limited Generalization: Even with diverse training data, the model may not generalize well to different imaging devices not represented in the training set. 
- Black-box Nature: Deep learning models, particularly convolutional neural networks (CNNs), are often criticized for their lack of interpretability. Understanding the decision-making process of these models is challenging, which can be problematic in clinical settings.
- Computational Complexity: Deep learning models can be computationally intensive, requiring significant resources for training and inference, which may limit their practical deployment in resource-constrained environments. 

3) Clinical Integration-

- Clinical Validation: The model needs thorough validation in real-world clinical settings to ensure it performs well outside of controlled experimental conditions.
- Acceptance by Clinicians: The adoption of deep learning models in clinical practice requires acceptance and trust from healthcare providers, which can be hindered by the model's complexity and lack of transparency. 

4) Performance Metrics-

- Inadequate Metrics: Commonly used metrics like accuracy, precision, and recall may not fully capture the model’s performance, especially in detecting rare but critical cases.
- Threshold Selection: The choice of threshold for classification can significantly impact the model’s performance metrics, making it important to choose thresholds that balance sensitivity and specificity appropriately. 

5) Maintenance and Updates-

- Model Degradation: Over time, the model’s performance may degrade due to changes in disease prevalence, new imaging technologies, or variations in clinical practices, necessitating regular updates and retraining. 
- Continuous Learning: Implementing a system for continuous learning and updating the model with new data is challenging but necessary to maintain high performance. 


### References:

[1]. Ketki S. Argade, Kshitija A. Deshmukh, Madhura M. Narkhede, Nayan N. Sonawane and Sandeep Jore: ”Automatic Detection of Diabetic Retinopa-thy using Image Processing and Data Mining 
Techniques”, International Conference on Green Computing and Internet of Things (ICGCIoT), 2015. 
 
[2]. Anupriyaa Mukherjee, Diksha Rathore, Supriya Shree and Asst Prof. Shaik Jameel:”Diagnosis of Diabetic Retinopathy”, Int. Journal of Engineering Research and Applications, ISSN : 2248-9622,Vol. 5, Issue 2, ( Part -4) February 2015. 
 
[3]. Karan Bhatia, Shikhar Arora and Ravi Tomar:”Diagnosis of Diabetic Retinopathy Using Machine Learning Classification Algorithm”, 2nd International Conference on Next Generation Computing Technologies (NGCT), 2016. 
 
[4]. Jyoti Dnyaneshwar Labhade, L. K. Chouthmol and Suraj Deshmukh:”Diabetic retinopathy detection using soft computing techniques”, Conference on Automatic Control and Dynamic Optimization Techniques (ICACDOT), 2016. 
 
[5]. Saboora Mohammadian, Ali Karsaz and Yaser M. Roshan:”A Comparative Analysis of Classification Algorithms in Diabetic Retinopathy Screening”, 29th International Conference on Software Engineering and Knowledge Engineering (SEKE), 2017. 
 
[6]. Darshit Doshi, Aniket Shenoy, Deep Sidhpura and Prachi Gharpure:”Diabetic retinopathy detection using deep convolutional neural networks”, International Conference on Computing, Analytics and Security Trends (CAST), 2016. 
 
[7]. Kele Xu, Dawei Feng and Haibo Mi:”Deep Convolutional Neural Network-Based Early Automated Detection of Diabetic Retinopathy Using Fundus Image”, Molecules, 2017 (Open Access Journal), 22,2054; doi:10.3390/molecules22122054. 
 
[8]. Rishab Gargeya and Theodore Leng:”Automated Identification of Diabetic Retinopathy Using Deep Learning”, American Academy of Ophthalmology, 2017. 

[9]. Dataset link: https://www.kaggle.com/datasets/sovitrath/diabetic-retinopathy-224x224-2019-data 
















