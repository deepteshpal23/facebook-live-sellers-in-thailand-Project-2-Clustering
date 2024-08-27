Title: Understanding Consumer Engagement Patterns on Facebook for Thai Fashion and Cosmetics Retailers

Introduction-
Social media platforms have emerged as powerful tools for businesses to connect with their target audience. 
Facebook, with its vast user base, has become a central platform for various industries, including fashion and cosmetics.
To effectively leverage this platform, understanding consumer engagement patterns is crucial. This study focuses on analyzing 
the engagement metrics of 10 Thai fashion and cosmetics retailers on Facebook to identify trends, patterns, and factors influencing 
consumer interaction.

Problem Statement-
Despite the increasing importance of social media for businesses, there is a limited understanding of consumer engagement patterns on 
platforms like Facebook, particularly within the Thai fashion and cosmetics industry. This study aims to address this gap by examining 
the factors influencing consumer engagement with Facebook posts and identifying opportunities for businesses to enhance their social media strategies.

Objectives-
1. To analyze consumer engagement metrics for Facebook posts of Thai fashion and cosmetics retailers.
2. To identify clusters of posts based on engagement patterns using unsupervised machine learning techniques.
3. To examine the impact of Facebook Live on engagement variability.
4. To analyze seasonal patterns in engagement metrics.
5. To identify outlier posts and understand their characteristics.

Key Tasks-
1. Data Collection and Preprocessing: Gather and clean the dataset containing Facebook post information and engagement metrics.
2. Exploratory Data Analysis: Conduct an in-depth analysis of the dataset to understand data distribution, identify outliers, and 
visualize relationships between variables.
3. Clustering: Apply K-means and Agglomerative clustering algorithms to group similar posts based on engagement metrics.
4. Principal Component Analysis (PCA): Reduce data dimensionality and identify underlying patterns in engagement.
5. Time Series Analysis: Analyze engagement metrics as time series data to identify seasonal trends.
6. Outlier Analysis: Identify and analyze outlier posts to understand their unique characteristics.

Data Description
The dataset consists of 7051 Facebook posts from 10 Thai fashion and cosmetics retailers. Each post is represented by 11 features, 
including post type (video, photo, status, or link), publication date, and various engagement metrics such as number of reactions 
(likes, loves, wows, hahas), comments, and shares. The dataset is multivariate and contains no missing values.
status_id (ID) - Integer
status_type (Feature) - Categorical
status_published (Feature) - Categorical
num_reactions (Feature) - Integer
num_comments (Feature) - Integer
num_shares (Feature) - Binary
num_likes (Feature) - Integer
num_loves (Feature) - Binary
num_wows (Feature) - Binary
num_hahas (Feature) - Binary

'''
