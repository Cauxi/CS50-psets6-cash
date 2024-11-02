# psets6-cash
<strong>NOTE</strong>: Copying this data and using it for your submission will breach the academic honesty policy of CS50. Please make sure to understand the material and solve the problem yourself—it's worth it!

<p>This is my solution to the CS50 "Cash" problem set, implemented in Python. You can find the full problem description <a href="https://cs50.harvard.edu/x/2024/psets/6/cash/">here</a>.</p>
Problem Overview
<p>In this problem, I implemented a program that calculates the minimum number of coins required to make a given amount of change. The program prompts the user to input a dollar amount, converts it to cents, and determines the least number of coins (quarters, dimes, nickels, and pennies) needed for that amount.</p> <p>This solution was completed as part of <strong>CS50: Introduction to Computer Science</strong>. Uploading my solution to GitHub complies with CS50’s academic honesty policy. For more information, please refer to this <a href="https://www.reddit.com/r/cs50/comments/63235w/is_this_reasonable/">Reddit thread</a>.</p>
Program Structure
<ul> <li><strong>User Input</strong>: Prompts the user to enter an amount in dollars and validates the input to ensure it’s a non-negative number.</li> <li><strong>Coin Calculation</strong>: Converts the dollar input into cents and calculates the minimum number of coins (quarters, dimes, nickels, pennies) required.</li> </ul>
Key Steps:
<ol> <li><strong>Input Validation</strong>: Prompts for a dollar amount and ensures it is a non-negative decimal.</li> <li><strong>Conversion to Cents</strong>: Converts the dollar amount into cents to simplify the calculation process.</li> <li><strong>Minimum Coin Calculation</strong>: Calculates the number of each coin type required, minimizing the total number of coins.</li> </ol> <p>Note: This repository does not include any files provided by CS50, such as sample input-output files or additional resources.</p>
