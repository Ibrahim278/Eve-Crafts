# Eve-Crafts

### Project Overview

In this project, we will be integrating artificial intelligence into our platform to enhance user experience and engagement. The process will involve developing AI-powered features to personalize recommendations, improve search functionality, and streamline user interactions. Let's dive into the exciting world of AI and revolutionize the way craft enthusiasts discover and interact with handmade creations.

### Scope

The scope of this project involved creating a Machine Learning model which recommends handmade products to consumers based on attributes such as product description and user reviews. The model could then be integrated into a mobile or web application using a backend infrastructure. 

### Objectives

•	Gaining knowledge of AI and NLP
•	Understanding the concept of Natural Language Processing
•	Collected relevant datasets
•	Performing data processing and cleaning
•	Developing a model to recommend handmade products
•	Fine Tuning the model
•	Finding a conclusion

### Tools Used

The model was developed using the Python programming language with the Jupyter Notebook environment. The main purpose of using Jupyter Notebook instead of an IDE such as PyCharm or Sublime Text is because Jupyter Notebook allows you to integrate markdown text along with Python code within one file. The Python libraries involved in the development process include Pandas, NumPy, Scikit-Learn, Seaborn, and Matplotlib.

### Development Process

The development process was broken down into 4 steps:
1.	Data Collection and Pre-Processing: There were two datasets used to pre-process the data required to develop the model. The data was first cleaned and analyzed before feature extraction techniques were used to separate the required data to train and test the model.
2.	Model Exploration: Once the dataset was cleaned and finalized, I split the data into training set and testing set. I then experimented the model using different techniques such as Demographic Filtering, Content-Based Filtering and Collaborative Filtering.
3.	Model Refinement: Once I had completed experimenting on the model, I refined the model using Linear Regressor and Random Forest Regressor.
4.	Testing and Evaluation: After refining the model, I tested and evaluated the model before coming to a conclusion.




### Key Decisions Made

The key decisions I had to make during the process of developing the model included:
•	Finding the most predictive features
•	Removing highly correlated attributes
•	Using mutual information to identify the right predictors
•	Extracting the necessary features such as “average sales per year”

### Conclusion

At the end of this project, we created a machine learning model that predicts what handmade products a user is most likely recommend. The model can be integrated into a backend infrastructure for further use.

Number of reviews were shown to be the most important indicator of success for shops as suggested by the high mutual information score and supported by the permutation importance test for our highly accurate random forest regression model. The correlation matrix revealed the surprising insight that the number of items a seller has available appears to be have a moderate positive correlation with number of reviews their shop received.
