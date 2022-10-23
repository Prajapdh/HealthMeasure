# HealthMeasure
A simple ML-powered tool to measure a person's wellness. The wellness index computed from model can be stored and comapred when a patient get his another dose. We tried to include several factors so this takes many things into account just like a physician would do. Patients can reduce the number of visits to doctors and rely on the score of this model when they are prescribed new drug.

# Inspiration
While BMI is a popular tool for measuring health around the world, it is also inaccurate due to inaccurate measurements of body fat content and muscle mass, bone density, overall body composition, and racial and sex differences was not considered.

# What it does
Takes number of inputs from the user and then computes HMI that could be used by patient to compare his wellbeing when he takes any prescribed drug. 

# How we built it
We used Jupyter Notebook to create a linear regression model to measure the impact of each health factor and SQL server to store patients' data

# Challenges we ran into
Determining the best factors for measuring health and their impact

# Accomplishments that we're proud of
The model can correctly measure a person’s health with root mean square error of 142 out of 1000, which was relatively useful

# What we learned
We had learned how to download dataset using kaggle api, different preprocessing steps on data, training model and then comparing the scores of different models to select the best model. The model selected can be tuned as per our preferences to give more accurate results. We also learned about different aws services and used the SQL database on aws server to store the data we get from the python model.

# What's next for HealthMeasure
Currently, we have a model that is not that accurate, we need to tune hyperparameters of decision tree regressor or gradient boosting algorithm to get more promising results. We can expand this futher and create an index for other diseses as well. Thus, we aim to expand this model to support more health conditions and gain a better understanding of people's well-being.
