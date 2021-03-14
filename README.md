### The Snake Game
 
## JAVA PROJECT
  * This Website was created for the sole purpose of completing the second Milestone Project for the Code Institute's Full Stack Developer course. It was built using the knowledge gained from the HTML, CSS, User Centric Design, JavaScript Fundamentals and Interactive Frontend Development modules. A full list of technologies used can be found in the technologies section of this document.

# Live project

  The live SnakeGame can be found [View here](https://aquesidilly.github.io/Java-Project)


# Screenshot

  ![](images/snakeGame.png) 


# Table of contents
  * User experience
       - User Stories
          * Snake Game
       - Design
          * Colour Scheme
          * Typography
          * Imagery
       - Features
          * Current Features
          * Future Features
       - Technologies Used
          * Languages Used.
          * Frameworks Libraries and Programs
       - Testing
          * Testing User Stories
          * Code Testing
       - Deployment
          * Github, Gitpod, Git and Gitub pages
       - Credits
          * Code
          * Media
          * Content.
          * Acknowledgements
Table of contents generated with markdown-toc

## Design
 
# Colour Scheme
   *  The two main colours used to create the game are blue colour #hsl, and a yellow colour #hsl representing the snake and food. Other colours were also used for border and background colour between the two main colours to create sections when playing the game .
   *  I also used black colour  for my borders respectively and also cream colour #ccc for my game board to display the snake and the food .

# Typography
   * In built text font was used in creating the snake game from inception to conclusion.

# Imagery
   * No physical images will be used on the site. The snake image will be drawn with code by using Scalable Vector Graphics (SVG) to display this on the HTML page.

## TECHNOLOGIES USED

#  Languages Used.
   * HTML5
   * CSS3
   * JAVASCRIPT

#   Frameworks Libraries and Programs
   * Git 

     - Git was used as a version control in the terminal.
   * Github

     - Github was used to create and store the project repository.
   * Gitpod

     - Gitpod was used to create my files and code the project.
   * jQuery

     - jQuery was imported from bootstrap to make the navbar responsive on smaller screen sizes.
   * Am Reponsive

     - Am responsive was used to make the screenshot or mockup

## Feature

# Current Features
   * Reponsive
     - This is the first responsive snake game which is available  on all screen sizes
     
   * Features
     
   * Existing Features
     - Game Instructions.
     - Snake image.
     - Win/Lose Scores.
     - User input.
     - Snake Game button to start and re-start game.

# Features Left to Implement
     
   * Game modes: 'Easy' or 'Hard' mode will be added in a future release. Easy mode will start with no figure parts displayed, this will leave 10 guesses. Hard mode will start with the snake and the food structure already drawn, this will leave 6 guesses.

# Testing

   * Test Strategy
   * Summary
     - Testing is required on The Snake  JavaScript game created for JS Project . All features and user stories documented in the README are to be tested.

     - HTML code must pass through the W3C HTML Validator.

     - CSS code must pass through the W3C CSS Validator.

     - JavaScript code must pass through the JS Validator.

 # Further Testing
    Once finished I tested the snakeGame across different screen sizes and different browsers.

  * I noticed the heading text was very small and less noticeable on smaller screens so I enlarged its size and added an opaque background to make it stand out more.
  * I also noticed some minor spelling mistakes which I have fixed.
  * I've also checked all links numerous times to make sure they all work.
 # 404 error

  * I used github to add a custom 404 error page if the user enters a wrong url to the page. I created a 404.html page on my repository by clicking the add file button and then added my html,css folder,assets folder and images folder to it. I've added jQuery to this page as well as a link back to the index.html page.
 # Issues and Resolutions to issues found during testing
  
   - The snakeGame had broken lines. This was found when running code through jshint.com and was fixed by removing the space.
   - Clicking the 'Start Game' button to play your first game and when you lose the game will restart automatically, reset functions being used to start the game all over again. This was fixed by hiding the start button after the first game has been played so it could not be pressed.
   - Reference error (404 error) was being displayed on the console if a user tried to input a guess into the text box when a game was not active. This was resolved by setting the You Lose variable to true when declaring it as the game only validates input while the game is active.
   - Replaced code in  form method that gets the input (guess) value to use dotnet notation to fix error shown in jshint validator.
## Deployment

# Github, Gitpod, Git and Gitub pages

   * How to run the project:.

     - I first created a repository cloning the Code Institutes template on my github page.
     - Once created I opened the page in Gitpod.
     - I then used the terminal to create my index.html file ie, touch index.html.
     - I then created my assets folder , to hold snakeGame.js,food.js,input.js,snake.js and matrix.js.
     - I then created the style.css file within the css folder.

   * Git

     - Once I created the main files and folders I then used the git add . command to add them to the staging area.
     - Once they were staged I then used git commit -m "initial commit" to commit them to github.
     - I then used git push to push the files onto my gihub page.
     - I used these steps to commit the project regularly throughout the development to keep everything saved and up to date on my github.
     - To make my project live I then used github pages.

     - Open a workspace in gitpod in my github
     - create a javascript project in my gitpod

# How to play the game
   * Download the game
   * Run it
   * Start playing with the arrow keys. 
   * If you lose, it will restart by it's self so you can continue playing the game 

# Content
   * All content was written by myself.

# Acknowledgements
   * Code Institute for getting me to this point
   * My Mentor for his help with this project.
