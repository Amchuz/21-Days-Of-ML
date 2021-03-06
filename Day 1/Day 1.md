### Topics
  
- What is ML ?
- Applications of ML
- Types of ML
- Scikit-Learn
- Scikit-Learn Installation

### What is ML ?
  
It is a type of **Artificial Intelligence** that allows software applications to learn from data and become more accurate in predicting outcomes without **human interventions**.
  
eg : Whether a piece of fruit in a picture is a orange or an apple, spotting people crossing the road in front of a self-driving car and taking actions accordingly, whether an email is a spam or not, or to generate captions for a YouTube video.
  
**What’s requires to create good machine learning systems ?**
1) Data Preparation capabilities
2) Algorithms — basic and advanced
3) Automation and iterative processes
4) Scalability
5) Ensemble Modeling
  
### Applications of ML
  
- Image Recognition
- Self Driving Cars
- Product Recommendation
- Stock Market Prediction
- Online Fraud Detection
- Spam Email Detection
- Online Customer Service
  
### Types of ML
  
- Supervised Learning
- Unsupervised Learning
- Reinforcement Learning
- Semi-supervised Learning
  
#### 1) Supervised Learning
  
<img src=https://github.com/Amchuz/21-Days-Of-ML/blob/master/Day%201/Supervised%20Learning>
  
  
Supervised learning algorithms are trained using labelled data, in which input and its desired output are known. Supervised learning is commonly used in applications where historical data predicts future events. For example, it can anticipate when credit card transactions are likely to be got cancelled or which insurance customer is going to file a claim.
  
**Important supervised algorithms**
  
- K-nearest neighbors
- Linear regression
- Support vector machines
- Logistic regression
- Decision trees
- Random forests
  
#### 2) Unsupervised Learning
  
<img src=https://github.com/Amchuz/21-Days-Of-ML/blob/master/Day%201/Unsupervised%20Learning.jpeg>
  
Unsupervised learning is used against data that are unclassified or unlabeled. The system does not know the “right answer”. The goal is to explore the data and find some structure within. Unsupervised learning works well on transactional data. Unsupervised Learning Algorithms allow users to perform more complex processing tasks compared to supervised learning.
  
**Important unsupervised algorithms**

- Clustering: k-means, hierarchical cluster analysis
- Association rule learning: Eclat
- Visualization and dimensionality reduction: kernel PCA, t-distributed, PC
  
#### 3) Reinforcement Learning
  
<img src=https://github.com/Amchuz/21-Days-Of-ML/blob/master/Day%201/Reinforcement%20Learning.jpeg width="400" height="400">
  
Reinforcement learning is often used for robotics, gaming and navigation. This algorithm achieves the highest accuracy through trial and error or repeatedly running the algorithm to achieve good accuracy.
  
**This type of learning algorithms has three primary components:**
  
- The agent (the learner or decision-maker)
- The environment (everything the agent interacts with)
- Actions (what the agent can do)
  
**Important reinforcement algorithms**
  
- Monte Carlo Methods
- Temporal Difference Methods
- Direct policy search
  
#### 4) Semi-Supervised Learning
  
<img src=https://github.com/Amchuz/21-Days-Of-ML/blob/master/Day%201/Semi-supervised%20learning.jpeg width="350" height="300">
 
The main objective of introducing this learning algorithm is to overcome the problems faced by the supervised or unsupervised learning. In supervised learning, the data should be labeled which is a costly process and in unsupervised the application spectrum is limited. To overcome these disadvantages Semi-Supervised learning was introduced. In this both labeled and unlabeled data is present. When this type of data is used then it shows considerable improvement in learning accuracy.
  
**Important semisupervised alorithms**
  
- Generative Models
- Low-density separation
- Graph-based Methods
- Heuristic approaches
  
### Scikit-Learn
  
- Open source library which is licensed under **BSD**
- Built on Numpy, scipy & Matplotlib
- Many tuning parameters
- Documentation & Support
  
Scikit-learn is probably the most useful library for machine learning in Python. The sklearn library contains a lot of efficient tools for machine learning and statistical modeling including classification, regression, clustering, and dimensionality reduction. Sklearn is used to build machine learning models. It should not be used for reading the data, manipulating, and summarizing it. There are better libraries for that (e.g. NumPy, Pandas, etc.)
  
**Components of scikit-learn**
  
Scikit-learn comes loaded with a lot of features. Here are a few of them to help you understand the spread:
  
- Supervised learning algorithms: Think of any supervised machine learning algorithm you might have heard about and there is a very high chance that it is part of scikit-learn. Starting from Generalized linear models (e.g Linear Regression), Support Vector Machines (SVM), Decision Trees to Bayesian methods — all of them are part of scikit-learn toolbox.
- Cross-validation: There are various methods to check the accuracy of supervised models on unseen data using sklearn.
- Unsupervised learning algorithms: There is a large spread of machine learning algorithms in the offering — starting from clustering, factor analysis, principal component analysis to unsupervised neural networks.
- Various toy datasets: Various academic datasets (e.g. IRIS dataset, Boston House prices dataset)
- Feature extraction: Scikit-learn for extracting features from images and text (e.g. Bag of words)
  
<img src=https://github.com/Amchuz/21-Days-Of-ML/blob/master/Day%201/Scikit-learn.jpeg width="500" height="450">
  
### Scikit-Learn Installation
  
**Using pip**\
$ pip install -U scikit-learn \
**In anaconda using conda run** \
conda install -c anaconda scikit-learn 
