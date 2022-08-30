# lab00 (introduction and setup)

WELCOME TO CS61A AT AHS!

CS61A: Structure and Interpretation of Computer Programs is an "introductory" CS course at UC Berkeley that succeeds CS10 (AP CSP equivalent, what Mr. Morris used to teach at Cal). It is a challenging and fast-paced course that starts to delve deeper into more complex algorithms and structures of CS using Python.  
  
In CS61A at Cal, they teach multiple languages other than Python (e.g. Scheme, Regex, SQL), but at AHS, we will focus on Python.  
UCB EECS has course websites archives available to the public, including lecture slides, HW, labs, discussion worksheets, and projects. We have adapted this course at AHS from the 2022 summer session, so they may not match other semesters' curriculum. Most of the lab problems are made by 61A course staff, but most answer keys are made by me (Robert Tian :)).  
  
This is a great opportunity to learn new topics and techniques that are not present or harder to implement in OOP languages such as Java. After CS61A, there is 61B and 61C, which explore data structures and computer architecture, respectively. I hope you enjoy this course!  


UC Berkeley CS61A Summer 2022 course website (archive): https://inst.eecs.berkeley.edu/~cs61a/su22/
  
  
instructions for setup in Replit:

1. import GitHub repository for each lab into Replit (make sure the repository is public on GitHub - you have to pay on Replit to import private ones)
2. go to shell and run ```python3 -m pip install pytest``` to install pytest code tester (auto-tester)
3. share your Replit project with "Robertian23"
  
completing problems:
1. go over lecture slides in order, they are linked in the README file of each lab
2. each lab assignment for this course merges lab, discussion, and hw questions from 61A (it was easier to just have one file, since the grade is not as important); sections of the lab assignment are separated, follow those links for problem descriptions and requirements
3. each problem will have doctests (the lines of code under def statements with >>>); these show you the correct output for each input to the Python interpreter
  
running tests:

- after completing each question, run the corresponding auto-tester for that question by running command: ```python3 -m pytest tests/test.py -k test_name_of_function``` 
- after completing ALL questions, run one final test for all questions by running command: ```python3 -m pytest tests/test.py```
  
debugging/reading failed tests:

- the red highlight is the failed case; the left side of the "==" is the output of your function, and on the right is the correct output - you can see the function call on the line before
- you can use console to call functions/test your code in a Python interpreter
  
  
  
  
  
  
  
code questions are compiled from UC Berkeley CS61A resources and assignments, auto-tester and test cases written by Sean Morris (AHS CS teacher) and Robert Tian (c/o '23)
