# Alpha Testing

## Sneaky Software

## Vision Statement
For people who want to create and play elimination-based live-action mobile games (like Assassin! or Humans Vs. Zombies), the Elimination Framework and API is an web application (and associated mobile apps) that allows for a host to make a game, set rules, and invite other users to join the game. Elimination-based live action games involve players being assigned other players as targets and then proceeding to attempt to eliminate their target/targets, traditionally with mock-projectiles (like Nerf-guns or balled up socks), by whatever rules are established for the specific game, until either the last player/team is remaining. Unlike current methods for playing elimination-based live-action games, our full website will remove the subjectivity that comes from a human moderator and human players determining a successful elimination and also make adding more rules and features (like player skill modifiers, a player inventory, and methods of elimination) to games easier and more fun. The application will store user accounts, skills, and stats from previous and on-going games, as well as make decisions for furthering current games and setting up new ones.

### https://elimination.azurewebsites.net/

### Any other info needed for testing
To test our sight fully, you should
1) Register an account. You'll need a picture with a face.
2) Create a game and/or join a game.
3) Possibly make other accounts to join the game so you can test the target functionality.

Thanks in advance for your feedback!


## William Leingang
__[Notes]__
I am using Chrome for my tests.

__[Presentation]__
When I leave a game that I am a part of, it brings me to a page that says "The resource you are looking for has 
been removed, had its name changed, or is temporarily unavailable." but what I expect it to do it just send me back 
to my profile or something similiar to that.


__[Presentation]__
When I add a file that isn't an image, it doesn't say anything until after I press delete, at which point is says
"Hey! Image only" which is what I would expect it to say the moment I try to upload something that isn't an image. 


__[Defect?]__
When creating an account, I uploaded an image and it got stuck on the "Checking face status...". I'm not sure if this is because
of the image's large size or because there wasn't really a face in it. The image was 3840x2160 and a png.


__[Defect]__
This one is mostly my fault. When creating an account I used '<div style="color:blue">Does this work?</div>' as a username. 
I didn't expect it to accept it, but it actually just sent me to an error page. What I expected it to do was tell me it wasn't a valid username and not create the account. 
On the other hand, since this will only happen if someone is doing this intentionally, it probably isn't a big deal. This is true in pretty much every field.


__[Defect]__
When I press eliminate on a player that is in my game, it tells me it isn't my game. They're not my target, so I was
unsure if it would let me eleminate them, but it IS my game, so the message didn't make much sense to me. Might be
a presentation issue where it should just say something else.


__[Defect]__
If I press "Start game" in my game after it has started, it tells me it isn't my game. I didn't even expect the button to be there
once the game had started.


__[Deficiency]__
When I register for a new account, I can use the same username as someone else, which makes it nearly impossible
to tell the difference between the two. Nothing technically wrong with this, but it can lead to confusion. 


__[Deficiency]__
When editing my account, I was able to put my birthday in the future, but I expected it to stop me like it did when I entered an invalid date. 


__[Presentation]__
When I am on the about page, it says if I have a different question I should feel free to contact you, but gives no contact information.


__[Presentation]__
When I am on the about page, there is a help button that basically brings up the about page over the about page. 