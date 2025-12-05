# Programming_Task_1-2-Python_Basic-Advanced-

## Task_1 :
Here is a sample line of code that can be executed in Python:
print("Hello, World!")
You can just as easily store a string as a variable and then print it to stdout:
my_string = "Hello, World!"
print(my_string)
The above code will print Hello, World! on your screen. Try it yourself in the editor below!
Input Format
You do not need to read any input in this challenge.
Output Format
Print Hello, World! to stdout.
Sample Output 0
Hello, World!

## Task_2 :
Given an integer, , perform the following conditional actions:
If  is odd, print Weird
If  is even and in the inclusive range of  to , print Not Weird
If  is even and in the inclusive range of  to , print Weird
If  is even and greater than , print Not Weird
Input Format
A single line containing a positive integer, .
Constraints
Output Format
Print Weird if the number is weird. Otherwise, print Not Weird.
Sample Input 0
3
Sample Output 0
Weird
Explanation 0
n = 3
n is odd and odd numbers are weird, so print Weird.
Sample Input 1
24
Sample Output 1
Not Weird
Explanation 1
n = 24
n > 24 and n is even, so it is not weird.

## Task_3 :
The provided code stub reads two integers from STDIN,  and . Add code to print three lines where:
The first line contains the sum of the two numbers.
The second line contains the difference of the two numbers (first - second).
The third line contains the product of the two numbers.
Example
a = 3
b = 5
Print the following:
8
-2
15
Input Format
The first line contains the first integer, .
The second line contains the second integer, .
Constraints
1 ≤ a ≤ 10¹⁰
1 ≤ b ≤ 10¹⁰
Output Format
Print the three lines as explained above.
Sample Input 0
3
2
Sample Output 0
5
1
6
Explanation 0
3 + 2 --> 5
3 - 2 --> 1
3 * 2 --> 6

## Task_4 :
The provided code stub reads two integers,  and , from STDIN.
Add logic to print two lines. The first line should contain the result of integer division,  // . The second line should contain the result of float division,  / .
No rounding or formatting is necessary.
Example
a = 3
b = 5
The result of the integer division 3//5 = 0.
The result of the float division is 3/5 = 0.6.
Print:
0
0.6
Input Format
The first line contains the first integer, .
The second line contains the second integer, .
Output Format
Print the two lines as described above.
Sample Input 0
4
3
Sample Output 0
1
1.33333333333

## Task_5 :
The provided code stub reads an integer, , from STDIN. For all non-negative integers i < n, print i².
Example
n = 3
The list of non-negative integers that are less than n=3 is [0,1,2]. Print the square of each number on a separate line.
0
1
4
Input Format
The first and only line contains the integer, n.
Constraints
1 ≤ n ≤ 20
Output Format
Print n lines, one corresponding to each i.
Sample Input 0
5
Sample Output 0
0
1
4
9
16

# Task_6 :
An extra day is added to the calendar almost every four years as February 29, and the day is called a leap day. It corrects the calendar for the fact that our planet takes approximately 365.25 days to orbit the sun. A leap year contains a leap day.
In the Gregorian calendar, three conditions are used to identify leap years:
The year can be evenly divided by 4, is a leap year, unless:
The year can be evenly divided by 100, it is NOT a leap year, unless:
The year is also evenly divisible by 400. Then it is a leap year.
This means that in the Gregorian calendar, the years 2000 and 2400 are leap years, while 1800, 1900, 2100, 2200, 2300 and 2500 are NOT leap years. Source
### Task
Given a year, determine whether it is a leap year. If it is a leap year, return the Boolean True, otherwise return False.
Note that the code stub provided reads from STDIN and passes arguments to the is_leap function. It is only necessary to complete the is_leap function.
Input Format
Read year, the year to test.
Constraints
1900 ≤ year ≤ 10⁵
Output Format
The function must return a Boolean value (True/False). Output is handled by the provided code stub.
Sample Input 0
1990
Sample Output 0
False
Explanation 0
1990 is not a multiple of 4 hence it's not a leap year.

## Task_7 :
The included code stub will read an integer, n, from STDIN.
Without using any string methods, try to print the following:
123...n
Note that "..." represents the consecutive values in between.
Example
n = 5
Print the string 12345.
Input Format
The first line contains an integer n.
Constraints
1 ≤ n ≤ 150
Output Format
Print the list of integers from 1 through n as a string, without spaces.
Sample Input 0
3
Sample Output 0
123
