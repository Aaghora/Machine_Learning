# Machine_Learning
Study Material

1.	What does one mean by the term "machine learning"?
	-> ML is a sub branch of Artificial Intelligence, which gives a computer the tendency to learn from the training datasets using various algorithms, 
  	and helps in further intelligent prediction of the result.

2.	Can you think of 4 distinct types of issues where it shines?
	-> a) Health sector- detection of various health issues like Diabetes, cancer, covid etc.
	b) Defence sector- Detection of mines, intercepting missiles, image recognition
	c) Industry sector- prediction analysis, speech recognition, Economy prediction
	d) Service sector- chat bots, automatic token generator, voice dialling, etc.

3.	What is a labelled training set, and how does it work?
	-> Labelled training sets are features of data that are provided to the algorithm in order to train the algorithm, which further helps is predicting 
	the results when new data is feed.First the data is divided into two parts training and testing then the training data is fed to the suitable 
	algorithm, after training the data, the testing data is fed in order to check the accuracy of the algorithm developed.  

4	.What are the two most important tasks that are supervised?
	-> Classification and Regression are the two major tasks performed supervised learning.
	Classification refers to the problems which have binary output likes Yes No, True false., whereas Regression refers to those set of data which 
	expect some sort of continuous outcomes like height, weight, Rank,etc. 

5.	Can you think of four examples of unsupervised tasks?
	-> Organise computing data (google location based request), 
	Market segmentation (sending ads to a particular group),
 	Grouping/clustering goods (Arranging goods on mall selves), 
	Social Network analysis (Connecting people on the basis of school, friends etc.). 
	Astronomical data analysis (Group far off galaxy, planets and satellite).

6.	State the machine learning model that would be best to make a robot walk through various unfamiliar terrains?
	-> Reinforced learning is best suited for the robot walking on through the unfamiliar terrains.

7.	Which algorithm will you use to divide your customers into different groups?
	-> The best algorithm to divide customers into different groups is unsupervised learning. It will create the clusters and assign accordingly.

8.	Will you consider the problem of spam detection to be a supervised or unsupervised learning problem?
	-> Spam detection is a supervised learning problem since group is decided as spam or not spam. In this case we try to keep False Positive (FP) 
	as low as possible. Precession should be our focused matrix score. Precission =TP/(TP+FP)

9.	What's the difference between a model parameter and a hyperparameter in a learning algorithm?
  -> Model parameters determines how a model will predict at an instance when a new data set is passed. Whereas hyper parameters helps in learn algorithm and tune           according to find the best fitted values of the parameters (it is not for the model).  

10.	What are the criteria that model-based learning algorithms look for? What is the most popular method they use to achieve success? What method do they use to make predictions?
 -> Model-based algorithm looks for an optimal values of parameters in the cost function, so as to minimize the cost function.
  The minimization of loss function parameters are generally used for this purpose.
  Once the parameters like slope and intercepts are known this values are used to generalise the equation and further predict the values by putting the values of         variables. 

11.	Can you name four of the most important Machine Learning challenges?
  -> The major challenges we generally faced with the machine learning are
    a)	Cleaning of data – handling missing values, handling Zeros and outliers etc.
    b)	Overfitting of the models
    c)	Under fitting models
    d)	Insufficient data and non-representative data

12.	What happens if the model performs well on the training data but fails to generalize the results to new situations? Can you think of three different options?
 -> If the model performs well on training data but fails to generalize the results to new situations that is an over fitting situation, this can be resolved by passing more data, removing the outliers or noises from the data,  and implement a more suitable model and tune it.

13.	What exactly is a test set, and why would you need one?
  -> Test set are the fraction of dataset we keep aside to check the accuracy of our model developed. It is needed in order to know how good or bad our model is             generalised.

14.	What is a validation set's purpose?
 -> Validation Set is used to compare between different training models.
  
15.	What could go wrong if you use the test set to tune hyper parameters?
 -> If we use test data for hyper tuning, the model developed maybe over fitted and biased, and also it might not behave properly because of improper generalisation.

16.	What is cross-validation and why would you prefer it to a validation set? 
  -> Cross Validation is a tool to compare models without needing a separate validation set. It is preferred over validation set because a fraction of data is stored for   the validation purpose from the  training set to create a validation set, as having more data is valuable regardless its size.

