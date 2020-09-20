## Testing

The testing process is outlined below. It includes:
- Testing User Stories
- Validating HTML, CSS and JavaScript code
- Checking website compatibility on different browsers
- Checking responsiveness of design on all screen sizes
- Manually testing the functionality of all links
- Manually testing the Bootstrap 4 MODEL


To return to the previous document, click [here](https://github.com/YOSTINA-dh/Ge-ez-Memory-Game/blob/master/README.md.

### Testing User Stories

These following tests were conducted to test the experience of each user outlined earlier.

#### Project stakeholders

The creators of this game want a consistent and encouraging design to inspire users to be more excited than intimidated by the subject;The creators of this game want a consistent and encouraging design to inspire users to be more excited than intimidated by the subject; Playing Geez numbers and scripts can be daunting to think about at first. This is achieved through a consistent design of the log, the background image on the first page, constant use of powerful colors, and encourages the user to move on to the next page.
The creators could feel confident and optimistic that the user experience would allow them to go further and learn more about the numbers and enjoy playing, thereby increasing the number of players and meeting their aims.

#### New users

*User (who is new to the concept of Geez memory Game ):*
 - Since this user was reasonably new to the concept of Geez memory game, they would come to this site to learn more and play an exciting game. Clicking their playing button leads to the next journey through the site:
  * Home: The user would use the arrows to scroll down the website before starting the game and see the logo of the page and copyright. 
  * 'A game': Arriving here, Users start by clicking on the cards. Once the user has started to play, the timer can count. 
-  The second thing to do to click on another card flips it. 2 flips of the card = 1 move. If the cards match, both cards stay flipped over, and If the cards do not check, both cards flipped back. 
-  The user can hit the new game button to restart the game at any time or can pause and start whenever the user wants to play. Users can play with the fail and success sounds or without the sound. At the bottom of the cards, they can click on the "click to read" bottom and learn more about the numbers and scripts of Geez to learn more (which we assume they do now).
-  This user would leave a positive experience; they probably know more now than before.

  
*User two (who wants to Play a Game):*
- As this user might already know the basics about the Geez Memory game, their main aim is to play a memory game. To do so, they could either:
  * Use the play button to go immediately the game page 
- You will start by flipping over one card
- If the next card you flip matches, a pop-up alert notifies you, and you get +1 to your score
- These cards stay flipped over
- If the next card you convert does not match, a pop-up alert notifies you of this, and the cards flip back
- The game continues until you check all the cards on the board
*At the bottom of the cards, they can click on the "click to read" bottom and learn more about the ancient numbers and scripts of Geez, which can be interesting to know old Ethiopians number. 

### Validating the HTML, CSS and JavaScript code

#### HTML
My HTML code was passed through the [W3C Markup Validation Service](https://validator.w3.org/).
Doing so brought up the errors below that I resolved in the following ways:
 - *index.html* - The first section of my 'Home' page was missing an div close tag, so I add a closed </div> tag to correct this. 
 - *Game.html* - Have an error with the bootstrap four modal and tried to fix but its change the whole structure of the game.
 
 #### CSS
I checked my CSS code with the [W3C Markup Validation Service](https://jigsaw.w3.org/css-validator/). 
This test did not produce any errors.

#### JavaScript
I used [JSHint](https://jigsaw.w3.org/css-validator/) to check my JavaScript files.
This brought up the following errors with the steps I took to correct them:
- *All JavaScript files* - The validator showed me that I had placed my local JavaScript tags at the end of my code outside of the `</body>` tag. I corrected this subsequently in each file.
- *index.js* - I was alerted to the fact that I was missing three semicolons in my code, as seen in the screenshot below. I corrected this by adding semicolons accordingly.
 
 ### Testing compatibility with different browsers

 I manually tested the website on the following web browsers, checking that buttons, responsiveness and design worked as planned:
- Google Chrome 
- Mozilla Firefox 
- Apple Safari


### Testing the design's responsiveness on several screen sizes
I manually tested the design of the live project by doing the following:
- Using Google Developer Tools to view the project on devices with different screen sizes.
- Checking the sound and cards feature still worked as planned on smaller devices.
- Asking for feedback from friends and family who opened and interacted with the project on their devices.


### Manually testing the functionality of all links
The following tests were made to see that all links responded as they should:
- Social media links were clicked on to ensure they open in a new tab at the correct corresponding landing page.
- Cards were clicked on from each of them to make sure that they can flip and correctly shown as 'active' when selected.
- New game buttons were clicked on to start to take the user to the new refresh game.
- The time counter button checked to ensure that they count correctly.
- The pause button checked if they work correctly
- The 'Back' button in the toper on the left side successfully work the user can back to the home page.
- Each button on all pages was clicked to ensure that they work correctly and were actively connected. 

#### Results and changes`
Once I began working on this project, I continued testing as I developed the Game page . This led to the following changes, corrections, and observations:
- I realised I would need to include a won messages to the user depending on their score, either congratulating them or encouraging them to try again. I therefore changed the `if` statement for my function to check the user's results and alter the message accordingly.
- I also realized I had to add a sound if the user would like to play with a soundtrack, especially kids; therefore, I add a sound button statement to include all kinds of players

[Return to previous document here](https://github.com/YOSTINA-dh/Ge-ez-Memory-Game/blob/master/README.md).