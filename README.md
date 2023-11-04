# small-sample-test
by using this code we can identity the Hypothisis of small sample data for various mean
Two-Sample Z-Test Tool
This Python script allows you to perform a two-sample z-test for comparing means between two groups. It calculates the z-statistic and determines whether to accept or reject the null hypothesis based on a given significance level (default is 0.05, corresponding to a 95% confidence level).

Prerequisites
Python 3.x installed on your computer.
Familiarity with two-sample z-tests and hypothesis testing.
How to Use
Run the script in your Python environment.

You will be prompted to provide the following inputs:

n1: The sample size of the first group.
n2: The sample size of the second group.
x: The data values of the first group. You can enter multiple values separated by spaces.
y: The data values of the second group. You can enter multiple values separated by spaces.
s1: The standard deviation of the first group.
s2: The standard deviation of the second group.
The script will calculate the z-statistic based on the provided inputs and compare it to a critical value (default is the z-table value). The result will be one of the following:

If the z-statistic is less than the critical value, it will print "accept null hypothesis."
If the z-statistic is greater than or equal to the critical value, it will print "reject null hypothesis."
Example
makefile
Copy code
n1 = 50
n2 = 60
x = 28 29 31 30 32 30 29 31 29 28
y = 32 33 30 34 31 33 32 31 30 33 31 32
s1 = 2.5
s2 = 3.0

x_bar = 29.8
y_bar = 32.5
z_calculated = -3.179085015022742
reject null hypothesis
Author
[Your Name]

License
This project is licensed under the MIT License - see the LICENSE file for details.

Make sure to replace [Your Name] with your name or your preferred attribution. You can also consider adding a license file (e.g., LICENSE) if you want to specify the terms under which others can use your code.
