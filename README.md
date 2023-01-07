CENG 464 Text Mining Term Project 

**Objective** 

The goal of the term project is to gain practical experience with various text mining tasks. Tasks that the project covers are cleaning, preprocessing data, feature extraction, data visualization, model classification with machine learning algorithms, topic modeling, text summarization, training a sentiment model.  

**Overview** 

You are expected to perform the tasks that are listed below, choose proper algorithms and techniques for the tasks, and report your findings in detail with your basis. The goal is to see if you apply the course objectives in hands-on activity.  

**Guidelines** 

The project report is just as important as your code. Please pay attention while reporting your findings and your reasons.  

The term project accounts for 50% of your grade and is associated with implementation (20%), report (20%), and presentation (10%).  

**Project Implementation (20%)** 

- You are expected to implement the tasks in the project in Python, write clean and readable code.  
- Please be sure that the code you send is run properly. 
- You can use any IDE you want and you can use necessary libraries that we used in our classes.  
- Use comments to explain your code.  

**Project Report (20%)** 

- Identification and Significance of Problem: What is the aim of this project and what values that it adds to you in the text mining field? What is the purpose of your experiments? What are you testing? 
- Methodology: What are the methods that you perform to tasks in this project? How are you measuring performance?  
- Implementation: What IDE that you used? What are the libraries that you used and for which part you used these? 
- Experimental Results: What are your results? Answer the questions in the project description.  
- Conclusion: Discuss the results and your findings from experiments. 

**Project Presentation (10%)** 

The goal of the project presentation is to give you experience with public speaking and to give us all the opportunity to learn from what you did. 

You are expected to tell your work step by step. Your aim, your reasons for choosing your algorithms and methods, your experimental results and your conclusions. 

**General Rules** 

- Cheating and plagiarism are not allowed. If any cheating has been detected, it will be graded as 0.  
- Send your projects as CENG464\_StudentID.zip that contains your code, your summarized txt files (Part D, neg\_summarized.txt and pos\_summarized.txt) and your report.  
- Please add your name, surname and student id into your project report. 

**Project Description** 

**Part A** 

**A.1.** There are two different folders in the dataset named ‘neg’ and ‘pos’. Read the data files and combine them to use as a whole. Examine the data in detail and clean it while applying 4 different preprocessing methods which are proper for the data.  

**Part B.** 

**B.1.**Choose 4 different general features fit for the data and extract these features from the cleaned dataset.  

**B.2.** Create Bag of Words and Term Frequency-Inverse Document Frequency models for the data that you cleaned in step A, compare 10 most frequently occurring words and choose one of the models which you think is more suitable to use as a feature for that dataset.  

**B.3.** With the model that you choose in step B.2, determine the 50 most frequently occurring words and visualize them with Word Clouds. 

**B.4.** Apply 4 machine learning algorithms to develop text classifiers into your data using features you extracted in part B. Apply k-means clustering, linear regression, one classification method and one tree based method that you think is more suitable for the data. Calculate the performance measures: confusion matrix, precision, F1 score, receiver operating characteristic (ROC) curve, root mean square error (RMSE). (**Note:** Decide the k by yourselves while trying a specific range). 

**Part C** 

3. Apply topic modeling to data that you cleaned in part A. Use Latent Dirichlet Allocation (LDA) algorithm. Decide the correct number of topics. Then, compare its results with K- Means algorithm. 

**Part D** 

4. Apply the text summarization method using TextRank algorithm for both ‘neg’ and ‘pos’ files in the dataset. Save the summarized texts as two different new .txt files (neg\_summarized.txt, pos\_summarized.txt). 

**Part E** 

5. Train a sentiment model that models the dataset as positive and negative sentences. Using the cleaned data in part A extract a specific feature and apply a machine learning algorithm. Divide data into test and train sets and use test sets to predict the sentiment of data that is not seen before. Calculate the accuracy of your model. 

**REPORT** 

**A.1.** Explain why you prefer these specific preprocessing methods in detail, which feature of the data made you think to apply these processes?  

**B.1.** Explain why you choose these features in detail, why you think that these features would be proper for the data? 

**B.2.** Explain the comparison of these two models in detail, the one that you choose and why you think that it is more suitable for the data? 

**B.3.** Add the output image of the Word Clouds method to your report.  

**B.4.** Explain why you choose these classification and tree based models in detail and compare 4 machine learning algorithms that you used in terms of performance measures. **C.** Discuss the proper number of topics and k value that you found in step B.4. Also discuss the relation between them.  **E.** Explain why you prefer that specific feature and machine learning algorithm in detail. Which feature of the data made you think that the feature and algorithm are more suitable? Also discuss the accuracy of your model. 
