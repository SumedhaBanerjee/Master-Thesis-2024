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

- Review on Conventional Methods: Argade et al. proposed Image Processing and Data Mining Techniques for automatic detection of Diabetic Retinopathy (3).
Mukherjee et al. proposed another conventional technique. The methodology followed by them included Image Processing which involves background normalization and contrast enhancement using histogram equalization. It is followed by Optical Disk Detection, Blood Vessel Extraction and Exudate Detection (4).

- Review on Machine Learning Techniques: Bhatia et al. proposed a Machine Learning Model for diagnosis of Diabetic Retinopathy using ensemble of classification algorithms, alternating decision tree, AdaBoost, Naive Bayes, Random Forest and SVM and achieved a maximum accuracy of 90 %, sensitivity of 94 % and F1-score of 90 % (5). Labhade et al. applied soft computing techniques for Diabetic Retinopathy Detection in which they used different classifiers like SVM, Random Forests, Gradient boost, AdaBoost, Gaussian Naive Bayes (6). Mohammadian et al. proposed a comparative analysis of 9 common Machine Learning Classification Algorithms for Diabetic Retinopathy Detection (7).

- Review on Deep Learning Approaches: Doshi et al. proposed a Deep Learning Approach involving a Deep Convolutional Neural Network with a specific Network Architecture obtaining a Quadratic Kappa Score of 0.3996 (8). Xu et al. applied Deep Convolutional Neural Networks for early automated detection of Diabetic Retinopathy and achieved a highest accuracy of 94.5% (9). Gargeya et al. proposed a Deep Learning Model for identification of Diabetic Retinopathy and achieved a Sensitivity of 0.93, Specificity of 0.87 and Area Under the Receiver Operating Characteristic Curve of 0.94 (10).


### Methodology:

<img width="689" height="322" alt="Capture 3" src="https://github.com/user-attachments/assets/073e678c-60c7-4cdd-9a60-588bf123c424" />


### Tools Used:

<img width="938" height="420" alt="Capture 5" src="https://github.com/user-attachments/assets/7c3706fc-6b7f-46cf-b51f-1e9e3fc0a3d2" />

### Dataset Description:

The dataset consists of retinal fundus images used for detecting diabetic retinopathy. A large dataset of retinal images was collected from Kaggle. The dataset 
consists of 2000 retinal images out of which, 1000 images are labelled as 1(Healthy folder) and 1000 images are labelled as 0 (DR_presence folder). 























