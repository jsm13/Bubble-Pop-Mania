
# Project Overview

## Project Schedule

This schedule will be used to keep track of your progress throughout the week and align with our expectations.  

|  Day | Deliverable | 
|---|---| 
|Day 1: Tue| Wireframes and Priority Matrix|
|Day 2: Wed| Project Approval /  Pseudocode / actual code|
|Day 3: Thur| Basic Clickable Model |
|Day 4: Fri| Working Prototype |
|Day 5: Sat| Final Working Project |
|Day 6: Sun| Bugs / Stylying / PostMVP |
|Day 7: Mon| Project Presentations |


## Project Description

Use this section to describe your final project and perhaps any links to relevant sites that help convey the concept and\or functionality.

This game is a point and click game called Bubble Pop Mania.  The idea is to click the bubbles to clear the screen.  The bubbles change in each level, ending as meteors attaching the Earth in the 3rd round.

## Wireframes

Include images of your wireframes. (DONE)
## Priority Matrix

Include a full list of features that have been prioritized based on the `Time and Importance` Matix.  

## Game Components

### Landing Page
1. Welcome greeting, with background of bubbles.
2. Instructions: "Enter 3 initials, then press START to play."
3. Start button


### Game Initialization
What will a player see when the game is started? 
1. Level I screen: Floating(or drifting bubbles) all same color.(possible animated bottom half of screen - pulsating or glowing.)
2. Timer, Score box, Level counter and Player's Initials at top of page

### Playing The Game
What will be the flow of the game, what will the user be expeted to do and what will the user expect from the game.
1. Level I: The user will be expected to clear the board before the timer expires. If successfully, the user can advance to Level 2. If I don't have time to make Level 2, the user will see a final score and congratulatory statement such as You Won!
2. Level II. The user will be expected to only pop the noncolored bubbles.  Colored bubbles are toxic and clicking one will cause the screen to get inked (turning into that color) and the user to lose a life value.  The user is given 3 life values.
3. Level III. The user will be expected to click and destroy all falling meteors to save the earth.  Gif meteors will fall at different speeds.  If one hits earth, game over!

### Winning The Game
What does it look like when the game ends, what determines winning or losing?
Winners see a congratulations statement, losers see something like Sorry, you lost, thanks for Playing.  Both will include final scores and a reset button.
### Game Reset
How will the user restart the game once it has been completed.
By pressing the reset button on the end of game page.
## MVP 

Include the full list of features that will be part of your MVP 
Barebones would include: Landing page, Level 1, End of Game Page.
## POST MVP
POST MVP - Levels 2 and 3.

Include the full list of features that you are considering for POST MVP
## Functional Components
animated gifs, determination if a gif hits Earth.  Replacement pic when gif is clicked (destroyed).
Detection for when all meteors are removed.
Based on the initial logic defined in the previous game phases section try and breakdown the logic further into functional components, and by that we mean functions.  Does your logic indicate that code could be encapsulated for the purpose of reusablility.  Once a function has been defined it can then be incorporated into a class as a method. 

Time frames are also key in the development cycle.  You have limited time to code all phases of the game.  Your estimates can then be used to evalute game possibilities based on time needed and the actual time you have before game must be submitted. 

| Component | Priority | Estimated Time | Time Invetsted | Actual Time |
| --- | :---: |  :---: | :---: | :---: |
| Component 1 | H | 40 hrs| 40hrs | 0 hrs |
| Total | H | 40hrs| 0hrs | 0hrs |

Form    H   10hrs   8hrs    8hrs
Landing Page and First Game Level | H | Page shell design | 2hrs
Animated bubbles for First Level H | 5 hrs
Bubble Counting/Score tracker and Timer | H | 5 hrs
Animation of bottom of screen | L | 3 hours
JQuery Point and Click functionality |  H  | 10 hrs   
Creation of Divs and classes  |  H  | 1 hrs
Bubble State Toggle to Popped  | H  | 5 hrs
Addition of Audio sound for Popped Bubble State H | 2 hrs   
Creation of Transition Pages |  L | 5hrs 
Creation of Transition Animation | L | 3 hrs
Creation of Level 2 | L | 3 hrs
Creation of Level 3 | L | 3 hrs

## Helper Functions
Helper functions should be generic enought that they can be reused in other applications. Use this section to document all helper functions that fall into this category.

| Function | Description | 
| --- | :---: |  
| Capitalize | This will capitalize the first letter in a string | 

## Additional Libraries
 Use this section to list all supporting libraries and thier role in the project. 

## Code Snippet

Use this section to include a brief code snippet of functionality that you are proud of an a brief description.  

## jQuery Discoveries
 Use this section to list some, but not all, of the jQuery methods and\or functionality discovered while working on this project.

## Change Log
 Use this section to document what changes were made and the reasoning behind those changes.  

## Issues and Resolutions
 Use this section to list of all major issues encountered and their resolution.

#### SAMPLE.....
**ERROR**: app.js:34 Uncaught SyntaxError: Unexpected identifier                                
**RESOLUTION**: Missing comma after first object in sources {} object
