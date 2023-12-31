

https://github.com/SnehashreeHazra/Python-for-Data-Science-IBM/assets/96810375/d7f2a073-2227-4e0a-af86-aaf39b0e3e1d


When we have a dataframe we can work with the data and save the results in other formats.
Consider the stack of 13 blocks of different colors.
We can see there are three unique colors.
Let’s say you would like to find out how many unique elements are in a column of a
dataframe.
This may be much more difficult because instead of 13 elements you may have millions.
pandas has the method unique to determine the unique elements in a column of a dataframe.
Let’s say we would like to determine the unique year of the albums in the data set.
We enter the name of the dataframe, then enter the name of the column ‘Released’ within
brackets.
Then we apply the method unique.
The result is all of the unique elements in the column ‘Released.’
Let's say we would like to create a new database consisting of songs from the 1980's and after.
We can look at the column ‘Released’ for songs made after 1979, then select the corresponding
columns.
We can accomplish this within one line of code in Pandas, but let’s break up the steps.
We can use the inequality operators for the entire dataframe in pandas.
The result is a series of Boolean values.
For our case, we simply specify the column ‘Released’ and the inequality for the
albums after 1979.
The result is a series of Boolean values.
The result is true when the condition is true and false otherwise.
We can select the specified columns in one line; we simply use the dataframe’s names,
and in square brackets we place the previously mentioned inequality and assign it to the
variable df1.
We now have a new dataframe, where each album was released after 1979.
We can save the new dataframe using the method to_csv.
The argument is the name of the csv file.
Make sure you include a dot csv extension.
There are other functions to save the dataframe in other formats.
