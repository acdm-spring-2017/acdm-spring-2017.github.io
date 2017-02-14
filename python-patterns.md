# Common Patterns in Python

- lists
- loops
- functions
- text processing
- math
- opening, editing files
- matplotlib (more on this later)

# Practice problem: Display a line plot of average number of words in Gothic novel titles by year

This doesn't sound terribly hard, but how do you start? I usually make a list of the things I will need to do to get from point A to point B.

1. Load a csv into python (as list? numpy array? dataframe?)
2. Tokenize titles so that each separate word can be counted once
3. Convert token lists to integer lists, each entry representing the number of words
4. Calculate an average title length for each year
5. End up with two lists or columns, one for avg count, one for year
6. Plot using matplotlib

## First question: load csv as what?

DataFrame make it easy to load, and easy to do other tasks

## Problem: DataFrame can't hold a token list

Need to go straight from title column to word count column without going back to DataFrame


# Give it a Try!

This is probably going to be difficult for most of you. Try it out and look at my solution if you get stuck. Below are some tutorials or documentation on specific aspects of this problem. A link to my solution is at the very bottom.

# Resources

## Load a csv or excel to a DataFrame

http://pandas.pydata.org/pandas-docs/stable/io.html#io-read-csv-table

http://pandas.pydata.org/pandas-docs/stable/io.html#io-excel-reader

## Convert DataFrame column to a list

http://stackoverflow.com/questions/22341271/get-list-from-pandas-dataframe-column

## Apply operations to grouped cells in a DataFrame

http://chrisalbon.com/python/pandas_apply_operations_to_groups.html

http://pandas.pydata.org/pandas-docs/stable/generated/pandas.Series.to_frame.html

## Plot of DataFrame columns

http://pandas.pydata.org/pandas-docs/version/0.15.0/visualization.html

# My Solution (one of many)

https://github.com/acdm-spring-2017/frank-gothic-data/blob/master/Title-Length-by-Year.ipynb
