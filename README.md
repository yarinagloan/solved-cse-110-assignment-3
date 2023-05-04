Download Link: https://assignmentchef.com/product/solved-cse-110-assignment-3
<br>
Your programming assignments require <strong>individual </strong>work and effort to be of any benefit. Every student must work independently on his or her assignments. You must work alone on the assignments – no collaboration of any kind is permitted. <strong>You cannot use Google, StackOverflow, Chegg or any other on-line resources</strong> to look up for the solution. Sharing your assignments with others in any way is <strong>NOT </strong>permitted. Violations of the University Academic Integrity policy will not be ignored.




Violations of the University Academic Integrity policy will not be ignored.     The university academic integrity policy is found at <u>https://provost.asu.edu/academic-integrity</u>

<strong><u>Important Note: </u></strong>All submitted assignments must begin with the descriptive comment block.  To avoid losing trivial points, make sure this comment header is included in every assignment you submit.

/*————————————————————————-

// AUTHOR: your name

// FILENAME: title of the source file

// SPECIFICATION: description of the program

// Name of the TA for your weekly lab

// FOR: CSE 110- homework #- days and time of your class

// TIME SPENT: how long it took you to complete the assignment

//———————————————————————-*/

Reasonably good amount of comments should be added in your program so that it is easy

<h1>Part 1: Written Exercises: (4 pts)</h1>

<ol>

 <li>Rewrite the following set of if statements using a nested if-else structure.</li>

</ol>

if (score &gt;= 90) grade = ‘A’;

if (score &gt;= 80 &amp;&amp; score &lt; 90) grade = ‘B’; if (score &gt;= 70 &amp;&amp; score &lt; 80) grade = ‘C’; if (score &gt;= 60 &amp;&amp; score &lt; 70) grade = ‘D’; if (score &lt; 60) grade = ‘F’;




<ol start="2">

 <li>Rewrite the following nested if-else statement as an equivalent <strong>switch s</strong> if (letter == ‘A’ | | letter == ‘a’)    System.out.println(“Excellent”);  else if (letter == ‘B’ | | letter == ‘b’)    System.out.println(“You can do better”);</li>

</ol>

else if (letter == ‘C’ | | letter == ‘c’)

System.out.println(“Try harder”);  else if (letter == ‘D’ | | letter == ‘d’)

System.out.println(“Try much harder”);

else

System.out.println(“Try another major! “);

<h1>Part 2: Programming: (16 points)</h1>

Write a program called Assignment3 (saved in a file <strong>Assignment3</strong> <strong>.java</strong>) that asks a user to enter two strings.




First, the program prompts:




<strong>Please enter a string. </strong>




The program should read in the string, and prompts:




<strong>Please enter another string. </strong>




The program reads in two strings and it prints a menu to the user. The program asks for user to enter an option and performs one of the following:

<strong>Here are the options on the menu: </strong>

<strong> </strong>

Option a: checks if the length of the two strings are the same.

Option b: checks if two strings are same or different.

Option c: checks which string is lexically larger, or if they are same

Option d: prints out the first character (index 0) of each string

Option e: prints out a new string consisting of the first string concatenated (appended) with the second string.

Option f: prints out two strings using upper case letters.

Option q: quit the program.

Here is the sample output your program should produce when the user enters the strings shown in bold:

<strong><u>Sample Output : (the user enters the string shown in bold)</u></strong>

Please enter a string.

<strong>apple </strong>

Please enter another string.

<strong>orange </strong>




Command Options

———————————–

a: find if the lengths of the strings are equal b: find if the two strings are the same

c: find which string is lexically larger d: print the first character of each string e: concatenate the two strings f: print both strings in uppercase

q: quit this program







Please enter an option or type?

<strong>a </strong>




The lengths are not the same.




Please enter an option or type?

<strong>b </strong>




The two strings are different.




Please enter an option or type?

<strong>c </strong>




The second string is lexically larger.




Please enter an option or type?

<strong>d </strong>




The first character of the first string is a

The first character of the second string is o




Please enter an option or type?

<strong>e </strong>




The concatenation of two strings is “appleorange”




Please enter an option or type?

<strong>f </strong>




The first string using upper case letters: APPLE

The second string using upper case letters: ORANGE




Please enter an option or type?

<strong>b </strong>




The two strings are different.




Please enter an option or type?

<strong>q </strong>

Press any key to continue . . .




<strong>Requirements:</strong> make sure you are using a <u>switch statement</u> for the menu. In addition, your program should keep asking for input until user chooses to quit.

<strong>Helpful hints for doing this assignment: </strong>

<ul>

 <li>work on it in steps –</li>

 <li>always make sure your code compiles before you add more code</li>

 <li>the options are called in any order</li>

</ul>