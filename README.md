# Students performance  prediction
This academic project is about using machine learning algorithms to predict whether or not a student would pass the final exam. 
The data set used is from UCI Machine Learning Repository.


# Introduction
Education is an important element of the society, every government and country in the world work so hard to improve this sector. With the corona-virus    outbreak that has disrupted life around the globe in 2020, the educational systems have been affected in many ways; studies show that student’s performance has decreased since then, which highlights the need to deal with this problem more seriously and try to find effective solutions, as well as the influencing factors.  


# Motivation
The educational systems need, at this specific time, innovative ways to improve quality of education to achieve the best results and decrease the failure rate. 
  
As students of the IT department who studied in the last month a little about machine learning, we know that in order for an institute to provide quality education to learners, deep analysis of previous records of the learners can play a vital role, and wanted to work on this challenging task. 


# Problematic
As already mentioned, with the help of the old students records, we can came up with a model that can let us help students improve their performance in exams by predicting the student success. So, it is obvious it's a problem of classification , and we will classify a student based on his given informations, and we will also use diffrent classifiers such as KNN or SVM classifier and compare between them. Many factors affect a student performance in exams like famiily problems or alcohol consumption, and by using our skills in machine learning we want to :

	    1) predict whether a student will pass his final exam or not.
	    2) came up with the best classifier that is more accurate and avoid 
	       overfitting and underfitting by using simple techniques.
	    3) know what the most factors affect a student performance.

So, teachers and parents will be able to intervene before students reach the exam stage and solve the problems.


# Dataset processing
Now before training our model we have to process our data :

1) We have to map each string to a numerical value so that it can be used for model training.
       
2) We have to perform feature scaling :

        Feature scaling is a method used to normalize the range of independent variables 
		or features of data. In data processing, it is also known as data normalization 
		and is generally performed during the data preprocessing step.
        
		This will allow our learning algorithms to converge very quickly. The operation requires 
		to take each column, let's say 'col', and replace it by :
        
  
# Dataset visualization  
After having our dataset processed, we move to the next step which is dataset visualization; so that patterns, trends and correlations that might not otherwise be detected can be now exposed.

This discipline will give us some insights into our data and help us understand the dataset by placing it in a visual context using python libraries such as: matplotlib and seaborn.

   There are so many ways to visualize a dataset. In this project we chose to: 
   
      #1- Plot distribution histograms so that we can see the number of samples that occur in 
      each specific category.
      E.g.  Internet accessibility at home distribution shows that our dataset consists of 
      more than 300 students with home internet accessibility, 
      while there are about 50 students who have no access to the internet at home.
      
      #2- Plot “Boxplots” to see to see how the students status is distributed according to each variable.
      
      #3- Plot the correlation output that should list all the features and their correlations 
      to the target variable.
      So that we have an idea about the most impactful elements on the students status. 



# Model evaluation (metrics)
Before starting training our classifers let us define the metrics that we will use to compare between our three classifiers :

    1) Confusion matrix
    2) F1 score
    3) The roc curve  
    4) ROC score 


# Logistic regression
Refer google or chatGPT to learn working of algorithms

# KNN
Refer google or chatGPT to learn working of algorithms
 
# SVM
Refer google or chatGPT to learn working of algorithms


# Conclusion

Improving the education system is a big problem, as an engineering student we can help achieve this goal by using technologies and study resources like machine learning materials, to come up with an innovative solution to help the student in need, especially students who live in difficult conditions. conditions (demographic, social and educational issues).
In this project, we came up with the idea of creating a model that predicts the status of students based on different functionalities.
 Our main challenges were to define the best classification algorithm and identify the most influential factors for the academic status of students to provide them with a summary or valedictorian of the best conditions for students to achieve high academic status and avoid failures.
  For this project entitled “Prediction of student performance ” ”, we used several classification methods such as logistic regression, KNN and SVM and we evaluate this model using different metrics like f1 score, roc curve and the confusion matrix and finally we got a winner with SVM with a precision of 80%compared to other algorithm .


