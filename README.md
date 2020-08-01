# Assignment-Python-PG-16
Python Time Tracking Program

This document defines the implementation process,design, program dependencies and team(contributors)  for this python code.

The program asks Nana to input the start date and time in the format [YYYY-MM-DD HH:MM:SS]. But more efficiently asks Nana to ENTER 'NOW' TO USE THE CURRENT TIME.

Then asks him to Enter stop date and time also in the format [YYYY-MM-DD HH:MM:SS]

The program calculates the hours he spent on a task multiplies it with the expected rates

It then gives Nana the amount of money he made tackling the task.

The time entered and output from the program is stored in a csv/excel file(named:nana) with headings(START_DATE_&TIME, STOP_DATE&_TIME, HOURS_SPENT,AMOUNT_MADE)for future referencing.

Program Dependencies: start_datetime stop_datetime and rates

Exceptions:
With the if statement, when the end date is less than the start date entered, it will output the "print functions" but if it is greater than the start date, it continues to the "else statement" which outputs the amount made.
The except section prints the "print functions" when there is a wrong format for the date and time or when the value entered in any of the format section is greater than the required input range.

Teams:
