# final.py
Load the data from reddit_comments.csv file Download reddit_comments.csv fileOpen this document with ReadSpeaker docReaderinto a dataframe, selecting only the columns: comment body, author, subreddit, comment creation timestamp, score, id, permalink, link_id, distinguished. (5 points)

Add a new column 'date' to your dataframe that stores the comment creation date in the format YYYY-MM-DD (Hint: Use comment creation timestamp to retrieve this information). Print each unique comment creation date and its corresponding number of comments in your dataframe.  (10 points)
Find the number of rows with at least one NaN value in your dataframe. (3 points)
Conduct a sentiment analysis on the body of each comment in your dataframe and insert a new column that stores the resulting sentiment scores. (7 Points)
Find the author who submitted the most number of comments in your dataframe. Find the author with the longest comment in your dataframe. Print the longest comment text. (8 points)
Find the three most frequent subreddits occurring in your dataframe. (3 points)
Add a column to your dataframe containing the number of words in the comment body. Across your dataframe, calculate the average and maximum number of words in comments (7 points).
Drop rows with comments containing fewer than 5 words from your dataframe. (3 points)
What is the percentage of remaining comments containing the word 'please'? (4 points)
Question 2: Analyzing the Restaurants Dataset of an Online Food Ordering App (50 points)
Load the data from data.csv file Download data.csv fileOpen this document with ReadSpeaker docReaderinto a dataframe with restaurant ID as the dataframe’s index. Skip the first 50 rows of the file when loading your data (5 points)

Sort the dataframe first by ‘Votes’ and next by ‘Price range’ in a single step, i.e., entries with equal ‘Votes’ values should be sorted based on their ‘Price range’ values. Print the first 15 entries of this sorted dataframe. (5 points)

Replace all instances of ‘Indian Rupees(Rs.)’ with ‘INR (Rs.)’ throughout your dataframe. (2 points)

Create a Pandas series that stores the number of restaurants registered with this app in each city. Find the city with the highest number of restaurants registered. (5 Points)

Add a new column, “Price Grade” which will have the following values based on the 'Price range' of the restaurant (7 points):

If the range is 1: Cheap
If the range is 2 or 3: Average
If the range is 4: Expensive
Print the restaurants with rating less than 2. Next, drop the entries of those restaurants. (3 Points)

Find the number of restaurants where the average cost of two is less than 500 and aggregate rating is greater than 3.5. (5 Points)

Drop all columns except ‘Restaurant Name’, ‘City’, ‘Price range’, and ‘Votes’ from your dataframe. Add the following entries to this dataframe: (8 points)

‘Amano’, ‘New York’, 12, 387‘
The Coppola Cafe’, ‘New Brunswick’, 9, 183

Convert all column names to UPPERCASE format. Save the updated dataframe in an Excel file called ‘output.xlsx’ in a sheet called ‘Restaurants’. Ignore writing the index column in this file. Attach this file in your submission. (10 points)
