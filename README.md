# Crowdfunding-ETL

**Purpose**

Independent Funding wants you and Britta to continue work on the crowdfunding ETL project and SQL data analysis. They have a new dataset with information about the backers who have pledged to live projects. They want you to use Python, Pandas, Jupyter Notebooks, and SQL to extract the data, transform the data, create an ERD and Table Schema, and then load the data and perform a SQL Analysis on it. 

**Results**

Uisng Pandas we were able to import the csv file and then extract the column headers from that. Then we iterated through each row of the dataframe creating a list where each item was a string that had its own dictionary. Then we converted to a json file that we could iterate through and then from that turned that into a dataframe with new headers taken from the list dict_values. From there we separated the name column into first_name and last_name and rearranged the dataframe and exported that to a new csv file. 

From that backers.csv file we created a new schema and five new tables. We imported the csv file and were able to perform new queries on it to get the number of backer_counts and the remaining_goal_amounts to send to the contacts and backers for each live campaign. 
