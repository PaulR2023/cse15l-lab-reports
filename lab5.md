Part 1 – Debugging Scenario
Design a debugging scenario, and write your report as a conversation on EdStem. It should have:

The original post from a student with a screenshot showing a symptom and a description of a guess at the bug/some sense of what the failure-inducing input is. (Don’t actually make the post! Just write the content that would go in such a post)

# My response:

Post: I'm encountering a problem with the test that it did compile and didn't show any failures. However when I'm trying to calculate all the values here for a,b, and c. When I did the calculation for the result, I expected the value of 29 but I got a value of 3.0 instead which is I don't get why its this case. I thought it would make sense when we use this "^" to square the value of the number. Any guidance would be appreciated.   

---
A response from a TA asking a leading question or suggesting a command to try (To be clear, you are mimicking a TA here.)
# My response

Hello, I noticed on your code that this "^" doesn't mean square, it's actually a XOR operator that you're showing that if the value is different, then it will return a number, otherwise it would be zero. It looks like it might've been comparing an "a" variable to a 2. I would recommend doing the System.out.println() on each of the letter integer that the value output when performing the expression. Hopefully it can help you see why the value is not what you expect it to be. 

---
Another screenshot/terminal output showing what information the student got from trying that, and a clear description of what the bug is.
# My response

It looks like a bug is that it gives an incorrect value and its not really performing the calculations since for (a)^2 it looks like to be a 0 since a is 2 which is compared with ^ so it returns 0 since they're both the same value. For both (b)^2 and (c)^2 it returned a different value since its not equal to 2 on the ^ operation. 

At the end, all the information needed about the setup including:
The file & directory structure needed

The contents of each file before fixing the bug

The full command line (or lines) you ran to trigger the bug

A description of what to edit to fix the bug

You should actually set up and run the scenario from your screenshots. It should involve at least a Java file and a bash script. Describing the bug should involve reading some output at the terminal resulting from running one or more commands. Design an error that produces more interesting output than a single message about a syntax or unbound identifier error – showcase some interesting wrong behavior! Feel free to set this up by cloning and breaking some existing code like the grading script or code from class, or by designing something of your own from scratch, etc.

# Part 2 – Reflection
In a couple of sentences, describe something you learned from your lab experience in the second half of this quarter that you didn’t know before. It could be a technical topic we addressed specifically, something cool you found out on your own building on labs, something you learned from a tutor or classmate, and so on. It doesn’t have to be specifically related to a lab writeup, we just want to hear about cool things you learned!

Something I learned that I never knew before is logging into a server and being able to make changes with VIM in just the terminal. This is really nice and cool to see that we can just really make an edit in the terminal. This is useful for making edits within the server. The autograder is interesting in that we can see what the TA/graders use to be able to check our work and give feedback if there is something wrong while its compiling and running.
