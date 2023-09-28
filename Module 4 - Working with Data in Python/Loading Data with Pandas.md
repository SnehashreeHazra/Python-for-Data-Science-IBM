

https://github.com/SnehashreeHazra/Python-for-Data-Science-IBM/assets/96810375/68130b67-7eeb-47ee-9470-661dd686c7db


Dependencies or libraries are pre-written code to help solve problems.
In this video, we will introduce pandas–a popular library for data analysis.
We can import the library or a dependency like pandas using the following command.
We start with the import command followed by the name of the library.
We now have access to a large number of pre-built classes and functions.
This assumes the library is installed. In our lab environment, all the necessary libraries
are installed. Let’s say we would like to load a csv file
using the pandas built-in function “read csv.”
A csv is a typical file type used to store data.
We simply type the word pandas, then a dot and the name of the function with all the
inputs. Typing pandas all the time may get tedious.
We can use the "as" statement to shorten the name of the library; in this case we use the
standard abbreviation pd. Now we type pd and a dot followed by the name
of the function we would like to use, in this case, read_csv.
We are not limited to the abbreviation pd. In this case, we use the term, banana.
We will stick with pd for the rest of this video. Let’s examine this code more in-depth.
One way pandas allows you to work with data is with a data frame.
Let's go over the process to go from a csv file to a data frame.
This variable stores the path of the csv. It is used as an argument to the read_csv function.
The result is stored to the variable df; this is short for “dataframe."
Now that we have the data in a dataframe, we can work with it.
We can use the method head to examine the first 5 rows of a dataframe.
The process for loading an excel file is similar. We use the path of the excel file.
The function reads excel. The result is a dataframe.
A dataframe is comprised of rows and columns. We can create a data frame out of a dictionary.
The keys correspond to the column labels. The values are lists corresponding to the
rows. We then cast the dictionary to a dataframe
using the function DataFrame. We can see the direct correspondence between
the table. The keys correspond to the table headers.
The values are lists corresponding to the rows.
We can create a new dataframe consisting of one column.
We just put the dataframe name, in this case "df" and the name of the column header enclosed
in double brackets. The result is a new dataframe comprised of
the original column. You can do the same thing for multiple columns.
We just put the dataframe name, in this case "df" and the name of the multiple column headers
enclosed in double brackets. The result is a new dataframe comprised of
the specified columns. One way to access unique elements is the ix
method. You can access the 1st row and first column
as follows. You can access the 2nd row and first column
as follows. You can access the 1st row, 3rd column as follows.
You can access the 2nd row, 3rd column as follows. When you use the name of the column as well,
you can access the 1st row of the column named 'Artist’ as follows.
Similarly, you can access the 2nd row of the column named ‘Artist.’
You can access the 1st row of the column named 'Released’ as follows.
Finally, you can access the 2nd row of the column named 'Released.’
You can also slice dataframes and assign the values to a new dataframe.
We assign the first two rows and the first three columns to the variable z.
The result is a dataframe comprised of the selected rows and columns.
You can also slice dataframes and assign the values to a new dataframe using the column
names. The code assigns the first three rows and
all columns in-between to the columns named 'Artist’ and 'Released.’
The result is a new dataframe z with the corresponding values.
