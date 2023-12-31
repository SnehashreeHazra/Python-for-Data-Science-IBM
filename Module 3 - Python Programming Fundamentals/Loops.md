In this video we will cover Loops, in particular “for loops” and “while loops.”
We will use many visual examples in this video. See the labs for examples with data.
Before we talk about loops, let’s go over the range function.
The range function outputs an ordered sequence as a list “i”.
If the input is a positive integer, the output is a sequence; the sequence contains the same
number of elements as the input, but starts at zero.
For example, if the input is 3 the output is the sequence 0,1,2.
If the range function has two inputs where the first input is larger than the second
input, the output is a sequence that starts at the first input.
Then the sequence iterates up to, but not including the second number.
For the input 10 and 15, we get the following sequence. See the labs for more capabilities
of the range function. Please note: if you use Python 3, the range
function will not generate a list explicitly like in Python 2.
In this section, we will cover “for loops”. We will focus on lists, but many of the procedures
can be used on tuples. Loops perform a task over and over.
Consider the group of colored squares. Let's say we would like to replace each colored
square with a white square. Let's give each square a number to make things
a little easier and refer to all the group of squares as squares.
If we wanted to tell someone to replace square 0 with a white square, we would say, “=Replace
square 0 with a white square” or we can say, “For square 0 in squares, square 0=
white square.” Similarly, for the next square, we can say,
“For square 1 in squares, square 1 = white square.”
For the next square, we can say, “For square 2 in squares, square 2= white square.”
We repeat the process for each square. The only thing that changes is the index of
the square we are referring to. If we are going to perform a similar task
in Python, we cannot use actual squares. So let's use a list to represent the boxes.
Each element in the list is a string representing the color.
We want to change the name of the color in each element to white.
Each element in the list has the following index.
This is the syntax to perform a loop in Python. Notice the indent.
The range function generates a list. The code will simply repeat everything in
the indent 5 times. If you were to change the value to 6, it would
do it 6 times, however, the value of “i” is incremented by one each time.
In this segment we change the i-th element of the list to the string white.
The value of “i” is set to zero. Each iteration of the loop starts at the beginning
of the indent. We then run everything in the indent.
The first element in the list is set to white. We then go to the start of the indent.
We progress down each line. When we reach the line to change the value
of the list, we set the value of index 1 to white.
The value of “i” increases by one. We repeat the process for index 2.
The process continues for the next index until we have reached the final element.
We can also iterate through a list or tuple directly in Python, we do not even need to
use indexes. Here is the list squares. Each iteration of
the list we pass one element of the list squares to the variable square.
Let's display the value of the variable square on this section.
For the first iteration, the value of square is red.
We then start the second iteration. For the second iteration, the value of square is yellow.
We then start the third iteration. For the final iteration, the value of square is green.
A useful function for iterating data is enumerate. It can be used to obtain the index and the
element in the list. Let's use the box analogy, with the numbers
representing the index of each square. This is the syntax to iterate through a list
to provide the index of each element. We use the list squares and use the names
of the colors to represent the colored squares. The argument of the function enumerate is
the list, in this case, squares. The variable "i" is the index, and the variable
square is the corresponding element in the list.
Let's use the left part of the screen to display the different values of the variable square,
and "i" for the various iterations of the loop. For the first iteration, the value of the
variable is red, corresponding to the zeroth index, and the value for “i” is zero.
For the second iteration, the value of the variable square is yellow and the value of
"i" corresponds to its index, i.e., 1. We repeat the process for the last index.
“While loops” are similar to “for loops”, but instead of executing a statement a set
number of times, a while loop will only run if a condition is met.
Let’s say we would like to copy all the orange squares from the list squares to the
list new squares, but we would like to stop if we encounter a non-orange square.
We don't know the value of the squares beforehand. We would simply continue the process while
the square is orange, or see if the square equals orange; if not, we would stop.
For the first example, we would check if the square was orange.
It satisfies the condition, so we would copy the square.
We repeat the process for the second square. The condition is met, so we copy the square.
In the next iteration, we encounter a purple square.
The condition is not met so we stop the process. This is essentially what a “while loop”
does. Let's use the figure on the left to represent
the code. We will use a list with the names of the color
to represent the different squares. We create an empty list of “New Squares.”
In reality, the list is of indeterminate size. We start the index at zero.
The “while” statement will repeatedly execute the statements within the indent until
the condition inside the bracket is false. We append the value of the first element of
the list squares to the list "New Squares." We increase the value of “i” by one.
We append the value of the second element of the list squares to the list "New Squares.“
We increment the value of “i”. Now the value in the array “Squares” is
purple. Therefore, the condition for the “while”
statement is false and we exit the loop. Check out the labs for more examples of loop,
many with real data.
