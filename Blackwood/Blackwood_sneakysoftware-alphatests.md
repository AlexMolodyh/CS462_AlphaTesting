# Alpha Testing

## Sneaky Software

## Vision Statement
For people who want to create and play elimination-based live-action mobile games (like Assassin! or Humans Vs. Zombies), 
the Elimination Framework and API is an web application (and associated mobile apps) that allows for a host to make a game, 
set rules, and invite other users to join the game. Elimination-based live action games involve players being assigned other 
players as targets and then proceeding to attempt to eliminate their target/targets, traditionally with mock-projectiles (like 
Nerf-guns or balled up socks), by whatever rules are established for the specific game, until either the last player/team is 
remaining. Unlike current methods for playing elimination-based live-action games, our full website will remove the subjectivity 
that comes from a human moderator and man players determining a successful elimination and also make adding more rules and 
features (like player skill modifiers, a player inventory, and methods of elimination) to games easier and more fun. The application 
will store user accounts, skills, and stats from previous and on-going games, as well as make decisions for furthering current games 
and setting up new ones.

### https://elimination.azurewebsites.net/

### Any other info needed for testing
To test our sight fully, you should
1) Register an account. You'll need a picture with a face.
2) Create a game and/or join a game.
3) Possibly make other accounts to join the game so you can test the target functionality.

## Koll Klienstuber -- Blackwood

__[ShoutOut]__ Landing page looks very clean and understandable to someone first visiting. 

__[Presentation]__ The "help" button on the landing page is pretty small and might be hard to find and or see. In addition "just do it" isn't the most descriptive way to get help and is in place for a few questions. 

__[Recommendation]__ Similar to the above, when visiting "About" some of that information could possibly be updated? But it could also still not be done which if that is the case then can ignore this.

__[ShoutOut]__ Register and login page look very clear and nicely laid out


__[Recommendation]__ Some people might not want to add a picture of their own face, so maybe add in a "sample face button" on the reigster page so people can more easily test out the product.

__[ShoutOut]__ Dashboard looks very nice!

__[Recommendation]__ On the dashboard it might be of value to denote if a feature is under development. Sometimes I'm not sure if it is just slow to load or a feature that just isn't implimented. 



__[Deficiency]__ When I go to https://elimination.azurewebsites.net/Dashboard/UploadFaces and upload a face, I'm not sure what the point is. Similarly I have no way to click the "upload face button"? Not sure what the point of the page is. 


__[Recommendation]__ Finding "create new" on the games page is a bit small. I think it is the only place to create a game so could be of value for some if it was bigger so people know more easily how to create a game.



__[Deficiency]__ When I go to create a game I am able to create a game in the past which seems like something I shouldn't be able to do. 

__[Deficiency]__ When sending Email invites it might be of value to hide the email button after its clicked onces so people can't spam emails by just clicking it a bunch


__[Defect]__ I created a game, and i added every avaibale player to the game then clicked "start game" Then when I go a given persons name I can click "Eliminate" or "remove player", remove player works, but when I click "Eliminate"  i get "Error Sorry not your game" when It is in fact, a game I had just created.

__[Deficiency]__ I have made a game and been added to that same game, but I have no way to know how to eliminate a player / play the game.

## William Leingang -- Blackwood
_[Notes]_
I am using Chrome for my tests.
_[Presentation]_
When I leave a game that I am a part of, it brings me to a page that says "The resource you are looking for has 
been removed, had its name changed, or is temporarily unavailable." but what I expect it to do it just send me back 
to my profile or something similiar to that.
_[Presentation]_
When I add a file that isn't an image, it doesn't say anything until after I press delete, at which point is says
"Hey! Image only" which is what I would expect it to say the moment I try to upload something that isn't an image. 
_[Defect?]_
When creating an account, I uploaded an image and it got stuck on the "Checking face status...". I'm not sure if this is because
of the image's large size or because there wasn't really a face in it. The image was 3840x2160 and a png.
_[Defect]_
This one is mostly my fault. When creating an account I used '<div style="color:blue">Does this work?</div>' as a username. 
I didn't expect it to accept it, but it actually just sent me to an error page. What I expected it to do was tell me it wasn't a valid username and not create the account. 
On the other hand, since this will only happen if someone is doing this intentionally, it probably isn't a big deal.
_[Defect]_
When I press eliminate on a player that is in my game, it tells me it isn't my game. They're not my target, so I was
unsure if it would let me eleminate them, but it IS my game, so the message didn't make much sense to me. Might be
a presentation issue where it should just say something else.
_[Defect]_
If I press "Start game" in my game after it has started, it tells me it isn't my game. I didn't even expect the button to be there
once the game had started.


## Sam Wetzel -- Blackwood

__[Deficiency]__
    1. When submitting a user account.
    2. Register everything as normal. Also, don't meet the requirements for password so it gives you the text to re-enter.
    3. Not only do you have to re-enter your password. You have to re drop in your photo which can be quite redundant.
    4. If this happens, it definitely shouldn't drop the picture.
    5. Find some way to keep that information. It would be helpful to just have the added text to have less password attempts.

__[Deficiency]__
    1. When uploading a picture under user registration.
    2. When I clicked the picture button.
    3. A file upload screen came up, but when using this technique it wouldn't upload.
    4. The picture should upload this way.
    5. It would be more user friendly if you could do it either way.

__[Presentation]__
    1. Under your help page.
    2. Click how do I start a game.
    3. Text says that developer doesn't currently know.
    4. Probably should have instructions here.
    5. I am sure it was just forgotten!

__[Presentation]__
    1. Under your help page.
    2. Click most links on this page.
    3. Most of them feel like filler text for later.
    4. Should be a helpful page to familiarize oneself with a website.
    5. Currently just seems to need a revisit.

__[Presentation]__
    1. Registering an account
    2. Fill out required fields
    3. When completed, if you don't upload a picture it just doesn't let you submit.
    4. Some sort of text that tells you that you can't submit without a profile photo.
    
__[Presentation]__
    1. Registering an account
    2. Password field registration
    3. When filling out the password field we have no input. So without submitting you can't tell the requirements.
    4. Should have text to show requirements to the side.
	5. Just add some information! It can be frustrating to submit multiple times.
	
__[Recommendation]__
    1. Registering an account.
    2. Too much information required.
    3. Entering text in too many spots to be a quick thing
    4. I like quick and easy registration but maybe that is just my preference.
    5. This is just a personal preference, at least when it comes to testing it's kind of a pain to setup multiple accounts this way.

__[Recommendation]__
    1. When clicking the games link while logged in.
    2. If I hover over an active game 
    3. Even though I am logged in, and would like to join a game. The System won't let me join.
    4. Be able to join a game
    5. I might be doing something wrong here. But it would be nice to have better directions in place.

__[Recommendation]__
    1. Logged in.
    2. When clicking the skills link or inventory link.
    3. Nothing happens.
    4. Link takes you somewhere.
    5. I am sure these are just not implemented. But even going to a page that just states that would be better.

__[ShoutOut]__ I really like the color scheme / styling of the website. Props!


__[ShoutOut]__ Logo's on the site look really good for each button when actually logged in.


__[ShoutOut]__ I like the idea of the website, after its fully implemented it could be alot of fun!


## Leo Thalman -- Blackwood

__[Defect]__ Uploading a photo through browse not working.

	Steps to recreate
    1. Went to registration page.
	2. Clicked the Drop Profile Photo text
	3. File browse popped up, selected a photo.

	Actual Result: Nothing loaded.
	Expected Result: Image loads on page.
	
	Tested on Firefox and Chrome.
	
__[Defect]__ Drag and droping a photo through file browse crashes chrome.

	Steps to recreate
    1. Went to registration page.
	2. Clicked the Drop Profile Photo text
	3. File browse popped up, dragged a photo from file browse to web page.
	4. Web page loaded photo, clicked registration

	Actual Result: Webpage crashes
	Expected Result: Successful registration.
	
	Tested on Chrome, firefox doesn't allow you to drag the photo over.

__[Defect]__ Photo Elimination not working

	Steps to recreate
    1. Created a game
	2. Invited a second test account to game
	3. Started the game
	4. Tried eliminating myself via photo elimination using same photo as profile.
	
	Actual Result: page just sits at Checking face...
	Expected Result: A sucessful elimination or a warning not to use the same picture.
	
	Tested on Firefox and Chrome.
	
__[Defect]__ Photo uploading not working on mobile

	Steps to recreate
    1. Loaded website with Safari browser on iPhone
	2. Went to registration page
	3. Filled out registration information.
	4. Clicked the drop profile photo text and a menu loaded asking if I wanted to take a photo or to select a photo from the library or browse.
	
	Actual Result: Nothing happens wh-en you do take a photo or photo from the library. Didn't have anything on the iCloud drive so I couldn't test browse, also doesn't work for image elimination.
	Expected Result: Loads the photo.
	
	Tested on Safari iPhone.
	

__[Deficiency]__ End date before start date
	
	Steps to recreate
    1. Created a game with a start date of 	10/11/1908 12:00:00 AM
    2. Set the end date to be 10/11/1907 12:00:00 AM
	3. Saved the dates
	
	Actual Result: Edit saved the dates fine
	Expected Result: Page throws an error, not allowing the end date to be before the start date or have the end date be in the past.
	
	Tested on Firefox and Chrome.
	
__[Deficiency]__ Start game after start and end dates
	
	Steps to recreate
    1. Created a game with a start date of 	10/11/1908 12:00:00 AM
    2. Set the end date to be 10/11/1907 12:00:00 AM
	3. Invited a second test account to game
	4. Started the game
	
	Actual Result: Game started up fine, and still allowed me to play.
	Expected Result: Game starts up and then ends as it's after the start date, and doesn't allow me to play.
	
	
__[Deficiency]__ Game of one player assigns yourself as the target
	
	Steps to recreate
    1. Created a game
	2. Invited a second test account to game
	3. Started the game
	
	Actual Result: Game started up and assigned myself as the target.
	Expected Result: Game to end as there is only one player.
	
	Tested on Firefox and Chrome.
	
__[Deficiency]__ Clicking details page of a hosted game loads normal details, not host details
	
	Steps to recreate
    1. Created a game
	2. Went to Join a game page
	3. Clicked the details button of my hosted game
	
	Actual Result: Loaded the player details page.
	Expected Result: Loads the host's details page.
	
	Tested on Firefox and Chrome.
	
__[Deficiency]__ Starting a game that has already started gives an error
	
	Steps to recreate
    1. Created a game.
	2. Invited a test account to game.
	3. Started game from the dashboard.
	4. Went to host details.
	5. Clicked the start game button.
	
	
	Actual Result: Gives an error saying this is not your game.
	Expected Result: An error saying game is already started, or take the button away if the games is active.
	
	Tested on Firefox and Chrome.	
	
__[Deficiency]__ Target eliminated appears when game starts
	
	Steps to recreate
    1. Created a game
	2. Invited a second test account to game
	3. Started the game
	4. Eliminated myself in the game via manual elimination.
	5. Game ended, then created another game and invited the same test account.
	6. Started the game.
	
	Actual Result: Game started up and assigned myself as target, and Target Eliminated! appeared below my Target picture
	Expected Result: Game starts up and assigns me my target.
	
	Tested on Firefox and Chrome.
	
	
__[Presentation]__ Badges page has some broken image links
	The images for the follow badges are broken links
	1. InvitedToGameBadge
	2. FriendRequestBadge
	3. EliminateSamePlayer-1-Badge
	4. FirstBlood
	
	Tested on Firefox and Chrome.

__[Presentation]__ Register button overlaps image
	When registering if you shrink the browser so that the input boxes stack vertically, 
	when you upload an image the register button overlaps the bottom left corner of the image.
	
	Tested on Firefox and Chrome.
	
__[Recommendation]__ Move the help button to the nav bar
	Since your Nav bar is fairly empty, moving the help button up there would make it easier to find.
	Making it a button could also work, having it be small red text in the bottom corner made it hard to find.
	
__[ShoutOut]__ The logos and color scheme give the website a really polished look.

__[ShoutOut]__ Badges are a nice touch, makes it feel like a real game.
	
	
	
	