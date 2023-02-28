# Team-Management Creator 
## ``[Work in progress] ``
## Description 
I created this project to practice Test-Driven Development, it is currently still a `work in progress`.

This Team Profile Generator project is a Node.js command-line application taking in information about employees on an engineering team, and generating an HTML webpage that displays summaries for each person. This project requires the creation of Javascript classes for each team member provided and exporting them, ensuring that all the tests for these classes pass. 

Inquirer is used to gather information about these team members, and the render function generates a block of HTML with templated div elements for each employee. The HTML is then written to a file, stored in the output folder. 
### How to use this program 

* Install neccessary dependencies by running `npm install` 

* Once dependencies are installed, you may rum the application with `node index.js` 

* As you input to the inquirer prompts, the application will use classes and methods to generate objects for each team member, and then use the render function to generate an HTML file with the team member information. 

* The HTML file will be written to the output folder, which will be able to be opened in the browser to view the team member information. 

### What I have learnt 

* Utilising Jest to write unit tests for specific functions, classess, and modules within code.
* Using Jest to test different types of inputs and edge cases to ensure my code handles them correctly
* Test-driven development: Writing automated tests before writing the actual code. 
### How to use tests for this program 

* Install Jest "- run npm install --save-dev jest" in the project directory

* Use "npm test" in the terminal to run the tests and you will then be able to analyze the results.  


## Credits 

* https://www.w3resource.com/jest/introduction.php
