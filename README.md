# CRISPM-Process---Seattle-AirBNB-Data
Overview of the AirBNB Dataset - Applying ML Linear Regression models to answer Main 3 Questions

Libraries Used:
   - numpy
   - pandas
   - matplotlib.pyplot
   - seaborn
   - sklearn (LinearRegression, train_test_split, r2_score, mean_squared_error)
   
Motivation:
   - Familiarize myself with the identification of the questions that a data-scientist should be asking her/himself.
   - Familiarize myself with the use of ML models and was to explore the obtained solutions.
 

Files:
   - Jupyter notebook: '0. Exercise Seattle AirBNB'

Main questions explored and summary of results:
   - Question 1 - What are the top 5 features which have more impact in the price? The top 5 features that have an impact is related to:
    * Property_type
    * host_has_profile_pic (very interesting)
    * neighbourhood_group_cleansed
    * zipcode
    * room_type

   - Question 2 - What impact have the ratings over the price? 
    * It has an impact of 2.415173 dollars per point

   - Question 3 - What are the top 5 features which customers value when rating their stay that depend only on the host? Top 5 features:
    * host_acceptance_rate - negatively.
    * review_scores_cleanliness - positively
    * review_scores_communication - positevely
    * review_scores_checkin - positevely
    * host_is_superhost_t - positevely
