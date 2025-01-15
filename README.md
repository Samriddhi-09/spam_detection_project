# spam_detection_project
Created an innovative approach for classifying SMS spam using Natural Language Processing (NLP), resulting in significant improvements to data accuracy during the AICTE internship on AI: Transformative Learning with TechSaksham.

Technology Used:
Python
Scikit-learn
Pandas
NumPy
Streamlit

Features
Data cleaning and preprocessing : First we drop unneecessary columns and duplicate values and then assign 0 to non spam messages and 1 to spam messages. The data was later converted into lowercase and tokenised.
Exploratory Data Analysis: Characters, words and sentences were separated and then mean,std,quartiles, correlation were calculated. Further we plot pycharts, barcharts, heatmaps and word clouds
Model building and selection : Multiple classifier models were used including different types of NaiveBayes. Accuracy and precision for each model was calculated. 
Web Deployment: Streamlit was used to deploy the model created.
