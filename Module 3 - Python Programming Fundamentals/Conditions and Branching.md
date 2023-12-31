In this video you will learn about Conditions and Branching.
Comparison operations compare some value or operand, then, based on some condition they
produce a Boolean.
Let's say we assign "a" value of “a” to 6.
We can use the equality operator denoted with two equal signs to determine if two values
are equal, in this case, if seven is equal to 6.
In this case, as six is not equal to 7, the result is false.
If we performed an equality test for the value 6, the two values would be equal.
As a result, we would get a true.
Consider the following equality comparison operator.
If the value of the left operand, in this case, the variable “i” is greater than
the value of the right operand, in this case, 5, the condition becomes true, or else we
get a false.
Let's display some values for "i" on the left.
Let’s see the values greater than 5 in green and the rest in red.
If we set "i" equal to 6, we see that 6 is larger than 5, and as a result, we get a true.
We can also apply the same operations to floats.
If we modify the operator as follows, if the left operand “i” is greater than or equal
to the value of the right operand, in this case, 5, then the condition becomes true.
In this case, we include the value of 5 in the number line and the color changes to green
accordingly.
If we set the value of "i" equal to 5, the operand will produce a true.
If we set the value of “i” to 2, we would get a false because 2 is less than 5.
We can change the inequality, if the value of the left operand, in this case, “i”
is less than the value of right operand, in this case, 6, then condition becomes true.
Again, we can represent this with a colored number line.
The areas where the inequality is true are marked in green and red where the inequality
is false.
If the value for "i" is set to 2, the result is a true, as 2 is less than 6.
The inequality test uses an explanation mark preceding the equal sign, if two operands
are not equal, then the condition becomes true.
We can use a number line.
When the condition is true the corresponding numbers are marked in green and red for where
the condition is false.
If we set “I” equal to 2, the operator is true as 2 is not equal to 6.
We compare strings as well.
Comparing “AC/DC” and “Michael Jackson” using the equality test, we get a false, as
the strings are not the same.
Using the inequality test, we get a true, as the strings are different.
See the labs for more examples.
Branching allows us to run different statements for a different input.
It's helpful to think of an “if statement” as a locked room:
If the statement is true, you can enter the room, and your program can run some predefined
task.
If the statement is false, your program will skip the task.
For example, consider the blue rectangle representing an ACDC concert.
If the individual is 18 or older, they can enter the ACDC concert.
If they are under the age of 18, they cannot enter the concert.
Individual proceeds to the concert, their age is 17, therefore they are not granted
access to the concert, and they must move on.
If the individual is 19, the condition is true, they can enter the concert; then they
can move on.
This is the syntax of the if statement from our previous example.
We have the if statement. We have the expression that can be true or
false, the brackets are not necessary.
We have a colon.
Within an indent, we have the expression that is run if the condition is true.
The statements after the if statement will run regardless if the condition is true or
false.
For the case where the age is 17, we set the value of the variable age to 17.
We check the if statement; the statement is false, therefore the program will not execute
the statement to print "you will enter."
In this case, it will just print “move on.”
For the case where the age is 19, we set the value of the variable age to 19.
We check the if statement.
The statement is true, therefore, the program will execute the statement to print “you
will enter.”
Then it will just print “move on.”
The “else statement” will run a different block of code, if the same condition is false.
Let’s use the ACDC concert analogy again; if the user is 17, they cannot go to the ACDC
concert, but they can go to the Meat Loaf concert represented by the purple square.
If the individual is 19, the condition is true.
They can enter the ACDC concert, then they can move on as before.
The syntax of the else statement is similar.
We simply append the statement else.
We then add the expression we would like to execute with an indent.
For the case where the age is 17, we set the value of the variable age to 17.
We check the if statement.
The statement is false, therefore, we progress to the else statement.
We run the statement in the indent.
This corresponds to the individual attending the Meat Loaf concert.
The program will then continue running.
For the case where the age is 19, we set the value of the variable age to 19.
We check the if statement.
The statement is true, therefore, the program will execute the statement to print “you
will enter.”
The program skips the expressions in the else statement and continues to run the rest of
the expressions.
The elif statement, short for “else if,” allows us to check additional conditions,
if the proceeding condition is false.
If the condition is true, the alternate expressions will be run.
Consider the concert example, if the individual is 18, they will go to the Pink Floyd concert,
instead of attending the ACDC or Meat Loaf concert.
The person of 18 years of age enters the area as they are not over 19 years of age.
They cannot see ACDC, but as they are 18 years, they attend Pink Floyd.
After seeing Pink Floyd, they move on.
The syntax of the “elseif statement” is similar.
We simply add the statement elseif with the condition.
We then add the expression we would like to execute if the statement is true, with an
indent.
Let's illustrate the code on the left.
An 18-year-old enters.
They are not older than 18 years of age, therefore the condition is false, so the condition of
the else if statement is checked.
The condition is true, so then we would print “go see Pink Floyd.“
Then we would move on, as before.
If the variable age was 17, the statement “go see Meat Loaf” would print.
Similarly, if the age was greater than 18, the statement “you can enter” would print.
Check the labs for more examples.
Now let’s take a look at logic operators.
Logic operations take Boolean values and produce different Boolean values.
The first operation is the not operator.
If the input is true, the result is a false.
Similarly, if the input is false, the result is a true.
Let A and B represent Boolean variables.
The “or” operator takes in the two values, and produces a new Boolean value.
We can use this table to represent the different values.
The first column represents the possible values of A.
The second column represents the possible values of B.
The final column represents the result of applying the "or" operation.
We see the "or" operator only produces a false if all the Boolean values are false.
The following lines of code will print out: “This album was made in the 70's or 90's”
if the variable album year does not fall in the 80s.
Let's see what happens when we set the album year to 1990.
The colored number line is green when the condition is true and red when the condition
is false.
In this case, the condition is true.
Examining the second condition, we see that 1990 is greater than 1989, so the condition
is also true.
We can verify by examining the corresponding second number line.
In the final number line, the green region indicates where the area is true.
This region corresponds to where at least one statement is true.
We see that 1990 falls in the area.
Therefore we execute the statement.
Let A and B represent Boolean variables the "and" operator takes in the two values,
and produces a new Boolean value.
We can use this table to represent the different values.
The first column represents the possible values of A.
The second column represents the possible values of B.
The final column represents the result of applying the "and" operation.
We see the "or" operator only produces a true if all the Boolean values are true.
The following lines of code will print out: “This album was made in the 80’s” if
the variable album year is between 1980 and 1989.
Let's see what happens when we set the album year to 1983.
As before, we can use the colored number line to examine where the condition is true.
In this case, 1983 is larger than 1980, so the condition is true.
Examining the second condition, we see that 1990 is greater than 1983 so this condition
is also true.
We can verify by examining the corresponding second number line.
In the final number line, the green region indicates where the area is true.
Similarly, this region corresponds to where both statements are true.
We see that 1983 falls in the area.
Therefore we execute the statement.
Branching allows us to run different statements for different inputs.
