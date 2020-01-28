
# E02a-Control-Structures

*If you wish your exercise to be graded, please edit the LICENSE file (add the current year and your name).*

- Open main01.py. Before running it, what do you expect this program to do?

 I expect python to print the following:
     Greetings!
     'What is my favorite color?'
 But it will not respond if you type anything in.
   
  - Now right click on the main1.py window and select “Run Python File in Terminal”. Click in the bottom panel, and answer the question. Describe what happened.
  
   I typed 'yellow' to answer the question, but the Python did nt respond in any way.
   
  - What do you think the program did with what you typed in answer to the question?
  
  Because the program did not have anything to do with a response, it sent me back to the starting point of terminal.
    
- Open main02.py. Before running it, describe how this is different than main01.py.

It will produce the same result, but it is different because there is an extra step of designating the term 'color.'

  - What do you think the color = input() will do?
  
  This designates what the term color means within the code.
  
  - Run the program in the terminal and answer the question. Did the program do what you expected?
  
  No, the program is designating the answer to the input "What is my favorite color" to be the 'color'. So after you answer the input, Python reprints your answer.
  
- Open main03.py. Before running it, describe how this is different than main02.py.

This code provides a correct answer for the user, instead of simply reprinting the whatever color the user types in. Python will tell the user to try again until they guess correctly.

  - What is happening on lines 9–12?
  
  These lines designate the correct answer and the responses for correct and incorrect answers by the user.
  
  - Why are lines 10 and 12 indented?
  
  They're indented because they are dependent upon the line of code written above them.
  
  - Run the program and answer the question. What happens if you don’t capitalize Red?
  
  It takes it as an incorrect answer.
  
  - What does this tell you about "color"?
  
  It needs to be tweaked to say "red," and then we need to add a command to turn each response into all lower case before Python processes the result.
  
- Open main04.py. Before running it, describe how this is different than main03.py.

This fixes the issue of different ways to type 'red' in a different way than I explained above. It does this by indicating clor can be 'Red' or 'red'.

  - What problem is this trying to solve?
  
   The lower case 'red' answer issue.
   
  - Run the program and answer the question. What happens if you use some other capitalization scheme (i.e., “RED” or “reD“)?
  
  Any response besides 'red' and 'Red' are considered incorrect, and Python prints "Sorry, try again."
  
- Open main05.py. What do you expect line 9 to do?

Convert answers to be a string of all lower case letters.

  - What problem is it trying to solve?
  
  The issue of different combinations of capitalizing the word 'red'.
  
  - Run the program and answer the question. What happens if you add spaces before or after the word (i.e., “ RED “ or “ red”)?
  
  Python takes this as an incorrect answer.
  
 - Open main06.py. How is line 9 different than in main05.py?
 
It includes '.strip' after '.lower'.
 
   - What would you guess .strip() is doing?
   
The '.strip' removes extra spaces(/characters) on either side of the answer.

   - Run the program and answer the question. Is there another way of writing “red” that will break this logic?
   
   If you mispell the word 'red,' Python will count this as an incorrect answer.
   
 - Open main07.py. Before running this program, how do you expect this to be different than main06.py?
 
 This program leads users in the correct direction instead of letting them guess aimlessly.
 
   - What is happening on line 12?
   
   Its using the 'elif'/else if command to designate another possible response by the user.
   
   - Run the program and answer the question.
 - Open main08.py. What is the purpose of line 9?
 
 To keep the program running until the user guesses the correct answer.
 
   - Why are lines 10–17 indented?
   
   They are indented because they are everything that is happening WHILE the user is guessing and the program is runnning, as specified by line 9.
   
   - Run the program. What would happen if line 10 were moved before line 9 (and no longer indented)?
   
   The user would have no question to answer and the program would not know what their answer is referring to.
   
   - Make that change and run the program again. (To end any Python program, you can type ctrl-c)
   
   It printed the question, but then printed the associated response continuously, instead of running the program continuously.
   
 - Open main09.py. What is happening on line 13?
 
 The program is counting how many responses the user writes to the question.
 
   - What is the purpose of “count”?
   
   The count gives the user a way to track their progress.
   
   - What is happening on line 22?
   
   This is how the program will tell the user how many tries it took them to guess the correct answer after they have guessed it.
   
   - Run the program.
 - *Extra credit:* open main10.py. Add a comment to each line describing what it is doing (a comment follows a pound sign [#]).
 - *Extra credit:* open main11.py. What is happening on lines 6-11?
  
Commit your changes and push them back to the repository.
 

---

Instructions for forking this repository:
 
Log into your account on [github.com](https://github.com)

Go to the [exercise template page](https://github.com/BL-MSCH-C220-S20/E02a-Control-Structures) on GitHub

There is a button in the top right corner of the page labeled "Fork". Press that now

This will create an independent copy of this repository in your account that you can control and edit

Go to your GitHub home page, and select the new E02a-Control-Structures repository

On that page, you will see a green button labeled "Clone or download". Press that now. You will see a drop down box. Press the "Open in Desktop" button.

This should launch GitHub Desktop. It will ask you for a location (on your computer) where the repository may be cloned (downloaded). Choose a location that will be easy for you to find, and press the blue "Clone" button.

Once GitHub Desktop has cloned (downloaded) the code, it will be responsible for keeping the code on your local computer synchronized with the repository in your GitHub account. Now, open Visual Studio Code, and choose File->Open. Find the folder of the cloned repository and select Open.

In the left (File Explorer) panel, you should see a list of files that comprise this repository

First, edit the file called LICENSE. Replace year and name with the current year and your name. Save this file

Then open README.md. Feel free to remove any extraneous information, and then answer the questions posed in the file. You can add your answers after each question

When the time comes for you to run any of the python files, you can do so by clicking the green arrow in the top right corner of the window or by right-clicking on the code and selecting "Run Python File in Terminal". The results will appear at the bottom. If you don't see "Run Python File in Terminal" in the contextual menu, that is because VS Code doesn't have the Python extension installed. You can do that here: [https://marketplace.visualstudio.com/items?itemName=ms-python.python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)

When you are done editing the files, return to GitHub Desktop. In the left panel, you should see a list of the files that have changed

At the bottom of the leftmost area, you should see a text box labeled "Summary (required)". Add a message that describes what you have done; these messages are typically stated in the active-present tense. For example, "Updates the LICENSE, README.md, and completes the assignment." Push the blue "Commit to master" button

In the top bar of the window, you should see a button that is labeled "Push origin", push that now

Check out your page on GitHub. You should see the changes you made reflected there, Repeat steps 10 through 16 as necessary

When you are satisfied with your efforts, turn in a URL to your repository on Canvas

---
If you try to push your changes, and you receive a permission error, it is likely that you are trying to edit the BL-MSCH-C220-S20 copy of the repository rather than your own. Make sure you don't skip the step of forking your own copy and cloning that.

---

The grading criteria will be as follows:
 
[1 point] Repository contains a description of the project in README.md

1 point will be awarded for answering the questions associated with each of the files

10 points total (+2 points extra credit)
