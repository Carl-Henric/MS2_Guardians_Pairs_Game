## Testing

_Code Validators_

All code passed validation tests from the [HTML](https://validator.w3.org/) and [CSS](https://jigsaw.w3.org/css-validator/) validation websites.

[JSHint](https://jshint.com/) was used to validate the JS code. 

All necessary corrections were made to the code following this test, however 1 warning remains:
 - The warning message is as follows: "Expected an assignment or function call and instead saw an expression"
 - This relates to the ternary operator used in my JS code on line 93:
        ```
        function checkCards() { 
        let isMatch = firstCard.dataset.cards === secondCard.dataset.cards;
        isMatch ? cardsMatch() : cardsDontMatch();
        }
        ``` 
 - From searching on google, I found other people have encountered this message from using ternary operators
 - I decided to leave this as is, as the code is functioning as I expect it to, without any problems to the functionality of the website

_Speed_

I used [GT Metrix](https://gtmetrix.com/) to analyse the speed of the website, which gave an overall grade of A.

_User Stories_

Below shows how the user stories have been addressed:

Story: I want the website to be intuitive, so I can get an impression of how the game works from first glance.
* The website design has been kept simple for this reason, to not overwhelm the user.
* The cards are placed centrally on the screen, and are coloured to stand out from the rest of the screen, so you get the impression this is the main area.
* There is a title underneath the heading logo describing the game, which helps the user establish the purpose of the site.
* Any areas which are "clickable" have been styled with a pointer cursor, to visually show the user which areas require user input/action.
* Familiar icons have been used for the help and mute buttons, so the user should recognise what these buttons do just by looking at them	.
* The theme is visually apparent from looking at the logo in the header, and the background image.

Story: I want the game to be visually appealing and well presented.
* Care has been taken to source quality images for the background image, and the character images on the cards.
* Colours used have been picked so they complement each other, there are not any harsh contrasting colours.
* Bootstrap and media queries have been used to place items centrally on the screen.

Story: I want the game to provide a challenge to keep my interest.
* The points system has been included to provide the challenge element, as users will want to see if they can complete the game with a high score.
* A further feature for development in the future would be different difficulty levels. (See 'Features - Left to Implement' for more details)
   
Story: I want the game to include fun, interactive features.
* Different quotes from the Guardians of the Galaxy movie play upon different actions in the game.
* A further feature for development in the future would be using the Marvel API to provide facts on the characters. (See 'Features - Left to Implement' for more details)
    
Story: I want some information available on how to play, if I don’t immediately understand what to do.
* There is a help modal giving simple instructions on how to play, should this be needed.
   
Story: I want the game to be customizable, so I can turn sound effects on or off depending on my preferences.
* There is a mute button, which turns off sound effects.

_Features_

The following details how the various features of the site have been tested for their intended purpose.

Feature | Expected | Testing | Result 
------- | -------- | ------- | ------
POINTER CURSOR | pointer cursor is shown when hovering over clickable elements | tested by hovering mouse over all relevant elements | works as expected
LOGO | expected to be an active link to homepage on clicking | tested by clicking the logo and seeing if page refreshes | works as expected
HELP BUTTON | expected to display help modal on clicking | tested by clicking help button | works as expected
SOUND ON/OFF BUTTON | expected to turn sound effects on/off on clicking | tested by clicking whilst game in play, upon a correct/incorrect match, and game completion | works as expected
CARD FLIPS ON CLICK | card should give impression of flipping over to reveal the front-face image of the card | tested by clicking on all cards, refreshing the page several times | works as expected
GAME LOCKS ON INCORRECT PAIR | if incorrect pair revealed there should be a short time delay before I can click any more cards | tested by attempting to click all unrevealed cards after an incorrect pair revealed | works as expected
CORRECT PAIR OF CARDS STAYS REVEALED | if correct pair revealed these stay revealed i.e. the front-face stays up | tested by attempting to click correct pair of cards after revelaed to see if they flip back over again | works as expected
POINTS ADDED CORRECTLY | the user gets 4 points for a correct pair match and loses 1 point for a mismatch | played game and monitored the points accumulation | works as expected
WIN MODAL APPEARS ON GAME COMPLETION | win modal appears after all pairs correctly matched | tested by completing game several times | works as expected
TOTAL POINTS DISPLAYED ON WIN MODAL TEXT | the number of points won should be part of the win modal text | monitored the text on the win modal to see if points shown are correct | works as expected
PLAY AGAIN BUTTON ON WIN MODAL RESTARTS GAME | clicking the play again button restarts the game | clicked the button to see if game reloads | works as expected
CARDS SHUFFLED ON RESTART | the cards are shuffled each time a new game starts | tested by restarting several times | works as expected
CORRECT SOUND EFFECT PLAYS ON EVENT | the releveant sound effect plays on revealing a correct/incorrect pair or completing the game | tested by listening for correct sound effect playing on all these 3 events | works as expected

_Responsiveness_

I tested the website by changing the screen size on my display, and using the inspect function on developer tools to show how it looks on different devices.

I tested the website on various browsers/devices which were availible to me.

When testing on iPhones, I encountered an issue where the cards were not "flipping" as intended on Safari. I resolved this problem through a combination of:
- Searching on Slack (see credits below): I found out about using [Autoprefixer](https://autoprefixer.github.io/) to check/add necessary code (i.e. webkit) so websites disaply on different browsers.
- Experimenting with changing different CSS stylings on my memory card: I found I had a style applied to the memory card "container" which was overriding the display of the front-face of the card, so I rearranged my code accordingly.

Although the site is intended to be used on all devices, it is recognised that the presentation of the site is better on larger devices. This is noted as a further area for development in the Features section.

_Bugs_

There are some minor issues encountered with the current version of the site:
 - on clicking the mute button for the first time afer loading the website, the image appears to flicker.
 - on changing to a landscape display on iPhones, the memory game section appears to be "pushed" towards the bottom of the screen instead of being centered vertically.

These were not deemed major issues in terms of the functionality of the website, and due to time constraints, were left to be resolved at a later date.