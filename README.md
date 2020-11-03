# Intro to working with files

This repo will introduce you to reading files and using data in calculations.

Start with [Files.md](https://maleich/CS-lesson-plans/blob/master/Files.md) and use [file_practice.py](file_practice.py
) to
 work through the examples.
 
At the end, switch to [my_code.py](my_code.py) to calculate the average temperature in October. 
* Be sure to return the average temperature rounded to 2 decimal places (the hundredths place).
* Run pytest when you are done to be sure your function passes.

## Problem Description
Use the daily temperatures in temps.txt to calculate the average temperature for October.

* Open and read the file into a list
* Remove the whitespace from each entry
* Compute the average of the entries

## Hints for the exercise
* Be careful about the data type. Check the type of the data in the file. What is it - and what does it need to be?
* Note that the first line is actual text - be careful with that.
* You have determined the average of numbers in a list before. Check out "Average x' for a reminder.
* To round a number,use the `round(arg1, arg2)` method
    * arg1 is the variable you want to round
    * arg2 is the number of decimal places you want
 
## Instructions for running the tests in PyCharm
* Go to File --> Settings --> Python Integrated Tools
* Under Testing, change Unittests to pytest
* Go to Run --> Edit Configurations
* Click the "+" to add a new configuration
* Select Python tests --> pytest
* Click OK
* Click the Run button in the toolbar.
* See Megan if anything goes wrong!
