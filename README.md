Download Link: https://assignmentchef.com/product/solved-cmpt141-assignment-1-algorithms-data-expressions-variables-and-i-o
<br>



<strong>Question 1</strong>

<strong>Purpose: </strong>To familiarize you with the Academic Honesty policy, and Moodle’s assignment submission, and to do a little writing practice. <strong>Degree of Difficulty: </strong>Easy

Read the <a href="https://www.cs.usask.ca/students/current-students/academic-honesty.php">Academic Honesty webpage</a> at <a href="https://www.cs.usask.ca/students/current-students/academic-honesty.php">https://www.cs.usask.ca/students/current-students/academi</a>c-honesty. <a href="https://www.cs.usask.ca/students/current-students/academic-honesty.php">php</a> (click coloured text to open). In the context of what you read, which of the following scenarios are violations of academic honesty? Explain in one or two sentences why or why not by referring to the academic honesty webpage. Please do not write lengthy answers.

<ul>

 <li>Red and Blue are working on an assignment together. Red emails her answer to Blue. Blue copies it and hands it in.</li>

 <li>Giovanni and Ash are enemies. Ash hacks into Giovanni’s user account, and copies Giovanni’s work for the assignment.</li>

 <li>Squirtle, Charry, Bulba, and Pikachu are a study group who have decided to work together on the assignment. Each of them answered one question, and then brought the answer to the group for discussion. After a long process of discussion and analysis, in which all the group members participated equally, they created a final answer to each question that they all copied.</li>

 <li>Brock and Misty just met in the lab. Misty has done some programming before, but Brock is a novice. Misty helped Brock fix his program so that it looked pretty much like her own.</li>

 <li>Jessie and James were passing through the lab when their friend Meowth stopped them and asked them for help figuring out why his program wasn’t working right. James and Jessie looked at Meowth’s program and explained what the problem was and what was causing it. Meowth pretended to thank them, and proceeded to fix the error on his own.</li>

 <li>Mewtwo and Lucario worked on the assignment together. Once they were fairly sure they understood the solutions, they destroyed all copies of their work. After playing an hour of Pokemon, they recreated the solutions to the assignment separately, from scratch, without consulting each other, or the notes they made.</li>

</ul>

Feel free to discuss these scenarios with other students, TAs, and instructors. It’s very important that everyone understand the rules, as they will be applied to all assignments in CMPT 141. When the solutions are released, come back to these scenarios to make sure your understanding is consistent with ours!

<strong>Question 2:</strong>

<strong>Purpose: </strong>To practice the concept of <em>stepwise refinement</em>.

<h2>Degree of Difficulty: Easy</h2>

Many students are too poor to have a dishwasher, so they might need to wash dishes by hand. Here is a pseudocode algorithm for the task of manually washing dishes.

Rewrite the algorithm in more detail by using stepwise refinement. Replace each action with at least three sub-actions that describe how to accomplish the original action. There are many possible correct answers. Any reasonable, sensible answer will be accepted.

<table width="652">

 <tbody>

  <tr>

   <td width="652">Algorithm WashDishes:fill sink wash dishes dry dishes</td>

  </tr>

 </tbody>

</table>




<strong>Question 3 :</strong>

<strong>Purpose: </strong>To understand the parts of an algorithm.

<table width="652">

 <tbody>

  <tr>

   <td width="652">Algorithm checkGrades:Input: a set of numbers representing percentile student grades.Grades range from 0 to 100, where 50 is a passing grade.Output: a variable ’fraction’ that is the percentage of grades that are at least 50 or higherlet count = 0 for each grade in the set of grades:if the grade is at least 50: let count = count + 1 let fraction = count / the size of the set of grades</td>

  </tr>

 </tbody>

</table>

<h2>Degree of Difficulty: Moderate 1</h2>

2

3 4 5 6

7 8 9

10

11

12

Answer the following questions about the above algorithm:

<ul>

 <li>How many <strong>inputs </strong>does this algorithm have? What are these input(s)?</li>

 <li>How many <strong>outputs </strong>does this algorithm have? What are these output(s)?</li>

 <li>In as <strong>few words as possible</strong>, what is the <strong>problem </strong>that the algorithm is solving?</li>

</ul>

<strong>Question 4:</strong>

<strong>Purpose: </strong>To practice console input and output of strings.

<h2>Degree of Difficulty: Easy</h2>

A “mad-lib” is a fill-in-the blank game. One player writes a short story in which some words are replaced by blanks. For each word that is removed, the appropriate part of speech is noted: e.g. noun (person/place/thing), adjective (word that describes a noun), verb (an action, e.g. eat), adverb (modifies a verb, e.g. quickly). Then, before reading the story, the story-writer asks the other player to write down a word of the appropriate part of speech for each blank without knowing the context in which it will be used. In this way, a humorous (sometimes) or non-sensical (usually) story is created.

Write your own mad-lib. It must have <strong>at least three blanks </strong>in it. Now write a Python program that does the following:

<ul>

 <li>Using the input() syntax (see textbook Section 2.4.2 “Reading Strings from the Keyboard”) for reading strings from the console, prompt the user to enter a word of the appropriate part of speech for each blank in your program. Have a different, appropriately named variable refer to each word.</li>

 <li>Print your story to the console using the print() syntax, filling in the blanks in your story using the strings referred to by the variables that you gathered in Step 1. While it is possible to do this using a single print(), readability of code is important! You are permitted to use as many print() statements as you wish.</li>

</ul>

You must write your own unique story. There is no good reason why two students should submit the same story. Remember you must use a minimum of three blanks, and therefore, your program must read at least three words from the console. You can have more blanks, but get all your other work done before you spend a lot of time having fun with this question!

<h1>Sample Run</h1>

Here is an example of how your program’s console output might look. <strong>Do not submit this story! </strong>Write your own story. In our example, we use green text to show what the user typed in; blue text highlights where the user’s data gets put in the story. If you’re using PyCharm to run your program, the user input will also be green, but it won’t show any blue text.

<table>

 <tbody>

  <tr>

   <td> </td>

  </tr>

 </tbody>

</table>

Enter a verb ending in “ing”: zipping

Enter a noun: squirtle

Enter a verb (past tense): zapped

Pikachu was zipping through some tall grass.

<table>

 <tbody>

  <tr>

   <td> </td>

  </tr>

 </tbody>

</table>

Suddenly, a squirtle appeared! The squirtle zapped Pikachu. It was not very effective.

<strong>Question 5 :</strong>

<strong>Purpose: </strong>To practice console I/O, particularly reading numbers from the console, and use of variables.

Degree of Difficulty: Easy

We’ve all fantasized about destroying our computers when they don’t work properly. In the spirit of scientific inquiry, let’s write a program to compute how long a computer will take to hit the ground when dropped out of a window. Ignoring air resistance, the time (in seconds) when the computer hits the ground is:

<em>t </em>= <sup>p</sup>(2× <em>H/</em>9<em>.</em>8)

In the above formula, <em>t </em>is the time in seconds, and <em>H </em>is the height in meters from which the computer is dropped with no initial velocity. The formula may not be accurate if you are throwing the computer!

Write a Python program that does the following:

<ul>

 <li>Put the following as the first line of your program:</li>

</ul>

import math as m

We’ll cover what this means in class a bit later. For now, it is enough to know that this line allows us to use mathematical functions defined in the module called math.

<ul>

 <li>Prompt the user to enter the starting height of the computer in meters. Read the user’s response <strong>as a number </strong>using the input() syntax (see textbook Section 2.4.3 “Reading Numbers from the Keyboard”) and set a variable called H to refer to it.</li>

 <li>Compute the time at which the computer hits the ground using the above formula and have a variable called time_of_impact refer to the result. You can compute the square root of the value of an expression by writing m.sqrt(<em>expression</em>). For example, the square root of two times seven can be written m.sqrt(2*7). This syntax is made available by the line you wrote in step (a): we’re using the square-root function defined in the math module.</li>

 <li>Use the values of the two variables to display a message to the console that describes the solution to the problem (see sample program run, below).</li>

</ul>

<h1>Sample Run</h1>

If you’ve completed your program correctly, you should see something like the following on the console when you run it:

From what height is the computer dropped? 42

There is a satisfying explosion of circuitry!

<table>

 <tbody>

  <tr>

   <td> </td>

  </tr>

 </tbody>

</table>

The computer dropped from 42.0 meters hits the ground after 2.9277002188455996 seconds.

Note: the green number is text entered by the user at the console; blue text highlights the values referred to by program variables H and time_to_impact. Of course, you’ll see different numbers if you enter different values of H. If you are using PyCharm, the input text will be green (unless you change the preferences), but none of Python’s console output will be blue.

<strong>What to Hand In</strong>

Hand in your solution in a file called a1q5.py.

<strong>Question 6:</strong>

<strong>Purpose: </strong>To practice the use of arithmetic expressions.

<h2>Degree of Difficulty: Moderate</h2>

Phoenix Wright is a lawyer who runs a small law office with some number of assistants. When (if?) Phoenix gets paid for a case, he divides the money between himself and all his staff. The office contract states that Phoenix, as senior partner, takes 25% of the fee for himself and divides the rest equally among all his staff.

Write a program for Phoenix that will ask the user to input the payment for one case (in dollars), and the number of staff in the office (not including Phoenix himself). Then the program should display the value of Phoenix’s share of the fee, the value of the remaining share to be divided amongst the staff, and the value of the pay that each staff member takes home.

You may assume that the user supplies valid input from the console, that is, a positive number for the fee, and a positive number for the staff size.

<h1>Sample Run</h1>

If completed correctly, your program’s console output should look something like this. As usual, green text shows the text entered by the user, and blue text highlights the values calculated by the program.

Enter the payment for the case: 9000

Enter the number of staff: 2

Phoenix Wright’s 25% share of the fee is worth: $2250.0

The staff’s 75% share of the fee is worth: $6750.0

<table>

 <tbody>

  <tr>

   <td> </td>

  </tr>

 </tbody>

</table>

Each staff member takes home: $3375.0

Notice that the user is not expected to type the $ when entering the value of the legal fee. It is also not a concern if your displayed dollar amounts have more or less than two digits after the decimal place, or don’t have a decimal at all. You will not be penalized for this (unless the values computed are incorrect). If you are having trouble getting the dollar amounts to print right next to the dollar signs without a space in between, think about how you might use the string concatenation operator (the very end of textbook Section 2.3.4 “Operators on Strings”) to achieve the desired output.