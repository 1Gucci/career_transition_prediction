## [Project 2: Predictive Analytics For Career Excellence]
### Introduction
![image](https://github.com/anbui-da/career_transition_prediction/assets/58675665/256e8659-1a93-4652-9163-5931ba5e25b8)
This project was implemented as an output of Data Capstone Project course of my college, which I had a chance to work with a client to pursue this real-world project. The course is not about counseling professionals on how to get a job or retain they current position, but how to look at their career and treat it like a problem to be solved or an opportunity to seek at work or business to come up with a sustainable solution. This project developed a machine learning model to predict the number of years before a professional makes a career transition.

### Methodology
1. Utilized web scraping techniques to collect data from LinkedIn profiles, yielding a dataset of 3000 profiles spanning various industries and career levels.
2. Preprocessed and cleaned the data, handling missing values.
3. Engineered features such as "unique job titles", "unique degree types", and target variable which is "number of years" it took for a particular profile to transit to a higher job level in order to enhance the predictive power of the model.
4. Implemented a linear regression model, achieving a Mean absolute error (MAE) of 2.44, which means on average, the model's predictions deviate by about 2.44 years from the actual career transition times.

### Results
1. The model showed that Work experience, Education level, With Honors, Volunteer_YN, Edu_Tech, Edu_NonTech are the most significant predictors. 
2. The model was tested on a separate validation set and demonstrated of 28.4% of accuracy in predicting career transition times within a 1-year-margin.
3. The model predicts 3.5 years on average that a profile make a transition to a higher job level.

   **Model report of all predictors**   
![image](https://github.com/1Gucci/An_Bui_portfolio/assets/58675665/1bcbe654-365c-485d-b485-4b3bd2981eba)

### Limitations and improvements
**Limitations**
1. Model Performance: While we have identified a set of variables related to transition years, there is a possibility that other important variables are missing.
2. Data Bias: LinkedIn profiles are not representative of the entire population, and there may be biases in terms of demographics, industry representation, or geographic location.
3. Data Preprocessing: The dataset required significant preprocessing and manipulation of categorical variables, that are complex and time-consuming.

**Improvements**
1. Explore more sophisticated machine learning algorithm or ensemble methods to handle complex feature interactions.
2. Validate the model's performance on external datasets to assess its generalizability.
