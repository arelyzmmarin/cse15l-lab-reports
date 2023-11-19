1. Log into ieng6\
   keys pressed:\
   ```
   ssh cs15lfa23cv@ieng6.ucsd.edu <enter>
   ```
   The ssh command is used to switch your terminal's context to running commands on another computer, in this case we are using my course specific CSE15L server. We press enter to execute this command.\
   ![Image](step1.png)
2. Clone your fork of the repository from your Github account (using the SSH URL)\
   keys pressed:\
   ```
   git clone git@github.com:arelyzmmarin/15Llab7.git <enter>
   ```
   The git clone command downloads the code from the given respository url. We press enter to execute this command.\
   ![Image](step2.png)
3. Run the tests, demonstrating that they fail\
   keys pressed:\
   ```
   cd 15Llab7 <enter>
   bash test.sh <enter>
   ```
   The file we want to run, test.sh, is in a folder called 15Llab7. We use cd to change the current working directory to the given path, cse15Llab7, so that we can access it. We press enter to execute this command. The bash command runs bash scripts, which are a sequence of commands we could run at the terminal saved in a file. The commands we want to run in order to run our tests are in the file test.sh. We press enter to execute this command.\
   ![Image](step3.png)
5. Edit the code file ListExamples.java to fix the failing test (as a reminder, the error in the code is just that index1 is used instead of index2 in the final loop in merge)\
   keys pressed:\
   ```
   vim ListExamples.java 
   /index1, <enter>
   N
   e
   x
   i
   2
   <esc>
   :wq!
   ```
   
   ![Image](step4.png)
7. Run the tests, demonstrating that they now succeed\
   keys pressed:\
   ```
   bash test.sh <enter>
   ```
   ![Image](step5.png)
9. Commit and push the resulting change to your Github account\
   keys pressed:\
   ```
   git commit <enter>
   changed index1 to index2
   <enter>
   :wq!
   ```
   ![Image](step6.png)
   ![Image](step7.png)
   
