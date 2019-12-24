# University-exam-task

Create a program that calculates how many biscuits your factory can make for a month (30 days) and the percentage of production compared to another factory production.
First, you will receive the biscuits produced per day (per worker). After that, you will receive the count of the workers in your factory. Last, you will receive the number of biscuits that the competing factory produces for 30 days.
You need to calculate the production of your factory for 30 days. Then you have to calculate how much more or fewer biscuits you produce compared to the other factory (in percentage). There will be no case where the factories will produce the same amount of biscuits.
Every third day the workers produce only 75% of the usual production. Keep in mind that there can be only a whole biscuit after making calculations for each day – format them to the lower number.
In the end, print the amount of biscuits produced for 30 days in the following format:

"You have produced {countBiscuits} biscuits for the past month."

Then print the percentage of the difference, formatted to the 2nd decimal place, in the following format:
If your production is bigger than the other factory:
"You produce {percentage} percent more biscuits."

If not:
 "You produce {percentage} percent less biscuits."

Input
•	On the first line you will receive the amount of biscuits a worker produce a day – an integer number in the range [1…200]
•	On the second line you will receive the count of the workers in your factory – an integer number in the range [1…1000]
•	On the third line you will receive the amount of biscuits that the competing factory produces for 30 days – an integer number in the range[1…2000]

NOTE: The input will always be in the right format.

Output
•	In the end print the amount of biscuits produced for 30 days and the percentage of the difference formatted to the 2nd decimal place in the format described above.
Constraints
•	Percentage can be over 100%.
•	There will be no case where the factories will produce the same amount of biscuits.



Input
78
8
16000





Output
You have produced 17160 biscuits for the past month.
You produce 7.25 percent more biscuits.

