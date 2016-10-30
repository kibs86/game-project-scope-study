# Game Project Scope Study

## Required Readings

-   [Game Project](https://github.com/ga-wdi-boston/game-project)
-   [Game API](https://github.com/ga-wdi-boston/game-project-api)
-   [What is a User Story](https://www.mountaingoatsoftware.com/agile/user-stories)

## Deliverables

After reading the `game-project` prompt and the `game-project-api` documentation
please do the following and be prepared to share and discuss during our next
class.

Submit detailed answers to the following in this file via a pull request:

-   A wireframe of what your game project will look like.
-   The data structure you plan to use.
-   How you will take the markup of the game board and represent it in JS
-   How you plan to approach this project.
-   4-8 user stories for your game project.
-   How you plan to keep your code modular.
-   What creative spin will you add to your project?
-   How will you use version control to backup / track your project?
-   Do you plan to attempt any of the bonuses?

You may want to submit pictures for your wireframes and/or user stories.
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
has instructions to link to a picture you've uploaded to a service like [Imgur]
(http://imgur.com/).

## Responses

### A wireframe of what your game project will look like.
Web images:
![alt text](http://imgur.com/UepNPW9 "Tic Tac Toe Web Page 1")
![alt text](http://imgur.com/21dwbm2 "Tic Tac Toe Web Page 2")

Mobile image:
![alt text](http://imgur.com/YyMZ14x "Tic Tac Toe Mobile")

### The data structure you plan to use.
I was originally thinking of mapping the board coordinates to an object so I could
store both the coordinates and whether it was "owned" by player X or O in the same
place, but I think I may try to keep it simpler by using a simple array if I can.

### How you will take the markup of the game board and represent it in JS
I might be misunderstanding either this question or the one above, but they seem
to be asking the same thing just in a different way.  I'm going to try to keep it
simple by mapping X or O to a certain index within an array to keep it the same as
what the API is expecting to see when a game is updated.

### How you plan to approach this project.
My plan is:
1. Read through the game requirements and try to make a list of the different features/test cases.
2. Read through the API and try to map out how the calls/interactions to the back end will work.
3. Take the above two steps and use them to help build a high-level plan for how to implement my code.
4. Turn that high-level plan into pseudo-code.
5. Work one feature/level at a time to translate that pseudo-code into something functional.
6. Set myself a schedule to try and have certain components done by certain times.

My primary plan is to use the advice given to us multiple times so far and try to work on
solving one small problem at a time instead of getting overwhelmed by the full picture.

### 4-8 user stories for your game project.
As a developer, I want modular code so I can keep things better organized and updated.
As a user, I want a game that allows me to create an account so I can see my game statistics.
As a user, I want to be able to change my password so I can keep my account more secure.
As an instructor, I want to see code that is readable so I can understand how the app is functioning.

### How you plan to keep your code modular.
I'm planning on following the DRY principle to help keep things modular, along with
making use of the templates we're provided and have used in our trainings to separate
certain components.

### What creative spin will you add to your project?
The Walking Dead is one of my favorite shows so given that, and the spirit of
the season, I'd like to do a zombie spin on mine.  The icons will be a zombie and
a cartoon Rick Grimes instead of the normal X and O.  I'll also be trying to use
zombie-ish fonts and color schemes.

### How will you use version control to backup / track your project?
I'll be using git for version control and project tracking.  I plan to create
branches for HTML, CSS, JavaScript, Ajax, etc.  I may also decide to do feature
branches as well, but I'm not completely sure yet.  I'll make sure to run saves
and commits frequently and only merge once I know my code is looking/working the
way I want it to.

### Do you plan to attempt any of the bonuses?
Not at this time.  I plan to focus on making sure my game meets all of the
requirements first and if I have time left over (big if) then I'll look at the
bonuses.
