**Lab Report 4**

For the lab report this week, reproduce the task from above on your own. For each numbered step starting right after the timer (so steps 4-9), take a screenshot, and write down exactly which keys you pressed to get to that step. For special characters like <enter> or <tab>, write them in angle brackets with code formatting. Then, summarize the commands you ran and what the effect of those keypresses were.

For example, when you run the tests, you might want to use the up arrow or Ctrl-R to access your bash history rather than typing in the full command with classpath, etc. You might say something like this accompanying the screenshot for running the tests:

Keys pressed: <up><up><up><up><enter>, <up><up><up><up><enter> The javac -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar *.java command was 4 up in the search history, so I used up arrow to access it. Then the java -cp .:lib/hamcrest-core-1.3.jar:lib/junit-4.13.2.jar org.junit.runner.JUnitCore ... command was 4 up in the history, so I accessed and ran it in the same way.

Add this lab report to your Github Pages site, and submit a PDF of it as usual.

My actual lab report below:
4.) Log into ieng6
Keys pressed: <ssh cs15lfa23bh@ieng6.ucsd.edu> <Enter>
Summary: I'm trying to log in to the ieng6 server without having to be prompted for a password. 

5.)Clone your fork of the repository from your Github account (using the SSH URL)
Keys pressed: <git clone git@github.com:PaulR2023/lab7.git> <Enter>
Summary: I had to fork the repository to my own and then have to git clone for lab7 and it should be able to transfer all the files here. 

6.)Run the tests, demonstrating that they fail
Keys pressed: <bash test.sh> <Enter> 
Summary: I run bash and it demonstates that there was a failure in the testMerge2(ListExamplesTest) in .java that needed to be fixed.

7.)Edit the code file to fix the failing test
Keys pressed: <vim ListExamples.java> <Enter> <Ctrl+D> <Ctrl+D> <8 down arrow> <7 right arrows> <i> <backspace> <2> <Esc> 
<:> <wq> <Enter>
Summary: I opened vim as a text editor and have to use the keyboard to navigate and insert the number 2 to fix the buggy code that is happening and then I save and quit.

8.)Run the tests, demonstrating that they now succeed
Keys pressed: <up><up><Enter>
Summary: I did the test again and it all said OK and that the test has finally passed.

9.)Commit and push the resulting change to your Github account (you can pick any commit message!)
Keys pressed: <git add .> <Enter> <git commit -m "Changes index1 to index2"> <Enter> <git push> <Enter>
Summary: I did the git commands to be able to see my edits in gitHub. 

The full keypresses from step 4 to 9.
<ssh cs15lfa23bh@ieng6.ucsd.edu> <Enter> I'm trying to log in to the ieng6 server without having to be prompted for a password., <git clone git@github.com:PaulR2023/lab7.git> <Enter>, <bash test.sh> <Enter> I had to fork the repository to my own and then have to git clone for lab7 and it should be able to transfer all the files here. , 
<vim ListExamples.java> <Enter> <Ctrl+D> <Ctrl+D> <down ><down><down><down ><down ><down><down><down> <right><right><right><right><right><right><right> <i> <backspace> <2> <Esc> <:> <wq> <Enter> I opened vim as a text editor and have to use the keyboard to navigate and insert the number 2 to fix the buggy code that is happening and then I save and quit., <up><up><Enter> I did the test again and it all said OK and that the test has finally passed., <git add .> <Enter> <git commit -m "Changes index1 to index2"> <Enter> <git push> <Enter>, I did the git commands to be able to see my edits in gitHub.
