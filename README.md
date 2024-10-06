Practice: Running JavaScript Locally
====================================

It's time to put your newfound Terminal and JS skills to the test!

In this practice, you'll be working with VS Code to create new folders and files, and Node to run JavaScript.

Phase 1: Creating files and folders
-----------------------------------

Let's kick off this project by creating a folder to contain your code.  In fact, this would be a good time to create a folder for all your work here at App Academy. Feel free to name the folder whatever you like, just make sure you remember where you put it. (The Desktop is an ideal place!)

Once you've created a folder for your work, create a new folder within that folder. This folder will contain the work you do for this project, so name it **first-project**.

The first thing you'll want to do with this **first-project** folder is open it up in VS Code. Once you've entered VS Code you can go to "File" then "New File" to create a new file. Name this file **phase-one.js**.

At the top of the **phase-one.js** file, add the following line of code and then save the file.

    console.log ("Look at me go!");
    

Now let's go run some JavaScript.

Phase 2: Using Node to run JavaScript
-------------------------------------

Remember that you have two ways to run JavaScript using Node:

1.  With the REPL
2.  With **.js** files

In this practice, you will use get experience using both. 

### Phase 2A: Using the Node REPL

The first way you'll run JavaScript today is by using the Node REPL. Open a window of the Terminal application and type in the command:

    ~ $ node 

You should see your icon change to look like this: `>`. Now do the following to get comfortable using the Node REPL:

1.  Write a `console.log` statement that will print "Hello Node!".
2.  Write four mathematical expressions.
    *   Each expression should use one of the following symbols: `+`, `-`, `*`, and `/`.

The Node REPL is an interactive code environment that allows you to test how JavaScript will react to simple expressions. Learning to use a REPL to test ideas and to ask your coding environment questions (as shown in the above simple and quick problems) is a great way to teach yourself, and become more self-sufficient as a programmer.

### Phase 2B: Running JavaScript files

In the **phase-one.js** file you created above, you wrote a simple `console.log` statement that will print "Look at me go!" to the console. To run this file, open a window of the Terminal application on your computer and navigate to the **first-project** directory. Once inside the directory, run the code within the **phase-one.js** file by using the following command:

    ~ first-project $ node phase-one.js
    

You should see "Look at me go!" printed to the console.

Congratulations, you've just written and run JavaScript on your computer using both the Node REPL and a **.js** file!