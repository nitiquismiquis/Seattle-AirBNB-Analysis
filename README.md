# CRISPM-Process---Seattle-AirBNB-Data

<h2>Motivation</h2>

Overview of the AirBNB Dataset - Applying ML Linear Regression models to explore tha Seattle AirBNB database to understand what features can optimize host´s profits minimizing the investment.
   
<h3>Main questions explored and summary of results</h3>
   
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

<h2>Libraries Used</h2>
   - numpy
   - pandas
   - matplotlib.pyplot
   - seaborn
   - sklearn (LinearRegression, train_test_split, r2_score, mean_squared_error)
   
<h2>Files</h2>
   - Seattle AirBNB Analysis.ipynb
   - calendar.csv
   - listings.csv
   - calendar.csv
   - README.md
