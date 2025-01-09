# JS-Chapter4
JavaScript Chapter 4 Programming Assignment

In this project you have been given a program that generates a random Jane Austen quote each time a page reloads. The application calls the following function to generate a random integer used in picking the quote from an array of quotes:

randomInt(lowest,highest)

where lowest is the lowest integer in the range and highest is the highest integer. Thus, the statement

randomInt(0,5)

will generate a randomly selected integer from 0 up to 5 (including both 0 and 5). However, there are several bugs in the application that need to be fixed before the page will work properly. Figure 4-31 shows a preview of the page with a randomly selected quote.

![image](https://github.com/user-attachments/assets/06889929-57ab-45a7-bcd0-c6a7e8337fa3)
Figure 4-31

Do the following:

Use your code editor to open the index.html and script.js files. Enter your name and the date in the comment section of each file and commit your changes.

Go to the index.html file in your code editor and in the head section add a script element to load the script.js file, deferring the loading of the JavaScript source file until the entire HTML file is loaded. Study the contents of the HTML file and save your changes.

Go to the script.js file in your code editor. At the top of the file insert a command to have the JavaScript interpreter parse the code using strict standards.

Commit your changes to the file and then load index.html in your browser.

Use the debugger to locate the syntax and runtime errors within the document. Fix the errors using your code editor.

Once you have fixed the syntax and runtime errors, continually reload the web page. Each time the page is loaded, a Jane Austen quote is randomly selected from the array. Occasionally, an undefined value appears where the quote should be. Find the source of this logic error by setting a breakpoint at Line 48 and watch the values of the randomQuote and quotes[randomQuote] expression. What are their values that result in an undefined quote?

Return to the code editor and fix the program to remove the logic error. (Hint: What is the largest index in the quotes array and what would happen if you tried to retrieve an entry larger that index?)

Return to the index.html file in your browser and continually reload it to verify that the undefined quote no longer appears.
