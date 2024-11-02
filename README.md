# psets6-cash
<strong>NOTE</strong>: Copying this data and using it for your submission will breach the academic honesty policy of CS50. Please make sure to understand the material and solve the problem yourself—it's worth it!

<p>This is my solution to the CS50 "Sentimental Mario (Less Comfortable)" problem set, implemented in Python. You can find the full problem description <a href="https://cs50.harvard.edu/x/2024/psets/6/sentimental/mario/less/">here</a>.</p>
Problem Overview
<p>In this problem, I recreated the classic Mario pyramid-building program from Week 1, now using Python instead of C. This program takes a user input to specify the pyramid's height and then outputs a half-pyramid of hashes (`#`) of the specified height.</p> <p>This solution was completed as part of <strong>CS50: Introduction to Computer Science</strong>. Uploading my solution to GitHub complies with CS50’s academic honesty policy. For more details, refer to this <a href="https://www.reddit.com/r/cs50/comments/63235w/is_this_reasonable/">Reddit thread</a>.</p>
Program Structure
<ul> <li><strong>User Input</strong>: Prompts the user to enter the height of the pyramid, accepting only valid integer inputs within the range (1–8).</li> <li><strong>Pyramid Construction</strong>: Uses loops to construct a half-pyramid of hashes (`#`), with the number of rows matching the specified height.</li> </ul>
Key Steps:
<ol> <li><strong>Input Validation</strong>: Prompts the user for a height input between 1 and 8 and validates the input.</li> <li><strong>Pyramid Printing</strong>: For each row, the program prints spaces to align the hashes, followed by a number of hashes corresponding to the row number.</li> </ol> <p>Note: This repository does not include any files provided by CS50, such as sample input-output files or additional resources.</p>
