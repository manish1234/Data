# Data
This repository for simple Machine Learning Prototype and learning

1. How to implement cold start strategy in recommendation engine If there are not popular musics in the database how to recommend them.
-  Implement item based collaborative filtering rather than user until we have good number of data.
-  Sometimes we don't recommend until we don't have sufficient data. Make search is more better and advanced.

2. How to implement large layer in model.
 	- Define the goal for the process
	- Data cleaning
	- Removing null value
	- Visualising data and observing the pattern
	- Removing outlier if needed
	- Imputing value for data normalising.
	- 

3. How to develop a recommendation engine based on content and context.
     		- Cleaning the data
		- Calculating the missing value
		- Flattening the data if   if required
		- Find the similarity of the data based on different statistical measure for e.g. cosine similarity

4.   How many reiterations have you done to generally train the model to give better results.
	-  I don't have specific number but I try to avoid the overfitting the data in the model 

5.   How to incorporate user feedback in the training cycle and where its stored
	- It depends on business problem we are trying to solve.
	- If there is no human intervention we can feed incorrect data to model and result in produce inaccurate results.
	- Implicit feedback and explicit feedback
	- What we want to achieve from feedback for e.g. YouTube's recommendation system is designed to increase people's watch time.
	-  Trying to improve accuracy might have undesirable effect and overfitting of data.
	- The type of machine learning model: classification, recommender system, etc.
	- Feedback data is stored in database where it is easy to query and filter the useful and non-useful data. We should also make sure we have user-consent before storing user-specific information for the feedback.
			- 

6. Long tail in recommendation system
	- Data Augmentation
	- Starting line of selection
	- Data Preprocessing
	-
		
7. How to deal with sparse matrix
	- Reduce the dimensionality for e.g. PCA 
	- Feature Hashing
	- Remove unimportant feature from dataset.
	- entropy-weighted k means - Use feature which is not affected by sparse data set.
	- using t-SNE  Distributed Stochastic Neighbor Embedding
