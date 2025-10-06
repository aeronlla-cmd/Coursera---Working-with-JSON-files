# Coursera - Working with JSON files
Coursera module activity requirement
For this activity, I used pandas to utilize dataframes in manipulating the data in the CSV file. 


Cell 11 - Grouping all records of Red and White wines from the CSV file

I used a for loop to go through all the rows of the dataframe and if the data in the cell under variety column says 'Red Wine' it'll be appended to the initially empty list red_wine[] and if it says 'White wine' it'll be appended to the initially empty list white_wine[].

At the end, I converted each list into a dataframe for better presentation when queried. 


Cell 13 - Grouping all records of wines with scores of 95 and above. 

I also used a for loop to go through each row of the dataframe and put a conditional on the rating column that if it's above 95, it should be added to the initially empty list of high_score_wines[]. Finally converted it as well to a dataframe for better presentation when queried.


Cell 14 - Grouping all records of wines that comes from France

Another for loop is used here to go through each row of data and used a conditional for the Region column that if it contains the word 'France', it should be appended to the initially empty list france_wines[]. Also turned it into a dataframe for better presentation when queried.


Cell 15 - turning each result into a json file

using the to_json function, we converted each dataframe into a json file that's oriented as records, which turns each line of result as a single JSON object, with line breaks for each object. 

