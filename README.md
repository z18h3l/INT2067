java cAssignment 1 
INT2067 Introduction to Programming and Problem Solving 
2024-2025 Semester 1 
Due Date: October 30, 2024 (Wednesday) 
1 Introduction 
In this assignment, you need to implement a text-based game based on the riddle about 
a farmer who needs to cross a river with a fox, a goose, and a sack of corn. 
2 Riddle 
A farmer with a fox, a goose, and a sack of corn needs to cross a river. The farmer has a 
rowboat, but there is room for only the farmer and one of her three items. 
Unfortunately, both the fox and the goose are hungry. The fox cannot be left alone with 
the goose, or the fox will eat the goose. Likewise, the goose cannot be left alone with 
the sack of corn, or the goose will eat the corn. How does the farmer get everything 
across the river? 
3 Game 
In your text-based game, the farmer can move at most one item to the other shore each 
time. You should ask the user to enter a command to determine what item the farmer 
wants to take at each turn. The game ends when the user quits the game or when the 
user has succeeded or failed. 
4 Basic Design 
You may follow the following basic flow in your program: 
 Show item locations. 
 Repeat: 
1. Ask for the next command. 
2. Update item locations if necessary. 
3. Show item locations. 
4. Exit the loop if the game has succeeded or failed. 
You may need to add other steps and/or flows to fulfill all the requirements. 
5 Requirements (70%) 
Your program should do the following: 
 [5%] Print the goal of the game at the start. 
 [10%] Ask the user to enter a command at each turn and continue until the user 
requests to quit or the goal has succeeded or failed. 
 [10%] Show the location of the boat and the three items (fox, goose, corn) clearly 
at the start of the game and after each turn. You may follow the output in the 
sample session. 
 Accept the following five one-character strings as valid commands: f, g, c, m or 
q. After receiving a valid command, the game should: 
o f, g or c: move the fox, goose, or corn, if available, to the opposite shore 
along with the boat. [10%] 
o m: move the boat to the opposite shore without any item. [5%] 
o q: quit the game. [5%] 
 [10%] Check whether the requested item is on the same shore as the boat when 
the game receives the command f, g or c. If not, it should prompt an error and 
allow the user to enter a command again. 
 [10%] Check whether the game has succeeded or failed after each turn. The 
game has succeeded if all items have been moved to the far shore. The game 
has failed if the fox has eaten the goose, or the goose has eaten the corn. When 
the game has succeeded, it should congratulate the user. When the game has 
failed, it should tell the user why. 
 [5%] Show an error if the user has entered an unrecognized command character 
(i.e. a string other than ‘f’, ‘g’, ‘c’, ‘m’ or ‘q’). 
6 Program Design and User Interface (30%) 
 [10%] You should break down your program into functions with reasonable 
length. 
 [10%] You should use functions and/or lists to reduce redundancy. 
 [10%] The output should be neat, and the required information should be shown 
clearly. The text in the output should be correct and contain no spelling 
mistakes. 
7 Submission Requirements 
 Your Python file shoul代 写INT2067、Python
代做程序编程语言d be named as assignment1.py. Submit only the Python 
file assignment1.py through Moodle. Failure to submit the file properly will 
result in a penalty of 5 to 20 marks. 
 See Moodle for the exact time of the deadline for submission. Late submission is 
usually not accepted. You should submit earlier to avoid possibly high tra  ic 
around the deadline. 
8 Hints 
Please check the discussions forum on Moodle regularly for any hints. 
9 Plagiarism Policy 
The assignment should be done only by yourself. Every line of code should be written by 
you. Discussions on the assignment should be kept at a high-level only. You are 
suggested to refer your classmates to the relevant notes or lab exercises if you want to 
help them. 
If cheating is found, both the copier and originator will get zero mark for the 
assignment. 
Repeat o  enders may result in a deduction of the course grade. 
If you have discussed the assignment with anyone, you should provide an 
acknowledgment at the end of your program file. Give the names of all classmates that 
you have discussed with. For example, your acknowledgement may look like this at the 
end of your program file: 
# Acknowledgement: I have discussed it with Thomas, Gordon, and Emily. 
10 Sample Session 1 
Welcome. 
You must bring the fox, the goose, and the corn across the 
river. 
------------------------ 
Boat 
------------------------ 
Fox Goose Corn 
You are now at the near shore, what do you want to take? g 
 Goose 
------------------------ 
Boat 
------------------------ 
Fox Corn 
You are now at the far shore, what do you want to take? m 
 Goose 
------------------------ 
Boat 
------------------------ 
Fox Corn 
You are now at the near shore, what do you want to take? f 
Fox Goose 
------------------------ 
Boat 
------------------------ 
 Corn 
You are now at the far shore, what do you want to take? g 
Fox 
------------------------ 
Boat 
------------------------ 
 Goose Corn 
You are now at the near shore, what do you want to take? c 
Fox Corn 
------------------------ 
Boat 
------------------------ 
 Goose 
You are now at the far shore, what do you want to take? m 
Fox Corn 
------------------------ 
Boat 
------------------------ 
 Goose 
You are now at the near shore, what do you want to take? g 
Fox Goose Corn 
------------------------ 
Boat 
------------------------ 
Congratulations! 
You have brought all the items across the river. 
11 Sample Session 2 
Welcome. 
You must bring the fox, the goose, and the corn across the 
river. 
------------------------ 
Boat 
------------------------ 
Fox Goose Corn 
You are now at the near shore, what do you want to take? 
goose 
You have entered an invalid command. 
------------------------ 
Boat 
------------------------ 
Fox Goose Corn 
You are now at the near shore, what do you want to take? f 
Fox 
------------------------ 
Boat 
------------------------ 
 Goose Corn 
You have failed. 
The goose has eaten the corn. 
References 
V. Anton Sprual. Think Like a Programmer: An Introduction to Creative Problem Solving. 
No Starch Press, San Francisco, 2012. 

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
