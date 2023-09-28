

https://github.com/SnehashreeHazra/Python-for-Data-Science-IBM/assets/96810375/532eda92-69b1-4bbe-8338-66d3166c18b1


We can also write to files using the open function.
We will use Python’s open function to get a file object, to create a text file, we can
apply method write to write data to that file.
As a result, text will be written to the file.
We can create the file Example2".txt" as follows: We use the open function.
The first argument is the file path.
This is made up of the file name; if you have that file in your directory, it will be over
written, and the file directory.
We set the mode parameter to 'w' for writing.
Finally, we have the file object.
As before we use the "with" statement.
The code will run everything in the indent block, then close the file.
We create the file object File 1.
We use the open function.
This creates a file Example2.txt in your directory.
We use the method write to write data into the file.
The argument is the text we would like input into the file.
If we use the write method successively, each time it’s called, it will write to the file.
The first time it is called we will write: this is line A with a slash n to represent
a new line.
The second time we call the method it will write: this is line b.
Then it will close the file.
We can write each element in a list to a file.
As before we use a "with" command and the open function to create a file.
The list 'lines' has three elements consisting of text.
We use a “for loop” to read each element of the list lines and pass it to the variable
line.
The first iteration of the loop writes the first element of the list to the file example 2.
The second iteration writes the second element of the list, and so on.
At the end of the loop the file will be closed.
We can set the mode to appended using a lower case "a".
This will not create a new file, but just use the existing file.
If we call the method write, it will just write to the existing file, then add: this
is line C. Then close the file.
We can copy one file to a new file as follows: First, we read the file example 1 and interact
with it via the file object "read file“.
Then we create a new file example 3 and use the file object "write file" to interact with it.

The “for loop” takes a line from the file object read file and stores it in the file
example 3 using the file object write file.
The first iteration copies the first line.
The second iteration copies the second line till the end of the file is reached, then
both files are closed.
Check out the labs for more examples.

