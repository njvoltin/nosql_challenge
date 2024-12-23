This project analyzes UK Food Standards Agency data. The repository focuses on database setup, modifications, and analysis using MongoDB
and Python. The establishments.json was imported using mongoimport. The code for the setup and modification on the database can be
found in the nosql_setup_starter.ipynb file. It first adds a new establishment to the database. Then updates the BusinessID of the 
new establishment. Then, some of the fields need to be updated with appropriate datatypes so they can be analyzed in the second part. 
Finally, some unwanted data is removed from the database. 

The second part of this project is exploratory analysis using PyMongo and Pandas which can be found in the nosql_analysis_starter.ipynb.
This file explores 4 questions. 1) What establishments have a hygiene score of 20? 2) Which establishments in London have a
RatingValue greater than or equal to 4? 3) What are the top 5 establishments near the restaurant that we added in the first part?
Top 5 means that they have the lowest hygiene score and a Rating Value of 5. 4) How many establishments in each LocalAuthorityName
have a hygiene score of zero?
