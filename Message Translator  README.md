# University-exam-task-1


Message Translator
Create a program, that checks if inputs have a valid command and message and encrypt it. You will receive n count of messages. For each message check if it’s valid.
A message is valid when:

-	The command is surrounded by '!', start with a uppercase letter, followed only by lowercase letters.
-	The command Is mininum 3 characters long
-	There is a colon after the command.
-	There is message consisting of alphabetical letters between '[' and ']'.
-	It has to be minimum 8 characters long.

Example for a valid message: 
"!Send!:[IvanisHere]"

You must check if the message is valid and if it is - encrypt it, if it isn’t - print the following message: 
"The message is invalid"

Encrypting a message means to take all letters from the message and turn them into ASCII numbers. After successful encrypt, print it in the following format:
{command}: {number1} {number2} {number3} (…)

Note: Encrypt only the text in the message. If you have "[Ivan is Here]", the part that you need to encrypt is "Ivan is Here". 

Input
•	You receive a line - input that you have to check if it has a valid message.

Output
•	Print the result in format described above.



Input
2
!Send!:[IvanisHere]
*Time@:[Itis5amAlready]


Send: 73 118 97 110 105 115 72 101 114 101
The message is invalid

