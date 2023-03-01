# IBM Machine Learning Professional Certificate
## Machine Learning Capstone Course

This repository contains the various notebooks completed during the course Machine Learning Capstone for IBM's Machine Learning Professional Certificate on Coursera.

### 1.1-Course Dataset EDA

Performs EDA on the Course Enrollment Dataset which is to be used for the Final Project (Capstone Project). Involves identifying keywords in course titles using a WordCloud, calculating the summary statistics and visualizations of the online course content dataset, determining popular course genres, calculating the summary statistics and create visualizations of the online course enrollment dataset and finally identifying courses with the greatest number of enrolled students.

*Tools: Pandas, Numpy, Matplotlib, Seaborn, Wordcloud*

### 1.2-BoW (Bag of Words) Dataset

Involves extracting Bag of Words (BoW) features from course titles and descriptions and building a course BoW dataset to be used for building a content-based recommender system later.

*Tools: Pandas, Gensim, NLTK*

### 1.3-Course Similarity

Focuses on calculating the similarity between any two courses using BoW feature vectors.

*Tools: Pandas, Numpy, Matplotlib, Seaborn, Gensim, NLTK, Scipy*

### 2.1-Content_User_Profile

Focuses on generating a user profile based on course genres and rating as well as generate course recommendations based on a user's profile and course genres.

*Tools: Pandas, Numpy, Scikit-learn*

### 2.2-Content_Course_Similarity

Involves obtaining the similarity between courses from a course similarity matrix and using the course similarity matrix to find and recommend new courses which are similar to enrolled courses.

*Tools: Pandas, Numpy, Seaborn, Matplotlib*

### 2.3-Content_Clustering

Performs k-means clustering on the original user profile feature vectors, applies PCA (Principle Component Analysis ) on user profile feature vectors to reduce dimensions, performs k-means clustering on the PCA transformed main components and generates course recommendations based on other group members' enrollment history.

*Tools: Pandas, Numpy, Seaborn, Matplotlib, Scikit-learn*

### 3.1-KNN

Introduces the user-item interaction matrix. Performs KNN-based collaborative filtering on the user-item interaction matrix.

*Tools: Pandas, Numpy, Scikit-surprise*

### 3.2-NMF

Performs NMF-based collaborative filtering on the user-item matrix.

*Tools: Pandas, Numpy, Scikit-surprise*

### 3.3-Neural Networks

Uses tensorflow to train neural networks to extract the user and item latent features from the hidden's layers and predict course ratings with trained neural networks.

*Tools: Pandas, Tensorflow, Keras, Matplotlib*

### 3.4-Regression_with_Embeddings

Focuses on building regression models to predict ratings using the combined embedding vectors.

*Tools: Pandas, Scikit-learn*

### 3.5-Classification_with_Embeddings

Focuses on building classification models to predict rating modes using the combined embedding vectors.

*Tools: Pandas, Scikit-learn, Imblearn*

### Final Presentation

Final Presentation of the Machine Learning Capstone project, discussing all the different aspects involved in designing a Course recommender System making use of a provided Courses enrollment dataset. Discusses all the different aspects involved in designing the course recommender system, ranging from basic EDA, determining courses similarity, applying machine learning models and publishing the resulting recommender system as a Streamlit app.
