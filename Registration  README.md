# University-exam-task 

Registration

Create a program, that checks if registrations are valid. A registration consists of a Username and a Password. On the first line you will receive a number that indicates how many inputs you will receive on the next lines.
A registration is valid when:

-	The  username is surrounded by "U$"
-	The username needs to be minimum 3 characters long, start with an uppercase letter, followed only by lowercase letters
-	The password is surrounded by "P@$"
-	The password needs to start with minimum 5 alphabetical letters (not including digits) and must end with a digit

Example for a valid registration: 
"U$MichaelU$P@$asdqwe123P@$"

You must check if the registration is valid and if it is print:

"Registration was successful"
"Username: {Username}, Password: {Password}"

If it isn’t - print the following message:
"Invalid username or password"

In the end print the count of successful registrations:
"Successful registrations: {successfulRegistrationsCount}"

Input
•	On the first line - n - the count of inputs.
•	On the next n lines - input that you have to check if it has a valid registration.

Output
•	Print all results from each input, each on a new line.
•	In the end print the count of successful registrations


Input
3
U$MichaelU$P@$asdqwe123P@$
U$NameU$P@$PasswordP@$
U$UserU$P@$ad2P@$


Output
Registration was successful
Username: Michael, Password: asdqwe123
Invalid username or password
Invalid username or password
Successful registrations: 1





