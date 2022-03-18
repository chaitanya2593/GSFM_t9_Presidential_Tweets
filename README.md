# GSFM_t9_Presidential_Tweets
The repo is created to store the GSFM_t9_Presidential_Tweets project files


### Dependencies
1. Twitter Raw data -> nayibbukele_user_tweets.xlsx
2. Bitcoin data -> ../BTCUSDT.csv


### CheckpoinFiles  Files:

This data files are created as the checkpoint files in case the kernal breaks or notebook is revisited later points. 
- tweeter_data_cleaned_v1.csv -> Twitter data after translating the Spanish text to English 
- tweeter_data_cleaned_v2.csv -> Twitter data after performing the sentiment analysis using the vedar and text blob/spacy
- tweets_under-analysis.csv -> Extracted the initial set of tweets with sentiment analysis for manual sentiment check.
- filtered_tweets_df.csv -> This is the resulted tweets data after applying all the filters on the initial tweets 
- abnormal_evenst_60_60.csv -> abnormal events for the filtered tweets observed from an hour before and after the event 
- abnormal_evenst_2-60.csv -> abnormal events for the filtered tweets observed from 2 minutes before and 15 minutes after the event


### Packages to install:
Please refer to the requirement.txt for all the packages required for the analys. Please open the command prompt and run the command 'pip install -r requirements.txt'


Note: All the required outputs are displayed and not required to re run all the code to review teh results.
