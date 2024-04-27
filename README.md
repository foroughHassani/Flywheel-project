This repository contains the following files:

1. Flywheel_Assignment: Jupyter Notebook containing project code.
2. Data: The original dataset data 


The question is :
According to the data, how many searches does the keyword with rank 1 receive for each search engine?

Summary of Findings:
To address this question, I opted for Random Forest, a robust and versatile modeling technique, to establish the relationship between the dependent variable (number of searches) and the independent features (date, 'keyword_rank,' and 'search_engine').
I used a random forest with 30 estimators and a maximum tree depth of 10. The model exhibits an accuracy of 96% in forecasting the test dataset with a Mean Absolute Error = 0.14.
