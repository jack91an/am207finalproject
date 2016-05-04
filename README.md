#### Final Project for AM207 - Harvard University Spring 2016 

### Tittle:
NOW I SEE YOU: Sensor Based Single User Activity Recognition 


### Team Members: 
- Xiaowen Chang (xiaowenchang@g.harvard.edu)
- Siv Lu (blu@g.harvard.edu)
- Jack Qian (fqian@g.harvard.edu)
- Yuhan Tang (tang01@g.harvard.edu)

### Project Scope:

Activity recognition, which identifies the activity (eg. cooking, sleeping, reading) that a user performs from a series of observations, is an active research area. It has many real-life applications ranging from healthcare to intelligent environments. In our project, to simplify the problem, we used sensor based single user data with multiple sensored placed in three different houses. Each participate recorded their activities in a series of over 20 days. We experimented with different ways of data representation and lengthes of timeslices in data when building and testing different models. We used Naive Bayes, First Order HMM, and Second Order HMM. We tested and reported on Precision, Recall, F-measure and Accuracy. We found Second Order HMM with Change-point data representation gives best result. 


### File Organization:

- "code": contains ipython notebooks of all the code for data cleaning and model building.
- "data": contains activites data and sensor data. 
- "report": contains files for report using LaTeX
- "submission": deliverable for course (poster and report)
