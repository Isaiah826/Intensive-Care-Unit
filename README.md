![icu_Image](Intensive-Care-Unit-ICU.jpg)
# Intensive-Care-Unit
Machine Learning Applications for Predicting NHS Patient Outcomes in Intensive Care Units Using Electronic Health Records (EHRs): Algorithms, Performance Metrics, and Clinical Implications

### Machine Learning for Predicting NHS ICU Patient Outcomes

This project focuses on using **machine learning (ML)** models to predict patient outcomes in NHS Intensive Care Units (ICUs) based on **Electronic Health Records (EHRs)**. 

#### Key Points:
- **Objective**: Predict ICU patient outcomes and explore the role of predictive modeling in improving patient care and resource allocation.
- **Algorithms Used**: Logistic Regression, Support Vector Machine (SVM), Random Forest, CatBoost, and Decision Trees  
- **Performance Metrics**:   Precision, Recall, F1-Score, and Area Under the Curve (AUC)  
- **Findings**:  
  - Predictive modeling demonstrates significant potential for improving clinical decision-making, optimizing healthcare efficiency, and allocating resources effectively.  
- **Implications**:  
  - Results support practical applications in healthcare for better decision-making and resource optimization.
This study underscores the importance of leveraging ML in healthcare settings for more informed and efficient outcomes.

### Demographic Data of Utilised Dataset
The ICU mortality distribution is imbalanced, with 60.69% of patients surviving and 39.31% not. Further analysis of factors driving the higher mortality rate is essential to improve outcomes and optimize healthcare resources.
![iuc1_Image](icu1.jpg)

### Distribution Of Dataset Across Various Characteristics
![iuc2_Image](icu3.png.jpg)
The mortality distribution by gender shows that 39% of female patients did not survive, compared to 37% of male patients. Female survival rates (61%) are lower than male survival rates (63%). Additionally, most ICU patients were male, with a majority surviving, while a higher proportion of female patients did not survive.

![iuc3_Image](icu5.jpg)
The mortality distribution by admission type shows survival rates of 72% for "Elective," 53% for "Emergency," 99% for "Newborn," and 49% for "Urgent" patients. Patients in the "Urgent" category have the lowest survival likelihood, while the "Newborn" category has the highest survival rate.

![iuc4_Image](icu6.jpg)
The mortality distribution by insurance type shows survival rates of 84% for "Government," 74% for "Medicaid," 43% for "Medicare," 80% for "Private," and 79% for "Self-Pay." Patients in the "Medicare" category have the lowest survival rate, while other insurance types show higher survival rates.

![iuc4_Image](icu7.jpg)
The tree map in Figure 4.7 shows the distribution of common diagnoses among surviving patients. The most frequent diagnosis is "Newborn" (21.23%), followed by "Coronary Artery Disease" (4.18%). Other notable diagnoses include "Pneumonia" (1.66%), "Sepsis" (1.21%), and "Chest Pain" (1.41%). "Newborn" is the most common diagnosis associated with survival.

![iuc5_Image](icu8.jpg)
The tree map in Figure 4.8 highlights the distribution of common diagnoses leading to patient death. "Pneumonia" accounts for the highest proportion (21.32%), followed by "Sepsis" (4.18%). Other notable diagnoses include "Congestive Heart Failure" (1.66%), "Intracanal Haemorrhage" (1.21%), and "Gastrointestinal Bleeding" (1.41%). "Pneumonia" is the leading diagnosis associated with patient deaths.

![iuc6_Image](icu9.jpg)

The bar chart in Figures 4.9 and 4.10 shows mortality distribution by first and last care units, including TSICU, MICU, CCU, SICU, CSRU, and NICU. MICU has the highest number of both patient survivals and deaths among all care units.

### Machine Learning Model
 **F1 Scores**:  
  - Models achieve F1 scores between **53% and 71%**, indicating effective prediction of ICU patient survival or mortality.  
  - Two models with F1 scores of **70% and 71%** highlight the robustness of the data preprocessing.

- **Precision**:  
  - Precision measures the accuracy of positive predictions, crucial for imbalanced datasets.  
  - **Random Forest**: 74%, **CatBoost**: 72%.  

- **Recall**:  
  - Recall assesses the model's ability to detect all true positives.  
  - **Random Forest**: 69%, **CatBoost**: 68%.  

These results underscore the effectiveness of the Random Forest and CatBoost models in predicting ICU outcomes with strong precision and recall performance.
