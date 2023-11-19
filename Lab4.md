1. Log into ieng6\
   keys pressed:\
   ssh cs15lfa23cv@ieng6.ucsd.edu <Enter>\
   ![Image](step1.png)
2. Clone your fork of the repository from your Github account (using the SSH URL)
   keys pressed:
   git clone git@github.com:arelyzmmarin/15Llab7.git <Enter>
   ![Image](step2.png)
3. Run the tests, demonstrating that they fail
   keys pressed:
   cd 15Llab7 <enter>
   bash test.sh <enter>
   ![Image](step3.png)
4. Edit the code file ListExamples.java to fix the failing test (as a reminder, the error in the code is just that index1 is used instead of index2 in the final loop in merge)
   keys pressed:
   vim ListExamples.java
   /index1, <enter>
   N
   e
   x
   i
   2
   <esc> :wq!
   ![Image](step4.png)
6. Run the tests, demonstrating that they now succeed
   keys pressed:
   bash test.sh <enter>
   ![Image](step5.png)
7. Commit and push the resulting change to your Github account
   keys pressed:
   git commit <enter>
   changed index1 to index2
   <enter>
   ![Image](step6.png)
   ![Image](step7.png)
   :wq! 
