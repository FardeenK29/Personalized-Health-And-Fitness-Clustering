# PROJECT TITLE: Personalized Health & Fitness Clustering
# Deep Bhanushali(A012) &  Fardeen Khatri(A018)

📌 PROJECT OVERVIEW:

This project applies unsupervised machine learning techniques—specifically K-Means clustering—to group individuals based on their fitness and health-related data from the FitLife dataset. The goal is to generate actionable and personalized fitness recommendations for different clusters of users by analyzing trends across key attributes such as age, BMI, heart rate, hydration, sleep, and more.

===========================================================

🎯 OBJECTIVES:
- Cluster users with similar health and fitness patterns using K-Means.
- Use PCA and t-SNE for dimensionality reduction and visualization.
- Analyze health trends within clusters.
- Generate personalized recommendations based on cluster analysis.

===========================================================

📁 DATASET:
- File Used: fitlife_health_fitness.csv
- Attributes: age, height, weight, BMI, steps, heart rate, blood pressure, stress, hydration, sleep, intensity, calories burned, and more.

===========================================================

🛠️ TOOLS & LIBRARIES USED:
- Python
- Pandas, NumPy – Data wrangling
- Matplotlib, Seaborn – Data visualization
- Scikit-learn – KMeans, PCA, t-SNE, preprocessing
- Yellowbrick – KElbowVisualizer for optimal k
- Jupyter Notebook / Google Colab environment

===========================================================

🔍 PROJECT STEPS:

STEP 1: INSTALL & IMPORT LIBRARIES
  - Import required Python libraries and install additional dependencies.

STEP 2: LOAD & INSPECT DATA
  - Load the dataset and preview its structure using pandas.

STEP 3: DATA PREPROCESSING
  - Drop irrelevant columns like ID and text-based metadata.
  - Handle missing values and remove duplicates.
  - Encode categorical values (e.g., 'intensity') using Label Encoding.
  - Normalize selected features using StandardScaler.

STEP 4: FIND OPTIMAL NUMBER OF CLUSTERS
  - Use the Elbow Method (with Yellowbrick) to determine the optimal number of clusters (k) for K-Means.

STEP 5: APPLY K-MEANS CLUSTERING
  - Train a K-Means model on the preprocessed data.
  - Assign cluster labels to each user and evaluate clustering using the silhouette score.

STEP 6: VISUALIZE CLUSTERS
  - Use PCA for 2D visualization of clusters.
  - Use t-SNE for both 2D and 3D projections to visualize and validate cluster separations.

STEP 7: GENERATE PERSONALIZED RECOMMENDATIONS
  - Define a function that maps cluster labels to health/fitness advice.
  - Append the recommendations to the dataset for each user.

===========================================================

📊 SAMPLE RECOMMENDATIONS BY CLUSTER:

Cluster 0 ➤ Increase daily steps and hydration, reduce stress levels  
Cluster 1 ➤ Maintain balanced workouts and optimize sleep routine  
Cluster 2 ➤ Focus on improving endurance with high-intensity workouts  
Cluster 3 ➤ Incorporate strength training and monitor blood pressure  
Cluster 4 ➤ Work on weight management and cardiovascular health  

===========================================================

📈 OUTPUTS:
- Cluster-labeled dataset with visualizations.
- Personalized health recommendations based on cluster group.
- PCA and t-SNE plots for visual interpretation of clusters.

===========================================================

📌 CONCLUSION:
This project showcases how unsupervised learning techniques like K-Means, combined with dimensionality reduction tools, can uncover hidden patterns in fitness data and provide targeted wellness strategies. The methodology supports personalization in health tracking applications.

===========================================================

👤 AUTHOR:
A012_DeepBhanushali & A018_FardeenKhatri

🔁 VERSION:
1.0

🗓️ DATE:
7th April 2025

===========================================================

LICENSE:
This notebook is intended for academic and educational purposes only.

