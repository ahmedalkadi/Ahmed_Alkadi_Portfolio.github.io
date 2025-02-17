---
title: "Machine Learning Projects <br/>" 
excerpt: "The following page highlights some selected projects I have created using AI. You are welcome to visit my [GitHub](https://github.com/ahmedalkadi) Account to review and clone the code."
collection: portfolio 
---

The following page shows selected projects utilizing AI in :
=====
1. Computer Vision.
2. Deepfake.
3. Natural language Models (NLP) Arabic and English.
4. Recommender Systems.
5. Large language models (LLMs).
6. Machine learning (Supervised and Unsupersived).

Some other Related topics:
-----
1. Random Search Algorithm.
2. Quantum Machine Learning Algorithms.
3. Optimizers From Scratch Implementation.
4. Models Architecture From Scratch Implementation.
5. Webpages Scrapping. <br/><br/>


# GitHub Projects:

## Computer Vision Projects:
- [Visual And Textual Product Similarity Recommendation](https://github.com/ahmedalkadi/Visual_And_Textual_Products_Similarity):
  This project recommends products based on their textual and visual similarity using cosine similarity. Visual features are extracted with ResNet-50, textual features with TinyBERT-6L, and images are preprocessed by        removing backgrounds using a UNet model with MobileNetV2 encoder. Features are combined into vectors, stored in a vector database, and used to find and visualize the top similar products.

  This model was used in a fashion recommendation project supervised by Twenty Too © Fashion company.

  For more details, please follow the link for [video demonstration](https://drive.google.com/file/d/1NZfyY95Ria7TJMhhy76MW5mRTGM6eOKU/view?usp=sharing)

<br/>

- [Driver distraction detector](https://github.com/ahmedalkadi/Distracted-Driver-Detection_Deep_Learning):
  The project aims to identify the types of distracted driver through their facial and body movement like arms and face poses. The project went through many stages of testing to increase the accuracy of the prediction from   using simple NN to use pretrained models.

## Deep fake project.
- [Video Lip-Syncing](https://github.com/ahmedalkadi/Hight_Quality_LipSync):
  The Lip-Syncing project focuses on creating a system that synchronizes lip movements with spoken audio using deep learning techniques. The project involves detecting language and converting audio to text, aligning lips    with the audio using Wav2Lip models, and enhancing video quality after face detection. The system is evaluated using LSE-D and LSE-C metrics, ensuring accurate and realistic lip-sync performance. This project aims to      improve multilingual lip-syncing, especially in Arabic, by fine-tuning the model with region-specific data.

## Natural language Models (NLP) Projects.
- [Arabic Dialect Classifier](https://github.com/ahmedalkadi/Arabic_Dialect_Detector_NLP):
  The project aims to build a model to identify and classify different Arabic dialects from text data, ranges from using traditional ML Algorithms like LR and decision trees to more complex DL approaches such as LSTMs and   hybrid models combining CNNs with LSTMs, to improve accuracy in dialect classification.
- [Arabic POS Detector](https://github.com/ahmedalkadi/Arabic_POS_Detector_NLP):
  The objective of this project is to perform Part-of-Speech (POS) tagging on Arabic text using Recurrent Neural Networks (RNNs). Specifically, the Universal POS (UPOS) tags, a standardized set of POS tags that aims to      cover all languages, will be used for tagging. The dataset provided contains labeled data for Arabic text with Part-of-Speech (POS) tags in CoNLL-U format

## Recommender Systems projects.
- [Recommendation_Systems_IMDb_Movies_And_Users_Similarity](https://github.com/ahmedalkadi/Recommendation_Systems_IMDb_Movies_And_Users_Similarity):
  The project involves two models; one for calculating movie similarity based on features. The other recommending movies to users by predicting their ratings. The first model uses cosine similarity, while the second         leverages user-rating history with matrix factorization.

  For more details, please follow the link for [video demonstration](https://drive.google.com/file/d/1oHviItTj6_KJp0JPsm_uErOuLRVepD3D/view?usp=sharing)
<br/>

## LLMs projects:
- [SpaceX RAG system](https://github.com/ahmedalkadi/SpaceX_RAG_system):
  The SpaceX Retrieval-Augmented Generation (RAG) system project focuses on building a robust information retrieval and question-answering system using data about SpaceX. The system combines retrieval-augmented              generation techniques with a language model to provide accurate and contextually relevant answers based on SpaceX documents, PDFs, and videos. In this project, I used RAG to pull in relevant information from a curated     dataset before generating responses, which enhances the model's ability to provide accurate answers rooted in specific SpaceX-related knowledge. I implemented an embedding-based search to enable the model to identify      the most relevant information for each query, drawing on resources beyond the training data. This setup allows for more precise and nuanced responses by augmenting generative outputs with fact-based retrieval.
  
## Machine learning (Supervised and Unsupersived) Projects.
- [Devices price classification](https://github.com/ahmedalkadi/devices-price-classification):
  The Devices Price Classification project was designed to predict price categories for electronic devices based on features such as camera quality, screen size, and weight. The project combined machine learning with API    development to create a user-friendly prediction system. I used Python to build a machine-learning model that classifies devices into different price categories based on input features. To make the model accessible, I     developed a RESTful API with Spring Boot, which included endpoints for device operations such as GET and POST requests. This allowed users to retrieve device data from an H2 database, add new records, and get price        predictions in real time. For the user interface, I created a Flask application with HTML pages, providing an easy-to-use interface where users could enter device IDs and trigger predictions. The Flask app integrated      with the API, passing device data to the prediction model and displaying the results.

  For more details, please follow the link for  [video demonstration](https://drive.google.com/file/d/15g8Gqzb6F90OPUbjFGOSOOgNvGsYQ625/view?usp=sharing)
<br/>
<br/>

- [Face_Pose_Detector_Machine_Learing](https://github.com/ahmedalkadi/Face_Pose_Detector_Machine_Learing):
  A face pose estimator is a computer vision technique that determines the orientation and position of a human head relative to a camera In this Repo you can detect the pose angles of a picture , web cam video or imported   video In this Repo an augmentation was carried out to help inhance the performance of the roll angle.
- [Bank_Account_Business_Analysis_Unsupervised_Machine_Learning](https://github.com/ahmedalkadi/Bank_Account_Business_Analysis_Unsupervised_Machine_Learning):
  This project aims to perform an analysis of bank account data using unsupervised machine-learning techniques. The primary objectives include evaluating different data transformation techniques, comparing the performance   of principal component analysis (PCA) with kernel PCA, exploring various evaluation metrics, and testing multiple unsupervised algorithms for clustering and anomaly detection.

## Random Search Algorithim projects.
- [Ant_Colony_Optimization_ACO_Algorithm_For_TSP](https://github.com/ahmedalkadi/Ant_Colony_Optimization_ACO_Algorithm_For_TSP):
  Ant Colony Optimization (ACO) is a metaheuristic algorithm inspired by the foraging behavior of ants. Introduced by Marco Dorigo in the early 1990s, ACO has become a popular method for solving combinatorial optimization   problems.ACO simulates the behavior of ants searching for food to find optimal solutions in a given problem space. The algorithm is particularly effective in scenarios where finding the best path or solution involves      navigating through a large number of possible combinations.
- [Genetic_Algorithm_For_TSP_and_Knapsack](https://github.com/ahmedalkadi/Genetic_Algorithm_For_TSP_and_Knapsack):
  A Genetic Algorithm (GA) is an optimization technique inspired by natural selection. It starts with a population of possible solutions, evaluates their fitness, and selects the best individuals for reproduction.           Offspring are created through crossover and mutation, introducing variation. The process repeats over generations, evolving better solutions until an optimal or satisfactory solution is found.
  This algorithm is used to solve the following Problems:
  Traveling Salesman Problem (TSP), is a well-known combinatorial optimization problem. The objective is to find the shortest possible route that visits each city exactly once and returns to the origin city. Given a         list of cities and the distances between each pair of cities, the task is to determine the optimal order in which to visit the cities to minimize the total travel distance.
  Knapsack Problem, is another classic optimization problem. Given a set of items, each with a weight and a value, the objective is to determine the number of each item to include in a collection so that the total           weight is less than or equal to a given limit and the total value is as large as possible.

## Quantum Machine Learning Algorithms Projects.
- [Quantum Machine Learning: Implementing the K-Means Algorithm](https://github.com/ahmedalkadi/Kmeans_Implementaion_Quantum_Machine_Learning):
  Quantum Machine Learning (QML) is an emerging field that leverages quantum computing to enhance traditional machine learning algorithms. The K-Means algorithm, a popular clustering method, can benefit from the unique      capabilities of quantum computing, potentially offering improvements in speed and accuracy for large and complex datasets.
  The K-Means algorithm is a method used to partition a dataset into K distinct, non-overlapping subsets (clusters). The goal is to minimize the variance within each cluster. The algorithm follows these steps:
  Initialization: Select K initial centroids randomly.
  Assignment: Assign each data point to the nearest centroid, forming K clusters.
  Update: Recalculate the centroids as the mean of all points assigned to each cluster.
  Repeat: Repeat the assignment and update steps until convergence (i.e., centroids no longer change).
- [Optimization-with-Hyperopt-in-Quantum-Machine-learning](https://github.com/ahmedalkadi/Optimization-with-Hyperopt-in-Quantum-Machine-learning):
  Hyperopt is a powerful Python library for hyperparameter optimization, particularly popular in the machine learning and data science communities. It offers an efficient and flexible framework for automatically tuning      the hyperparameters of machine learning models, aiming to find the best configuration for a given optimization objective.

## Optimizers From Scratch Implementation Projects.
- [Implementing_Adagrad_RMSProp_Adam_Optimizers_From_Scratch](https://github.com/ahmedalkadi/Implementing_Adagrad_RMSProp_Adam_Optimizers_From_Scratch):
  This project involves developing a Python program to implement accelerated gradient descent methods with adaptive learning rates, specifically Adagrad, RMSProp, and Adam, for linear regression of a set of data             points. These algorithms aim to optimize the learning process by dynamically adjusting the learning rate based on the gradients of the loss function, leading to faster convergence and improved performance.

## Models Architecture From Scratch Implementation Projects.
- [MobileNet-V1-Model Implementation](https://github.com/ahmedalkadi/MobileNet-V1-Model-Implementation_From_Scratch):
  This project implements the MobileNetV1 model using PyTorch, a lightweight convolutional neural network architecture designed for mobile and embedded devices. Then to train it on the CIFAR-10 dataset, which consists of    60,000 images across 10 classes.

## Implementing Naive Bayes from Scratch for IMDB Fake / Real Review Classification
- [Implementing_Naive_Bayes_From_Scratch](https://github.com/ahmedalkadi/Implementing_Naive_Bayes_From_Scratch):
  Bayes Theorem is named after the English mathematician Thomas Bayes, who made significant contributions to decision theory, a field of mathematics that involves probabilities. Bayes Theorem is widely used in machine       learning as a simple and effective way to predict classes with precision and accuracy. The Bayesian method of calculating conditional probabilities is particularly useful in classification tasks. This project focuses on   implementing the Naive Bayes classification algorithm from scratch to classify IMDB reviews as fake or real. Specifically, we will implement the Multinomial Naive Bayes classifier, which is well-suited for text            classification tasks where the features are word frequencies or counts.

## Data Visualization and Webpages Scrapping.
- [Olympics-History-Dashboard_data_visualisation](https://github.com/ahmedalkadi/Olympics-History-Dashboard_data_visualisation):
  This project aims to explore the history of the Olympics and provide dynamic insights about the games and sports over time through an interactive dashboard. Leveraging Plotly, the dashboard offers visual representations   of Olympic data, including trends, medal counts, and athlete demographics. Additionally, the project utilizes machine learning models to make predictions for individuals seeking to participate in certain games based on    their body features, using the Olympics dataset.
- [Ikea_Sofas_Web_Scarpping_And_Data_Visualization](https://github.com/ahmedalkadi/Ikea_Sofas_Web_Scarpping_And_Data_Visualization):
  Web Scraping and Data Acquisition: IKEA Website Project Overview This project aims to collect and analyze data from the IKEA website. By extracting detailed information about IKEA's products, prices, and facilities, we    seek to gain valuable insights into market trends and customer needs. The data gathered will be utilized to inform business strategies and improve market understanding.
  The objectives are to Extract product information, prices, and facility details from the IKEA website. Analyze the collected data to uncover trends and insights. Visualize the findings using interactive dashboards.
  
  
