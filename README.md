
# PCOS Identification using Machine Learning techniques 

This project focuses on identifying Polycystic Ovary Syndrome (PCOS) using machine learning techniques based on research outlined in a journal paper. Both supervised and unsupervised algorithms are employed to detect PCOS using heart and diabetes datasets downloaded from Kaggle. The project involves several stages, including preprocessing, feature selection, applying algorithms to all features, examining the results, and plotting feature importance graphs and ROC curves.


## Background 
Polycystic Ovary Syndrome (PCOS) is a common hormonal disorder in women, affecting reproductive health and overall well-being. Early detection and timely treatment are crucial for better management of the condition. This project addresses the need for an accurate and efficient diagnostic tool using machine learning techniques.
## Authors

- Shivani Aggarwal 
- Kavita Pandey 


## Dataset
The heart and diabetes datasets are downloaded from Kaggle. They contain relevant health information that may help in identifying PCOS in individuals.

- [Heart dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
- [Diabetes Dataset](https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset)

## Project Steps
1. **Data Preprocessing**: The datasets are preprocessed to handle missing values, normalization, and any necessary data transformations.

2. **Feature Selection:** Relevant features for PCOS identification are selected based on domain knowledge and statistical analysis.

3. **Extract Important Features:** Feature importance analysis is performed to determine the most significant features.

4. **Applying Algorithms:** Both supervised (e.g., Random Forest, Logistic Regression) and unsupervised (e.g., K-means, DBSCAN) algorithms are applied to all features, important features, and remaining features.

5. **Examine Results:** The performance of each algorithm is evaluated and compared to identify the most effective approach.

6. **Plot Feature Importance Graphs:** Feature importance graphs are plotted to visualize the impact of features on PCOS detection.

7. **Plot ROC Curve:** The Receiver Operating Characteristic (ROC) curve is plotted to assess the classification model's performance.

8. **Three-Category Detection:** Utilizing the information from all three categories of features (all, important, and remaining), a comprehensive PCOS detection method is proposed.

## Instructions
1. Download the heart and diabetes datasets from Kaggle and place them in the appropriate folders.

2. Run the data preprocessing script to clean and prepare the datasets.

3. Use feature selection techniques to identify relevant features for PCOS detection.

4. Apply supervised and unsupervised algorithms to all features, important features, and remaining features.

5. Evaluate the algorithms' results and compare their performance in PCOS identification.

6. Plot feature importance graphs and ROC curves for visualization and analysis.

Combine information from all three categories of features to create a comprehensive PCOS detection model.
