# Data_Wrangling
Data wrangling can be quite intense sometimes depending on the quality of dataset one wants to analyze and the number of the datasets to be analyzed. Doing so with the datasets given was not different.

#### The Process
I started the data wrangling processs by first gathering the different datasets from different sources and after that, I started assessing them. The dataframes I was analyzing were, df, df_1 and df_2.
There are two main ways of assessing the dataframes that is visually and programmatically. Visual assessment is when one goes through a dataframe to see if there are any quality or tidiness issues. 
Through visual analysis in the first dataframe,df, several observations were made. The name column had names of dogs  that are nouns but there were other names like very, a to name a few that were not names for the dogs. They needed to be replaced with NaN to show that those names were not given.
Other observations made were that the doggo, floofer, pupper and puppo were supposed to be in the same column. 
From the first dataframe, these were the quality issues that were noted:
 1. The first column, tweet_id is in integer form, instead of being a string.
 2. The timestamp is in object form, it should be changed to timestamp for.
 3. The source column is incomplete because only the truncated data can be viewed.
 4. Extracting the source name from the source column.
 5. Change all the names in the names column that start with a lowercase letter to NaN
 
 The second dataframe, df_1, had the following quality issues:
 1.The tweet_id is in interger form whereas it's supposed to be a string.
 2. Change the titles p1, p1_conf, p1_dog, p2, p2_conf,p2_dog, p3,p3_conf and p3_dog to be meaningful titles.
 3. The names in column p1 are separated by a hyphen and should be capitalized.
 4. The names in column p2 are separated by a hyphen and should be capitalized.
 5. The names in column p3 are separated by a hyphen and should be capitalized.
 
 The third dataframe,df_2, had the following quality issues:
  1. id column is an integer its supposed to be a string.
  2. Id column to be renamed tweet_id.
  
  The following were the tidiness issues identified:
 1. Add a column called rates and compute the rates by taking numumerical value/denominator value.
 2. in_reply_status_id, in_reply_retweet_id, retweet_status_id, retweeted_status_user_id, retweeted_status_timestamp columns should be dropped.
 3.  doggo, floofer, pupper and puppo are is a one variable and should be in one column.

I started by working on the quality issues first using the define, code and test procedure and then after working on each dataframe individually rectified the tidiness issues. 
Thereafter, analyzing and visualization was done.
