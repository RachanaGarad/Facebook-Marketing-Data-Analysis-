# Facebook-Marketing-Data-Analysis-
Unsupervised Analysis Project(PCA,ML)

**Objective**
The objective of this project is to analyze the impact of video content, specifically live streaming, on social media engagement. The focus is on Facebook Live sellers in Thailand to understand how live streaming influences viewer interaction and engagement metrics.

**Introduction**
The marketing landscape is evolving rapidly with the advent of social media, and within this space, video content, especially live streaming, has emerged as a critical player. This study explores the effects of video content with a particular focus on Facebook Live sellers in Thailand, a market that has shown a high level of interest in live streaming as a social commerce platform .

**Analysis**
The analysis involved several steps:

Data Collection: Data was gathered from Facebook Live streams by sellers in Thailand.
Preprocessing: The data was cleaned and preprocessed to ensure accuracy and consistency.
Cluster Analysis: Using the elbow method and dendrograms, five clusters were identified as the optimal number for segmenting the data.
Principal Component Analysis (PCA): PCA was performed to reduce dimensionality and explain the variance within the data.
Model Evaluation: Various models were evaluated using metrics such as train-test gap, AUC score, and confusion matrix to determine their performance .

**Technology**
Python: Used for data analysis and model building.
Pandas: For data manipulation and analysis.
Scikit-learn: For implementing machine learning algorithms and PCA.
Matplotlib and Seaborn: For data visualization.
Jupyter Notebook: As the development environment.

**Results**
The results of the analysis are summarized below:

Cluster Analysis: Five distinct clusters were identified, each representing a unique segment of engagement patterns.
Cluster 1 - "Balanced Engagers": Moderate engagement, indicating balanced involvement without extreme reactions.
Cluster 2 - "Reaction Provokers": High instinctual reactions such as anger or surprise, often due to controversial content.
Model Performance:
Model 1: Best performing model with a train-test gap of 0.016 and AUC score of 0.72. The confusion matrix showed a balance between true positives (95) and true negatives (362), with 18 false positives and 100 false negatives.
Model 3: Showed a smaller train-test gap but lower AUC score of 0.676. The confusion matrix had 377 true negatives and 70 true positives, with increased false negatives (125) .
Conclusion
This project provides insights into how live video content affects user engagement on social media, specifically Facebook Live in Thailand. The findings can help marketers and businesses optimize their social media strategies to enhance viewer engagement and interaction.
