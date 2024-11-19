<h1 align="center">
🍇Raisin Binary Classification Models📈 
  
📈Prediction with Logistic Regression + KNN + SVM + DTC⚖️🔎

## Introduction
This project aims to classify two different varieties of raisins (Besni and Keçimen) grown in Turkey using their morphological features. By performing Exploratory Data Analysis (EDA) and implementing logistic regression models, the goal is to build effective classification models for raisin variety prediction. the aim is to enhance the understanding of raisin varieties and improve classification accuracy.

## Objectives
- Understand the dataset and its features.
- Clean and prepare the data for modelling.
- Feature engineering.
- Implement logistic regression and other algorithms to classify raisin varieties.
- Optimize model performance by tuning hyperparameters and focusing on important features.
- Compare the performance of logistic regression with other classification algorithms.


*The dataset and results are used for educational purposes, demonstrating the application of advanced machine learning techniques on real-world data. We aim to build an effective classification model to predict the type of raisin grains and gain a deeper understanding of machine learning techniques.

## About the Dataset
The dataset contains two types of raisins (Keçimen and Besni) grown in Turkey. 
Images of Kecimen and Besni raisin varieties were obtained with CVS. A total of 900 raisin grains were used, including 450 pieces from both varieties. These images were subjected to various stages of pre-processing and 7 morphological features were extracted.

**Dataset:** Raisin Grain 
- **Content:** 2 type of raisins (Besni(0) and Keçimen(1)).
- **Number of Rows:** 900  
- **Number of Columns:** 8  


**INPUTS**
- `Area`: The number of pixels within the boundaries of the raisin grain.
- `Perimeter`: The distance between the boundaries of the raisin grain and the surrounding pixels.
- `MajorAxisLength`: The length of the longest line that can be drawn on the raisin grain.
- `MinorAxisLength`: The length of the shortest line that can be drawn on the raisin grain.
- `Eccentricity`: A measure of the eccentricity of the ellipse which has the same moments as the raisins.
- `ConvexArea`: The number of pixels in the smallest convex shell of the region formed by the raisin grain.
- `Extent`: The ratio of the region formed by the raisin grain to the total pixels in the bounding box.


**Reference**
- CINAR I., KOKLU M. and TASDEMIR S., (2020). Classification of Raisin Grains Using Machine Vision and Artificial Intelligence Methods, Gazi Journal of Engineering Sciences, vol. 6, no. 3, pp. 200-209, December, 2020, DOI: https://doi.org/10.30855/gmbd.2020.03.03


## Conclusions:

In this project, we performed a comprehensive analysis to classify raisin varieties using their morphological features. Here are the key steps and findings:

1. **Exploratory Data Analysis (EDA)**:
   - Conducted thorough EDA to understand the dataset.
   - Identified and handled missing and duplicated values.
   - Analyzed basic statistics and categorical and numerical features.
   - Performed feature engineering, correlation analysis, and outlier detection.

2. **Machine Learning Models**:
   - Implemented several machine learning models:
     - **Logistic Regression**
     - **Support Vector Machine (SVM)**
     - **K-Nearest Neighbors (KNN)**
     - **Decision Tree Classifier**
   
3. **Model Comparison and Selection**:
   - Among all models, the **Grid Logistic Regression (GLR)** model demonstrated the highest accuracy and balanced performance.
   - **GLR Model Performance**:
     - Accuracy: 0.87
     - Balanced precision and recall values.
   - This indicates that the GLR model is robust and reliable for accurately identifying both raisin varieties.

The structured approach and thorough analysis ensured the selection of the most effective model for raisin classification.

---

## 🤝Contributing

Contributions are welcome! If you have any improvements, suggestions, or additional datasets and projects to share, please fork the repository and create a pull request.

<br>

## 🌱About Me

I'm Kalyani Wagh, a Data Scientist, passionate about data analysis, and machine learning.



🌐Feel free to connect with me!

<br>

🎯 Enhance your machine learning skills,<br>
💡 Share your insights with the community,<br>
✨ If you find this repository helpful, don't forget to give it a ⭐ star.<br>

Code with joy! 👩‍💻✨

---
