## Milestone 2 – Guardians Pairs Game

I am designing a website with a javascript pairs game, with a Guardians of the Galaxy theme. 



## UX

_Overview_

The aim of the project is to provide a simple, fun, interactive pairs game, for users of all ages to enjoy. The game will have a ‘Guardians of the Galaxy’ theme, the game will be designed to appeal to fans of the comic or films! 
The game is designed to be suitable for use on all devices, from desktop to mobile. 
The game will operate in a similar way to most pairs/memory games, where the user will click on two cards to see the images underneath. If the two images match, the user has successfully matched a pair, and the cards will remain revealed, however if there is no match, the cards will flip back over. The aim of the game is to match all cards, at which point the game is complete.

_User Stories_

   *	I want the website to be intuitive, so I can get an impression of how the game works from first glance.
   *	I want the game to be visually appealing and well presented.
   *	I want the game to provide a challenge to keep my interest.
   *	I want the game to include fun, interactive features.
   *	I want some information available on how to play, if I don’t immediately understand what to do.
   *	I want the game to be customizable, so I can turn sound effects on or off depending on my preferences.
	
_5 S's_

**Strategy** 

The primary goal is to provide a simple, fun, interactive pairs game, for users of all ages to enjoy. 

**Scope** 

The overall look and feel of the website was influenced by researching other character based online pairs games (credits at end) [https://guardiansofthegalaxy.marvelhq.com/games/guardians-of-the-galaxy-match] [http://www.trollsmovie-ph.com/memory/] :
-	These are simple in design, the main focus is on the game area, which contains the cards – these are usually styled in a way to make them stand out from the rest of the site.
-	Character images are used throughout the page to reinforce the theme, for example on the back of the cards, or as a background image.
-	There are some brief simple instructions for the user to understand how to play the game. 
-	There is a familiar soundtrack and/or sound effects used in the game, which tie-in to the theme of the game, which can be muted on the click of an icon.
- 	There is usually an element of challenge, typically the game advances in difficulty by increasing the number of cards to match.
-	There is a congratulatory popup modal on completion of the game.

With this in mind, my website will include:
- 	One simple page which contains the game area (i.e. the cards).
-	A suitable background image, which draws upon the theme, which will be familiar to fans of Guardians of the Galaxy.
-	A help button, which will open a popup modal containing some quick instructions on how to play the game. A modal will be used to keep the design clean and simple, and reduce real-estate on the screen.
-	Sound effects which come in to effect when playing the game.
-	A mute button for the sound effects.
-	A points system will be used in this game, with each correct match scoring 4 points, but an incorrect match losing 1 point (This will be used to provide the “challenge” to the user, as the user may try to complete the game earning the most points possible).
-	A congratulatory popup modal, displayed on completion of the game.

**Structure** 

In line with the features identified in the scope section, the website will be structured as follows:

1.	Logo/Title:

	-	The top of the page will contain a Guardians of the Galaxy logo, to make the theme clear to the user.
	-	Underneath the logo will be a title “Pairs Game” to make the purpose of the site clear to the user.
  
2.	Buttons:

	-	The page will contain two buttons, the help button, and the mute button, these will be positioned below the title. 
	-	Icons will be used for these buttons using familiar images, to make these intuitive.
	-	These are positioned towards the top of the page, as the user may wish to use these before commencing the game.

3.	Game Area:
	
	-	The game area with the cards will displayed below the above items. These will be positioned centrally in the screen, and will take up the most space on the screen, in line with the design principles found from my research on other similar websites.
	-	These will also be formatted in a way to make the cards stand out from the background, to make it clear to users that these are the cards which need to be “clicked”.

4. 	Responsiveness:
	-	The game is designed to be responsive and suitable for play on all devices, so bootstrap and CSS media queries will be used to structure/design the game.
	-	Essentially the game structure will remain the same on all formats, however the elements will scale down for smaller screens.


**Skeleton** 

[Wireframes](https://github.com/upeshp/MS2_Guardians_Pairs_Game/tree/master/assets/docs/wireframe)


**Surface** 

-	The colour scheme will tie into the theme.
-	The main colours used will come from the Guardians of The Galaxy logo (i.e. the same logo used at the top of the homepage) – these will be purple, yellow, and grey. These are also suitable for use as they tie into the space or galaxy theme.
-	The background image will be a simple image, with no overbearing features, so not to distract or overwhelm the user, ideally with grey or dark colours.
-	The cards will be formatted in a colour to make them stand out from the rest of the site, such as purple or yellow.
-	I wanted the fonts used to give a comic feel, given the theme of the site, but also be clear to read for all users. After examining various Google fonts, I decided on Marvel, as I thought this gave a compromise between the two.
-	As mentioned above, all elements on the page will reduce in scale on smaller screens, for presentation and good user experience.

## Features

_Existing_

- 	Main logo serves as a link to homepage
- 	Cursor changes to a pointer on items where clicking is required to activate a function
- 	Modal appears on clicking the question mark icon giving instructions on how to play the game
-	Clicking the sound icon toggles the sound effects being on or off
- 	Game section:
	- 	cards are "shuffled" each time the game is loaded/restarted
	-	cards appear to "shrink" when clicked giving 3D effect
	-	cards "flip over" when clicked 
	-	image "underneath" the card is revealed when clicked
	- 	cards return to original state if there no matched pair 
	- 	cards remain revealed if there is a matched pair
	- 	the points counter increases by 4 for a matched pair
	- 	the points counter reduces by 1 for an incorrect pair
	-	different sound effects play on the event of a matched pair/incorrect match/game completion
	-	a win modal appears on game completion showing the final score
	-	the win modal has a button to "play again" i.e. restart the game


_Left to Implement_

The following features were considered during the build of the site, however due to time constraints, these were not included in this version, but could be added at a later date:

- 	Increasing difficulty levels for the game, giving increasing numbers of cards to match (omitted as diffcult to source enough quality character images to use for an increasing number of cards)
-	Using Marvel API to include info such as character bio's

## Technologies Used

- 	HTML5
-	CSS3
-	Javascript
-	Bootstrap 4.5.2
-	Gitpod
-	Github

## Testing
