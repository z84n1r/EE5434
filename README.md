java c
EE5434 homework 1 
Out: Monday, September 16, 2022 
Due: 11:59PM September 25 (Wed.). No late submission will be graded. Submit everything at Canvas.Considering this is the first programming homework, you can ask for help from your friends/classmates. In that case, clearly state that fact at the beginning of your report: “ Igot help from first name + last name”. Remember that you should not copy anyone’s codes. Use one- hour rule.Accepted programming languages: Python or MATLAB (only acceptable for the first homework). The following description is using python as the example. If you use MATLAB, please submit your source codes and a readme file for running your programs.
Total point: 50
Handin method and requirement:
1.    Python version:
Name your notebook file (.ipynb) as yourlastname-firstname-studentID-hw1.ipynb. For example, if your name is Amy Zhang, the file should be named as zhang-amy-5678910-hw1.ipynb. Also, attach an html file (generated by the notebook file) with your notebook using the naming rule: yourlastname-firstname-studentID-hw1.html.
2.    MATLAB version:
Name your source code file (.m) as yourlastname-firstname-studentID-hw1.m. Also, attach a report file (pdf version) using the same naming rule.Commonly seen issues: 1. Forget to attach the html file; 2. Use Chinese characters in these files (practice your English for the tests/exams); 3. Used open-source codes online (high identity can lead to a score of -50).
Note that if you copy others’ codes, you can get a heavy penalty up to -50. Multiple violations can lead to heavier penalties.
Overview of the homework: 
Implement the PLA learning algorithm and analyze its performance using different training sets. You can call vector operations but not any modules/APIs about the learning algorithms.
We will provide you with a program that can generate training data for you. Each line contains the coordinates of a data point and its label (+ or -). For example,
10 11.9 +
100.9 20 -
-1 0 +
7 29.8 +
0 99.8 +
0 -18.9 -
23.8 0 -
-45.6 -90.8 -
-6 29 +
Your program will take the output file of th代 写EE5434 homework 1Python
代做程序编程语言e provided program as input and then output the learned weight using PLA.The output should be a weight vector  and also a plot that contains all the training data points and the line (represented by ). The detailed format of the plot: blue circle represents positive labeled data points and red cross refers to negative labels. The line can be black  (refer to the  note  about  the  PLA) .  No  need  to  show  the  vector w.  Just  plot  the  line: w1x1+w2x2+w0=0. Show the axis name (x1  or x2). An example is shown below.
Once you finish the programs. Do the following experiments and record the five images in the report. Name this section Experiment 1. Answer this question briefly: is the learned line closer or further away from the line represented by <5,2,3>? 
python DataEmit.py [5,2,3] 10 10
python DataEmit.py [5,2,3] 50 50
python DataEmit.py [5,2,3] 100 100 python DataEmit.py [5,2,3] 150 150 python DataEmit.py [5,2,3] 200 200
Note: if you are using macOS or Linux, the command line might be: python DataEmit.py ' [5,2,3]' 10 10Then, choose your own vector wand repeat the above experiment. Test PLA’sperformance with 1) increase of the training data (500, 700, and 1000) ; 2) the ratio of the two labels in the training data (balanced to unbalanced). Test at least 3 unbalanced ratios (1:5, 1:20, and 1:50). Name this section Experiment 2. 
For 1), show the running time and also the images. For 2), show the images only in your report.
20 points for the report containing the above analysis.
5 pts for following all the instructions.
25 points for the correct implementation.
The following questions are NOT required and are only for your own “fun” .
1.   Modify DataEmit.py to add noise to the data so that the samples cannot be linearly separable. Run your PLA implementation and see whether it will behave as you expected.
2.   Modify your PLA into the pocket algorithm. Run your pocket algorithm on the same data and check whether the output is expected.
3.   Run your pocket algorithm on the “noisy” data and check whether the output is expected.


         
加QQ：99515681  WX：codinghelp
