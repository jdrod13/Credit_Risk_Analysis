# Credit_Risk_Analysis

Machine learning models to predict credit risk using Python's imbalanced-learn and scikit-learn libraries

**On this project,  we focus on working with machine learning models to analyze credit risk to provide an efficient and more reliable loan experience process. Using these models, We took an adequate amount of time to identify promising loans candidates, which could help different financial institutions to decrease their loan default rates.**

Resources

•	Software used:

•	Python

•	Jupyter Notebook

•	NumPy, sci-kit-learn, and imbalanced-learn libraries

•	Logistic Regression and Random Forest models


•	Ensemble and resampling techniques


### Results


<img width="530" alt="Machine 1" src="https://user-images.githubusercontent.com/81654454/133009381-cc487185-47d5-482d-a30d-8bbc0dd9c3c7.PNG">




<img width="622" alt="Machine 2" src="https://user-images.githubusercontent.com/81654454/133009405-88a445be-a61e-440e-b673-5435d5f8702d.PNG">




<img width="637" alt="Machine 3" src="https://user-images.githubusercontent.com/81654454/133009431-5146db49-0cfa-44cc-8fc0-48dc2355f2a3.PNG">




<img width="625" alt="Machine 4" src="https://user-images.githubusercontent.com/81654454/133009464-8bcc7866-792a-4446-98de-1b428bac13ac.PNG">





<img width="651" alt="Machine 5 Oversampling" src="https://user-images.githubusercontent.com/81654454/133009485-27b0cce7-18a1-4135-8479-675678bd4068.PNG">






<img width="552" alt="Machine 5 undersampling" src="https://user-images.githubusercontent.com/81654454/133009496-861a5af7-5a6a-4eaf-b4ec-52c45b82f28a.PNG">




<img width="626" alt="Machine 6" src="https://user-images.githubusercontent.com/81654454/133009527-8dde08c4-f6df-4075-bb35-d6021b575ae6.PNG">




<img width="626" alt="Machine 7" src="https://user-images.githubusercontent.com/81654454/133009554-1ee16d92-a30b-4d76-80a4-baa9cfbd6e46.PNG">




## Results and conclusion
    
    
    
  
  **In the financial industry, it's crucial to find the value of potential qualifying candidates for analyzing risk and default rates on loan candidates. All banks want to highlight all high-risk individuals for their potential approvals**
 
 
 **In terms of risk, The highest one was the Easy Ensemble AdaBoost Classifier with 7% precision which is still considered pretty low for finding these high-risk individuals that riskier to be approved. Therefore, this means that out of all the customers marked as high-risk, 7% were high-risk.**
  
  

**It is essential to keep in mind that this analysis's precision is not telling us much information to compare the algorithms, so we should look at sensitivity. The model with the highest sensitivity was the easy ensemble AdaBoost classifier (91% for high-risk and 94% for low-risk individuals), meaning that 91% of the time, all the high-risk individuals are marked as high-risk individuals. The other two with high recall followed by this model were the Random Forest Classifier (67%) and SMOTEENN Resample (70%).**
