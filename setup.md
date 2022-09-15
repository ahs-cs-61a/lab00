# instructions for setup in Replit:

1. make Github repository public: settings, scroll to bottom -> change visibility -> complete verification, make public
2. import GitHub repository for each lab into Replit
3. select "labs/lab0x" from dropdown when asked to configure entry point
4. go to Shell and run ```python3 -m pip install pytest``` to install pytest code tester (auto-tester)
5. run ```python3 -m pip install -e .``` to correctly import files and packages
6. share your Replit project with "Robertian23"
  
completing problems:
  
1. go over lecture slides in order, they are linked in the README file of each lab; optional corresponding lecture recordings will also be linked
2. each lab assignment for this course merges lab, discussion, and hw questions from 61A (it was easier to just have one file, since the grade is not as important); sections of the lab assignment are separated, follow those links for problem descriptions and requirements
3. each problem will have doctests (the lines of code under def statements with >>>); these show you the correct output for each input to the Python interpreter
  
running tests:

- after completing each question, run the corresponding auto-tester for that question by running command: ```python3 -m pytest tests/test.py -k test_name_of_function``` 
- after completing ALL questions, run one final test for all questions by running command: ```python3 -m pytest tests/test.py```

debugging & testing code:
  
- to test code yourself, put function calls in main.py and run ```python3 main.py``` in the Shell to see the output (you may need to put some stuff in prints); you don't have to press "Run" after making changes
- the red highlight is the failed case; the left side of the "==" is the output of your function, and on the right is the correct output - you can see the function call on the line before
  
running "What Would Python Display?" (WWPD?):
  
- un-comment the first WWPD line in main.py and run ```python3 main.py``` in the Shell and complete the questions
- re-comment out that line and un-comment the next line after completing each question set

helpful resources: 
 
- [Python Tutor](https://pythontutor.com/composingprograms.html#mode=edit): great visualization of frames and environments; to use: paste code into Python Tutor, click "visualize execution", and click through steps
- [CS61A Code](https://code.cs61a.org/): easy and quick browser Python interpreter; for longer problems, paste code into a new file, run/open new Python interpreter by clicking green arrow in top right (do this every time you make changes to code in a file)

reminders:
  
- everything is run in Shell, not Console!
- after completing each lab, push to GitHub and complete the turn-in in GradeScope
