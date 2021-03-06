# Analyzing Thanksgiving Dinner in the U.S.
•To discover patterns and habits according to particular demographics such as gender, income and location.

# Installation
•Clone this repo to your computer.  
•OPTIONAL: the original dataset can be found [here.](https://github.com/fivethirtyeight/data/tree/master/thanksgiving-2015)  
•Install the requirements using pip install -r requirements.txt.  
•Make sure you use Python 3.  
•You may want to install [Jupyter](http://jupyter.org/install) to run the ipynb.

# Usage
•Run the Jupyter Notebook "Turkey.Analysis.ipynb" either in Jupyter or the IDE of your choice.

# Tasks Performed
### •Filtered out rows from dataframe.
••Used pandas.Series.value_counts() method to display occurrence of each category in particular columns.  
••Used Boolean conditionals to select and filter.
### •Explored main dishes at Thanksgiving dinner.
••Used pandas.Series.value_counts() method to display occurrence of each category in particular columns.  
••Used Boolean conditionals to select and filter.
### •Explored dessert dishes at Thanksgiving dinner.
••Generated Boolean series to select null values in pies columns.  
••Used pandas.Series.value_counts() method to display whether or not pies were served and if so, what type of pies.
### •Converted Age column to integers.
••Created function to convert a string to an appropriate integer. 
### •Converted Income column to integers.
••Created function to convert a string to an appropriate integer income value.
### •Correalated travel distance & income.
••Filtered dataframe according to income; under and over 150000.  
••Used pandas.Series.value_counts() method to display distances people in these two categories are willing to travel.
### •Linking Friendsgiving & Age
••Called pivot_table() method to discover any significant patterns between age and people who spend Thanksgiving with friends.

# Observations
### •The analysis on demographics according to income reveals that people with higher income tend to have Thanksgiving at home compared to people with lower income. A possible explanation is that people with higher income usually have their own homes whereas people with lower income might be students who go home for Thanksgiving.
### •This dataset also reveals that younger people are more likely to attend Friendsgiving and meet up with friends on Thanksgiving night.
