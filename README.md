# Optimizing Fetal Health Prediction Using CNN with Dropout

## Introduction
Fetal growth analysis is a critical part of prenatal care, providing insights into fetal well-being and development. Early detection of inadequate growth can prevent serious complications, benefiting both maternal and infant health.

With the rise in pregnancy-related health issues, timely monitoring is essential to improve outcomes, aligning with the UN’s **Sustainable Development Goal 3**: promoting well-being for all.

Machine learning (ML) and deep learning (DL) techniques, such as **logistic regression, support vector machines (SVMs), and convolutional neural networks (CNNs)**, are effective tools for analyzing medical data. This project uses a **CNN with dropout regularization** to enhance predictive accuracy and enable real-time fetal health monitoring.

---

## Scope of the Project
This project focuses on developing a **fetal health prediction portal** using the MERN stack and deep learning.

### Key Features
- **Data Handling:** Collect and preprocess Cardiotocogram (CTG) data  
- **Feature Engineering:** Extract meaningful fetal health indicators  
- **Model Development:** Implement Random Forest, MLP, and CNN models  

### Deliverables
- Trained deep learning model  
- User-friendly web interface  
- Comprehensive documentation  

### Limitations
- Performance may vary on unseen data  
- Real-time monitoring and certain risk factors are excluded  
- Clinical validation by medical experts is required  

---

## Existing System
Current fetal health monitoring relies on **Cardiotocography (CTG)**. Challenges include:

- Heavy reliance on clinician expertise → **diagnosis variability**  
- Difficulty handling **complex or high-dimensional data**  
- Limited diagnostic accuracy using traditional methods  

Although ML/DL models improve classification, many face **overfitting** and poor generalization. Advanced methods are needed for more accurate fetal health prediction.

---

## Proposed System
The project proposes a **CNN architecture with dropout** to classify fetal health based on CTG signals.

### Features
- **Classification Categories:** Normal, Moderate, Pathological  
- **Input Features:** Fetal heart rate (FHR) & uterine contractions  

### Techniques Used
- Dropout layers to prevent overfitting  
- Batch normalization and early stopping to stabilize training  

The dropout-enhanced CNN outperforms stacking ensemble methods in accuracy and generalization, providing **precise fetal health assessments** to optimize prenatal care.

---

## Model Architecture
<img width="914" height="502" alt="image" src="https://github.com/user-attachments/assets/141fce6d-1e4c-4f4f-960c-c786dd6740d1" />


**Structure:**  
Input Layer → Convolutional Layers → Dropout Layers → Fully Connected Layers → Output Layer (Softmax)

---

## Outputs

### Pair Plot of Fetal Health Features with Risk Categories
<img width="491" height="549" alt="image" src="https://github.com/user-attachments/assets/b76e8676-e455-49eb-8e0c-a73eff7aa931" />


### Distribution of Baseline FHR
<img width="647" height="447" alt="image" src="https://github.com/user-attachments/assets/8e5de6ba-d4cf-4bb7-86b1-01d25c9445bf" />


### Accuracy Graph
<img width="739" height="412" alt="image" src="https://github.com/user-attachments/assets/92def90e-bbd3-4075-a175-9ebacd06d811" />


### Loss Graph
<img width="826" height="456" alt="image" src="https://github.com/user-attachments/assets/ab982b9e-3d2a-48df-9ea3-d5db08c8119d" />


---

## References
1. Subrota, Mazumdar; Rohit, Choudhary; Aleena, Swetapadma. *An innovative method for fetal health monitoring based on artificial neural network using cardiotocography measurements.* 265-268, 2017. doi:10.1109/ICRCICN.2017.8234518  
2. Mehdi, Fasihi; Mohammad, H.; Nadimi-Shahraki; Ali, Jannesari. *A Shallow 1-D Convolution Neural Network for Fetal State Assessment Based on Cardiotocogram.* 2021. doi:10.1007/S42979-021-00694-6  
3. Shen, Liyue, et al. *Deep learning with attention to predict gestational age of the fetal brain.* arXiv preprint arXiv:1812.07102, 2018  
4. Jiarui, Feng; Jennifer, Lee; Zachary, A., Vesoulis; Fuhai, Li. *Predicting mortality risk for preterm infants using deep learning models with time-series vital sign data.* 4(1):108, 2021. doi:10.1038/S41746-021-00479-4  
5. Płotka, Szymon, et al. *FetalNet: Multi-task deep learning framework for fetal ultrasound biometric measurements.* ICONIP 2021, Part VI 28. Springer International Publishing, 2021
