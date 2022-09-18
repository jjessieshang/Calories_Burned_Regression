# Launchpad_technical_challenge

# What is machine learning?
Fundamentally, machine learning involves building mathematical models to help understand data. The "learning" process arises when we give these models *tunable parameters* that can be adapted to observed data; the program can be considered to be "learning" from the data. Once these models have been fit to previously seen data, they can be used to predict and understand aspects of newly observed data. Alike the human brain, the more training algorithms get, the likelihood of better performance increases.

# Categories of Machine Learning
Machine learning can be organized into two categories: 

* Supervised learning involves somehow modeling the relationship between measured features of data and some label associated with the data; once this model is determined, it can be used to apply labels to new, unknown data. This is further subdivided into classification tasks and regression tasks: in classification, the labels are discrete categories, while in regression, the labels are continuous quantities.

* Unsupervised Learning involves modeling the features of a dataset without reference to any label, and is often described as "letting the dataset speak for itself." These models include tasks such as clustering and dimensionality reduction. A territory of unsupervised learning that peaks my interest is that of neural networks - computing systems inspired by the biological neural networks that constitute animal brains. Some examples include GPT-3 which produces human-like text and DALL-E which generates digital images from natural language descriptions.

# A Simple Machine Learning Application: 
I have created a statistical machine learning system which predicts how many calories are burned by a person during exercise. This model is a useful tool for calorie counting purposes; the model informs you the amount of exercise necessary for a specific individual to reach their fitness goals!

What happens when you exercise?
When exercising, glucose molecules in the body are converted into energy to fuel metabolic activities. The number of calories burned is the amount of energy the body uses during a specific activity, which varies for each individual. **This machine learning model takes parameters including: gender, height, weight, body temperature, age, average heart rate, and duration of exercise to predict the number of calories burned during exercise.**

An Analysis of Linear Regression with Machine Learning:
Advantages| Disadvantages
------------- | -------------
Easy to implement, interpret and efficient to train  | Accuracy suffers when impossible, unlikely, and incomplete values have been inputted as training data
Allows for extrapolation beyond a specific data set | Linear regression performs poorly when there are non-linear relationships
