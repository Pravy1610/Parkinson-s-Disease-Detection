# Parkinson-s-Disease-Detection
Project Outline:   
Parkinson's Disease is a brain neurological disorder. This disease affects movement, causes tremors and stiffness, and is a progressive illness of the central nervous system. It comprises five stages and affects more than 1 million people in India each year. There is currently no treatment for this chronic condition. It causes the body to shake, the hands to shake, and it makes the body stiff. At this advanced level, there is still no viable treatment or cure. Only when treatment is initiated at the earliest stage of the disease is it effective. These could potentially save a life in addition to lowering the cost of the illness. The majority of ways can identify Parkinson's disease after it has advanced, which results in basal ganglia, which regulates the movement of the body with a small quantity of dopamine, losing about 60% of their dopamine.    

Project Structure:   
The goal of the Parkinson's Disease Detection project is to build a machine-learning model capable of accurately diagnosing Parkinson's disease based on certain features derived from biomedical data. 
1. Data Collection and Preparation --> Worked on the dataset(https://www.kaggle.com/datasets/debasisdotcom/parkinson-disease-detection) from Kaggle that contains biomedical features and corresponding labels that indicates the presence or absence of Parkinson's disease. 0 stands for the absence of Parkinson's Disease in the particular individual and 1 stands for the presence of Parkinson's Disease.    
2. Data Cleaning --> Preprocess the data by handling missing values and scaling features.   
3. Data Visualization --> Creating visual representation of the distributions, correlations, and connections between the features and the target variable. Performed data exploration to gain insights into the dataset.     
4. Build the model --> Used the Python libraries scikit-learn, numpy, pandas, and machine learning algorithms to build the Classifier model. The models used here are XG Boost, Decision Tree Classifier, Logistic Regression, KNN Algorithm and Random Forest Classifier. Split the dataset into training and testing sets.   
5. Train the model --> The selected models are trained using the training data.
6. Model Evaluation --> Evaluating the model's performance on the testing data using metrics like accuracy, precision, recall and  F1-score. Analyzing the confusion matrix to understand the model's performance in classifying Parkinson's disease cases.
7. Conclusion --> Achieved 95% accuracy on this problem using XgBoost and Random Forest Classifier

