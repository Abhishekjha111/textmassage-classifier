# textmassage-classifier
The increasing volume of unsolicited bulk sms (also known as spam) has generated a need
for reliable anti-spam filters. Machine learning techniques now days used to automatically
filter the spam sms in a very successful rate.We review some of the most popular machine
learning methods (Random Forest Classifier) and of their applicability to the problem of
spam sms classification. Descriptions of the algorithms are presented, and the comparison
of their performance is presented.
Data Gathering
Data is recieved from a group of people of their smart phones and messages were extracted
with an application name “ApowerManager”.
Data Cleaning
Contrary to what most data science courses would have you believe, not every dataset is a
perfectly curated group of observations with no missing values or anomalies (looking at you
mtcars and iris datasets). Real-world data is messy which means we need to clean and wran-
gle it into an acceptable format before we can even start the analysis. Data cleaning is an
un-glamorous, but necessary part of most actual data science problems.
Data cleaning or cleansing is the process of detecting and correcting (or removing) corrupt
or inaccurate records from a record set, table, or database and refers to identifying incom-
plete, incorrect, inaccurate or irrelevant parts of the data and then replacing, modifying, or
deleting the dirty or coarse data.
The goal of this project is to predict classifications of messages. From the results we learn
that the dataset has 9871 rows and 6 columns.We also identify whether the features are nu-
meric or categorical variables. These are all usefull information.
Missing data
Dealing with missing data/value is one of the most tricky but common parts of data clean-
ing. While many models can live with other problems of the data, most models don’t accept
missing data.
Irregular data (Outliers)
Outliers are data that is distinctively different from other observations. They could be real
outliers or mistakes.
Unnecessary data
After all the hard work done for missing data and outliers, let’s look at unnecessary data,
which is more straightforward.
