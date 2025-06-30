# SpameBase

***About the Dataset:***
The Spambase dataset is a collection of email messages categorized as spam or not spam. It's a popular benchmark dataset used for machine learning tasks like spam filtering and text classification.

***Here's a breakdown of the dataset:***
	Source: UCI Machine Learning Repository (https://archive.ics.uci.edu/dataset/94/spambase)
	Task: Classification (spam vs. not spam)
	Number of Instances: 4601
	Number of Features: 57 (all numerical)

***Data Description:***
	Each email is represented by 57 features. These features are numerical values that capture various characteristics of the email, such as word frequency counts, presence of certain characters or symbols, and message length.
	The specific details of these features are not provided in the dataset but are meant to represent characteristics that might distinguish spam emails from legitimate emails.
	The target variable indicates whether the email is spam (1) or not spam (0).

***Significance:*** 
	The Spambase dataset serves as a valuable tool for developing and evaluating spam filters, introducing text classification concepts, and demonstrating the importance of feature selection.
	 Its accessibility makes it a great resource for those getting started with machine learning on text data.


***Block Diagram:*** 

![image](https://github.com/user-attachments/assets/077a5147-4593-45ff-b2d9-364450c45f80)

      
***Splitting Dataset:***
•	 Divided the dataset into training (80%) and testing (20%) sets.
•	 Chose the split ratio based on best practices in machine learning.

***Navies Bayes Algorithm Implementation:***
	Train Naive Bayes: Train a Naive Bayes classifier on the preprocessed Spambase data. This involves calculating the probability of each feature value occurring in both spam and non-spam emails.
	Classify New Emails: For a new email (represented by its features), calculate the probability of it being spam and not spam using the trained Naive Bayes model.
	Predict Spam: Classify the new email as spam if the probability of being spam is higher than a predefined threshold (e.g., 0.5). Otherwise, classify it as not spam

***Performance Evaluation:***
	 Metrics:
   Evaluated model performance for each k value using standard metrics:
•	Accuracy
•	Precision
•	Recall
•	F1score
 
 ***Conclusion***
   Naive Bayes offers a good balance between simplicity, efficiency, and performance for spam classification with the Spambase dataset. However, it's crucial to be aware of its limitations, particularly the feature independence assumption. For more complex tasks or datasets with strong feature dependencies, other algorithms like Support Vector Machines (SVM) or Random Forests might be better suited.

***Results:***

 ![image](https://github.com/user-attachments/assets/2c505941-a644-4a74-bbfd-1b2c7535605a)
     
