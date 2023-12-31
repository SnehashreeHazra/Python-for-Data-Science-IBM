

https://github.com/SnehashreeHazra/Python-for-Data-Science-IBM/assets/96810375/0390260e-7744-406a-99e3-c4d3b81eac97



Let’s cover dictionaries in Python. Dictionaries are a type of collection in Python.
If you recall, a list has integer indexes. These are like addresses.
A list also has elements. A dictionary has keys and values.
The key is analogous to the index, they are like addresses but they don’t have to be
integers. They are usually characters; the values are
similar to the elements in a list and contain information.
To create a dictionary, we use curly brackets. The keys are the first elements; they must
be immutable and unique. Each key is followed by a value separated
by a colon. The values can be immutable, mutable and duplicates.
Each key and value pair is separated by a comma.
Consider the following example of a dictionary, the album title is the key and the value is
the release data. We can use yellow to highlight the keys and
leave the values in white. It is helpful to use the table to visualize
a dictionary, where the first column represents the keys and the second column represents
the values. We can add a few more examples to the dictionary.
We can also assign the dictionary to a variable. The key is used to look up the value. We use
square brackets; the argument is the key. This outputs the value.
Using the key of "Back in Black," this returns the value of 1980.
The key "The Dark Side of the Moon," gives us the value of 1973.
Using the Key "The Bodyguard," gives us the value 1992, and so on.
We can add a new entry to the dictionary as follows.
This will add the value 2007 with the new key called "Graduation."
We can delete an entry as follows. This gets rid of the key "Thriller" and its
value. We can verify if an element is in the dictionary
using the in command as follows. The command checks the keys. If they are in
the dictionary, they return a true. If we try the same command with a key that
is not in the dictionary, we get a false. If we try with another key that is not in
the dictionary, we get a false. In order to see all the keys in a dictionary,
we can use the method keys to get the keys. The output is a list like object with all
the keys. In the same way, we can obtain the values
using the method values. Check out the labs for more examples and info
on dictionaries.
