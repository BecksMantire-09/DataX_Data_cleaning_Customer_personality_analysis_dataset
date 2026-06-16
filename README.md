# DataX_Data_cleaning_Customer_personality_analysis_dataset
I downloaded the customer personality dataset titled 'marketing_campaign.csv' on kaggle.
When i inspected this dataset, all the columns where in one row but seperated with \t. so i created a new dataframe with sep = 't' so the different columns appear on their seperate columns
I also noticed the income column had 24 missing values. So I imputed by the median for similar education levels.
I then noticed the date datatype was an object instead of datetime so i adjusted it
Finally I converted the column headers to lower case to make it more clean.
