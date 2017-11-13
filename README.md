Let's Practice Using Pandas
---------------------------



Objective
-------------
Hotel X wants to know how customers feel about their stay at the hotel

Use the comments in the hotel reviews file (data.json file) to do a simple sentiment analysis

Instructions
------------
    1. Install the sentiment analysis package afinn. You can find out more about it at https://pypi.python.org/pypi/afinn/0.1

    2. Create a DataFrame that includes in its rows some data from each review.

    Each row should include:

    •	review author's screen name
    •	author location
    •	review ID
    •	review date
    •	review title
    •	each rating provided by the reviewer
    •	an afinn sentiment score for the reviewer's written comment.

    3. Save the dataframe to a shelve database.

    4. Calculate descriptive statistics for the sentiment score to summarize the reviewers' feelings about their
    experiences with this hotel.

    5. Plot sentiment score distributions (ie Histogram)
    
Extra Points:
------------
If you were providing these results to the hotel, and they asked you what their sentiment scores should be compared to.
what would you tell them?
