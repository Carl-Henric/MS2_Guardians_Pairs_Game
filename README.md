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



## Deployment

The website code was written in Gitpod (IDE). The code was stored in Github (repository).

To deploy the website, under the Github repository, I went to Settings > Github Pages > Chose ‘master’ branch, after which the website was deployed.

You can run the code locally by clicking on the ‘code’ button on my repository, here is the link: [MS2_Guardians_Pairs_Game](https://github.com/upeshp/MS2_Guardians_Pairs_Game)

## Credits

_Tutorials_

I went through the following online tutorials on making a javascript pairs game, working through these tutorials help me better understand the javascript code logic:
 - [scotch.io - Sandra Israel-Ovirih](https://scotch.io/tutorials/how-to-build-a-memory-matching-game-in-javascript)
 - [Code with Ania Kubów](https://www.youtube.com/watch?v=tjyDOHzKN0w)
 - [Memory Game in Vanilla JavaScript - Marina Ferreira](https://marina-ferreira.github.io/tutorials/js/memory-game/)

_Code_

My game is heavily based on the Marina Ferreira tutorial, as I found the presentation of this game appealing, and thought this style would best fit my particular theme:
 - [Memory Game in Vanilla JavaScript - Marina Ferreira](https://marina-ferreira.github.io/tutorials/js/memory-game/)

For the additional features, such as the points system, and the win modal, I found another tutorial, which builds on the above, and adds in these additional features:
 - [Techno Geek](https://www.youtube.com/watch?v=WXv51-Lk438) 

The code in my project has been based on the above two tutorials, and edited for my purposes. 

_Images_

The Guardians logo in the header was from:
 - [Free PNG](https://freepngimg.com)

The background image, and the character images used for the cards, were found from a google image search with creative commons licences. Appropriate credits have been included in the code, and below:
 - [Background image](https://i1.wp.com/voicesfilm.com/wp-content/uploads/2016/10/Guardians-Of-The-Galaxy-Vol.-2-1536-x-2048-700kb.jpg): Image cropped/darkened from original
 - [Gamora](https://i2.wp.com/voicesfilm.com/wp-content/uploads/2016/10/Guardians-Of-The-Galaxy-Vol.-2-1066-x-1500-700kb-2.jpg): Image cropped from original
 - [Rocket](https://i2.wp.com/voicesfilm.com/wp-content/uploads/2016/10/Guardians-Of-The-Galaxy-Vol.-2-1066-x-1500-700kb-3.jpg): Image cropped from original
 - [Groot](https://i1.wp.com/voicesfilm.com/wp-content/uploads/2016/10/Guardians-Of-The-Galaxy-Vol.-2-1066-x-1500-700kb-4.jpg): Image cropped from original
 - [Drax](https://i1.wp.com/voicesfilm.com/wp-content/uploads/2016/10/Guardians-Of-The-Galaxy-Vol.-2-1066-x-1500-700kb-5.jpg): Image cropped from original
 - [Nebula](https://i1.wp.com/voicesfilm.com/wp-content/uploads/2016/10/Guardians-Of-The-Galaxy-Vol.-2-1066-x-1500-700kb-10.jpg): Image cropped from original
 - [Starlord](https://i2.wp.com/voicesfilm.com/wp-content/uploads/2016/10/Guardians-Of-The-Galaxy-Vol.-2-1066-x-1500-700kb.jpg): Image cropped from original

The question mark icon for the help button was from Flaticon. Appropriate credits have been included both in the code, and below:
 - Question mark: Icon made by Roundicons on [flaticon](https://www.flaticon.com/authors/roundicons)

The sound on/off icons for the mute button was from Flaticon. Appropriate credits have been included both in the code, and below:
 - Sound on/off: Icon made by bqlqn on [flaticon](https://www.flaticon.com/authors/bqlqn)

_Sounds_

Sound effects were used from:
 - [movie-sounds.org](https://movie-sounds.org/superhero-movie-sound-clips/quotes-with-sound-clips-from-guardians-of-the-galaxy-2014/)

The following websites/resources were used to add features or resolve issues:
 - Inputting sound effects into website: [Mt. Ford Studios](https://www.youtube.com/watch?v=QHBOOouI1tY)
 - Muting sound using javascript: [W3 Schools](https://www.w3schools.com/tags/tryit.asp?filename=tryhtml5_av_prop_muted)
 - Toggling image on the mute button: [DevelopPHP](http://www.developphp.com/video/JavaScript/Change-CSS-Class-Style-className-Toggle-Tutorial)
 - Inputting a modal to display on click of button: [W3 Schools](https://www.w3schools.com/howto/tryit.asp?filename=tryhow_css_modal) 
 - Using the autoprefixer to add CSS code to make websites function on different browsers, found out about this from searching on Slack: [Autoprefixer](https://autoprefixer.github.io/) 

_Research_

I researched other online character based pairs games, the following in particular helped influence how I wanted to game to look, and the features I wanted to include:
 - [Official Marvel Guardians Pairs Game](https://guardiansofthegalaxy.marvelhq.com/games/guardians-of-the-galaxy-match)
 - [Trolls Pairs Game](http://www.trollsmovie-ph.com/memory/)



--------

