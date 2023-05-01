Download Link: https://assignmentchef.com/product/solved-cis1500-assignment-2-rock-paper-scissors-lizard-spock
<br>
<h1>1.0 Rock-Paper-Scissors (Lizard-Spock) Context</h1>

(Dialogue below taken from Series 02 Episode 08 of Big Bang Theory)

<em>Raj Koothrappali</em>: I’ll tell you what. How about we go rock-paper-scissors?

<em>Sheldon Cooper</em>: Ooh, I don’t think so. Anecdotal evidence suggests that in the game of rock-paper-scissors, players familiar with each other will tie 75 to 80% of the time due to the limited number of outcomes. I suggest rock-paper-scissors-lizard-Spock.

<em>Raj Koothrappali</em>: What?

<em>Sheldon Cooper</em>: It’s very simple. Scissors cuts paper. Paper covers rock. Rock crushes lizard. Lizard poisons Spock. Spock smashes scissors. Scissors decapitates lizard. Lizard eats paper. Paper disproves Spock. Spock vaporizes rock. And as it always has, rock crushes scissors.

Rock-Paper-Scissors (RPS) is a hand game which involves making a motion three times with your fists, and then either show a flat hand (paper), clenched fist (rock), or two fingers extended and separated (scissors). Depending on the results, the game is a tie (both show the same), or one person wins. The objective is to select a gesture which defeats that of the opponent. Gestures are resolved as follows:

<ul>

 <li>Rock blunts or breaks scissors: rock defeats scissors.</li>

 <li>Scissors cut paper: scissors defeats paper.</li>

 <li>Paper covers, sands or captures rock: paper defeats rock.</li>

</ul>

If both players choose the same gesture, the game is tied.

You may refer to the Rock-paper-scissors Wikipedia page

(https://en.wikipedia.org/wiki/rock-paper-scissors) to learn more about the game.

Check out the Additional Weapons (<u>https://en.wikipedia.org/wiki/Rock-paperscissors#Additional_weapons</u>) section for more information about the addition of lizardSpock to the base game.

<h1>2.0 Your Task</h1>

Write a program to play a game of Rock, Paper, Scissors.

Make sure your program is readable, including appropriate comments, and incorporates aspects of usability in the text prompts to the user.

<u>/! Note</u>: Your program should use decision statements, loops and simple user-defined functions with return types and call-by-value parameters.

Your program should perform the following:

<ol>

 <li>Prompt the player for the number of games they wish to play.</li>

 <li>Use a loop to allow the program to run a number of games requested by the player.</li>

 <li>Within each game, prompt the player for their choice of rock, paper or scissors. Use numeric values 1, 2, and 3 to allow the user to choose a gesture. Any other value is considered invalid. <u>You must do this inside a function. </u>Let the function return the gesture chosen by the player back to main.</li>

</ol>

Use the following name and prototype for this function:

int getPlayersResponse (void);

<ol start="4">

 <li>Use the code below (integrating it into your program) to generate the computers gesture: 1, 2, or 3.</li>

</ol>

<u>/! Note</u>: You must generate a new random value for x for each game.

<table width="0">

 <tbody>

  <tr>

   <td width="198">In the header section</td>

   <td width="284">In the main part of the program</td>

  </tr>

  <tr>

   <td width="198">#include &lt;stdio.h&gt;#include &lt;time.h&gt;</td>

   <td width="284">int x;srand (time (NULL)); x = (rand () % 3) + 1;</td>

  </tr>

 </tbody>

</table>

How does this code work? Basically the function rand() generates a random number and then performs mod 3, i.e. it returns the remainder when the random number is divided by 3 – so the remainder will be 0, 1, or 2. A value of 1 is added to this number to give 1, 2, or 3.

<ol start="5">

 <li>Decide who wins, the player or the computer, and print out an appropriate message – indicate who the winner is, or if the game becomes tied.</li>

 <li>At the end, your program should count the number of wins for the player, number of wins for the computer, and the number of ties, and display these statistics. <u>You must do this inside a function.</u></li>

</ol>

Use the following name and prototype for this function:

void printResults (int gamesTied, int gamesWonByPlayer, int gamesWonByComputer);

<h1>3.0 Sample Program Output</h1>

An example of a program with the features mentioned above is shown below.

User inputs are <u>Bolded and Underlined</u>

This program allows you to play Rock, Paper, Scissors  How many games do you want? <strong><u>2</u> </strong>




Game Number: 1




Possible Choices: 3=Rock, 2=Scissors, 1=Paper  What’s your choice (number)? <strong><u>1</u></strong>

My choice is paper.

Tie game – no winner




Game Number: 2




Possible Choices: 3=Rock, 2=Scissors, 1=Paper  What’s your choice (number)? <strong><u>3</u></strong>

My choice is scissors.

You win!!




Here is the final score…




I have won 0 game(s), you have won 1 game(s) and 1 game ended in a tie.




Thanks for playing!




<h1>4.0 Additional Functionality</h1>




By completing the above task correctly, you have the potential to earn up to 90% of the grade for this assignment. By going beyond the material given and completing the task below, you have the potential of earning another 10% for a total of 100%.

<ul>

 <li>Extend the program to play rock-paper-scissors-lizard-Spock.</li>

</ul>

<h1>5.0 Program Submission and Administration Information</h1>

The following section outlines what is expected when submitting the assignment and various other administration information with respect to the assignment.




5.1 Program Submission

To submit your assignment, upload your program C file to the submission box for A2 on Moodle. The following is expected for the submission file that is to be submitted upon completing the assignment:

<ul>

 <li>You are to submit ONE file containing your program.</li>

 <li>The file you are to submit is a code C file. (ends with .c)</li>

 <li>The name of the file follows the following format: lastnameFirstnameA2.c o Example: Ritu is the first name and Chaturvedi is the last name then the file name is chaturvediRituA2.c</li>

</ul>

o Incorrect file name will result in penalty.

5.2 Program Expectations

Your program is expected to follow the outlined information exactly. Failure to do so will result in deductions to your assignment grade.

<ul>

 <li>The program file you submit MUST compile with NO warnings and errors using the -std=c99 and -Wall flags.</li>

 <li>Programs that fail to compile will be given a mark of 0.</li>

 <li>Programs that produce warnings upon compilation will receive a deduction of 1 mark for each type/category of warning.</li>

 <li>The program file must contain instructions for the TA on how to compile and run your program in a header comment. For more information on this please see section <u>Compiling and Running Header Comment Format</u>.</li>

</ul>

<strong><u>/! Note</u></strong>: A header comment is a type of comment that appears at the top of your program before the #include line.

<ul>

 <li>The program file must contain the header comment shown in section <u>Program</u> <u>Header Comment Format</u> with the <strong><u>underlined &amp; bolded</u></strong> sections properly filled in.</li>

</ul>

5.3 Program Header Comment Format

/************************<strong><u>lastnameFirstnameA2.c</u></strong>**************

Student Name: <strong><u>Ritu Chaturvedi</u>       </strong>Email Id: <strong><u>ritu</u></strong>

Due Date: Mar 1<sup>st</sup>, 2019       Course Name: CIS 1500   I have exclusive control over this submission via my password.

By including this statement in this header comment, I certify that:

<ul>

 <li>I have read and understood the University policy on academic integrity;</li>

 <li>I have completed the Computing with Integrity Tutorial on Moodle; and</li>

 <li>I have achieved at least 80% in the Computing with Integrity</li>

</ul>

Self Test.

I assert that this work is my own. I have appropriately acknowledged any and all material that I have used, whether directly quoted or paraphrased. Furthermore, I certify that this assignment was prepared by me specifically for this course.

**********************************************************/

<strong><u>/! Note</u></strong>: The file name, student name and email ID must be changed per student.

<strong> </strong>

5.4 Compiling and Running Header Comment Format

/*********************************************************

Compiling the program

The program should be compiled using the following flags:

-std=c99 -Wall compiling:

gcc <strong><u>lastnameFirstnameA2</u></strong>.c -std=c99 -Wall

OR gcc <strong><u>lastnameFirstnameA2</u></strong>.c -std=c99 -Wall -o assn2

*********************************************************

Running the Program running: ./a.out

OR

Running: ./assn2

*********************************************************/

<strong><u>/! Note</u></strong>: The file name must be changed per student.