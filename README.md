# Movies-ETL


The code for this challenge uploads all necessary data, cleans up the data in each dataframe, merges the cleaned data into movies database and a ratings database, and finally loads the databases to pgAdmin. 
As more data is being uploaded, the code should continue to clean and load the data. Some hiccups that could occur during this process are: the amount of null values in columns can change- this would make previous columns with more than 90% null still excluded even though they have important data, the format of the data can change in a way that is not accounted for in the clean up, and data can get mixed in a different column. 
