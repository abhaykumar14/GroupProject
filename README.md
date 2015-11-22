

Explanation on Script

Step:1 Create the working directory in R. (Line 1 in script)

Step 2: Place all the necessary data file in the working directory (Copy and paste from the downloaded location manually – This is not a part of script).

Step 3: Include required library (Line 2 -3)

Step 4: Read all the necessary files in R. (Line 4-11)

Step 5: create a new data ’a’ that combines the ‘Subject’ (test subject of experiment), ‘Activity’ (the activity performed like Walking, Laying etc. and readings from subject_test.txt (ste), y_test.txt (tel) and x_test.txt (te) respectfully. This creates final test data (Line 12)

Step 6: create a new data ’b’ that combines the ‘Subject’ (train subject of experiment), ‘Activity’ (the activity performed like Walking, Laying etc. and readings from subject_train.txt (str), y_train.txt (trl) and x_train.txt (tr) respectfully. This creates final train data (Line 13)

Step 7: This merges test (a) and train (b) and creates ‘mrge’ data. (Line 14)

Step 8: creates a (z) data which calculates the mean (z1) and standard deviation (z2) all 561 domain variable. Then it names the rows of this data as ‘mean’ and ‘stdev’. (Line 15-18).

Step 9: This step adds the activity description from to each activity (like for Activity = 1 = WALKING….. ) in the form of new variable. This new variable is then assigned to Activity variable. Line 19-20) 

Step 10: Column names changed for domain variables (measured variables). (Line 21)

Step 11: The average for each subject and corresponding activity is calculated and furnished as new and final data (summary).

Step 12: The final data is written out as ‘summary.txt’

