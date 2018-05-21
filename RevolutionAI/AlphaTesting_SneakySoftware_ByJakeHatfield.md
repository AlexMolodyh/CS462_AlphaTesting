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

## Jake Hatfield

__[ShoutOut]__ The site looks very modern and cool. It is very inviting. Definitely something I want to try.

__[ShoutOut]__ From the start, it is very clear that I either need to register or login to enjoy the site. There is an info page that I can check out without loggin in.

__[Deficiency]__ The info page before logging in, https://elimination.azurewebsites.net/Home/About, contains outdated information such as, "How do I join a game?" with the answer being "I'm not entirely sure at this point, because another developer is working on that!". I think you know what you need to do here. Others, such as "How do I assassinate my target?" should also be updated so they are understandable and appealing. I know this is a game, but the answer to that question is pretty open ended.

__[Recommendation]__ It should be noted somewhere that this game is not meant to inflict harm on others as __HUGE DISCLAIMER!!!__ It is a game of cunning and skill and no animals were harmed in conducting this test.

__[Recommendation]__ The friends list is cool, but after knowing that anyone can see my phone number after I have registered is a red flag. Would you mind removing my phone number from you database? Or you could allow the phone numbers to be updated on the "Edit Player" page. *UPDATE* I found the edit phone number after clicking the cogs for "Account Settings". That was kind of hidden and I didn't know what it was for. I don't know if you could or should combine the two pages because they seem to be associated with the same person/profile, but nonetheless, the cogs was kind of hidden and I didn't know what it was for.

__[Deficiency]__ On my dashboard, when I click on "Inventory", nothing happens. I expect something to happen. Not sure what, but something.

__[ShoutOut]__ The badges are cool and a fun feature to include.

__[Recommendation]__ Showing a list of the badge names might be a cool feature. You could include the description if you want or just show the badge as a hidden achievement. This will give players incentive to accomplish things. Say you have badge for eliminating the same player 10 times. This would give a player the incentive of playing with the same group. Another badge for eliminating 10 different players gives the player the incentive of playing with other people.

__[Deficiency]__ After adding almost all the people to one of my games, I quickly realized I didn't know who they were or what they looked like. This would make it hard to or impossible to play with them. I know displaying an image isn't the best course of action since that is how you elimate people, but maybe a stock photo. Maybe there could be a requirement for a green background for uploading the initial photo. Then when the elimination photo is checked, if it has a green background, it could be flagged for review by an admin or something else along those lines.

__[ShoutOut]__ No one wants to be my friend :(.

__[Defect]__
1. Setup: I have an account. I created a game. On the "Dashboard", I click on the link of my "Hosted Games". From the "Details" page, I attempt to start the game before the start date/time.
2. Replication: I replicated it by refreshing the page and clicking on it again.
3. Actual result: I was directed to an Error page: "Error Sorry not your game".
4. Expected result: I thought it would start the game, or tell me it was before the start date. Not throw an error.
5. Remarks: After I added players and sent email invites, it stopped saying it wasn't my game. I received the same error again after I tried to elimate someone from my game though.

__[ShoutOut]__ The custom Error page looks cool and has the same styling as the rest of the pages.

__[Deficiency]__ I was able to spam the send invite buttons, specifically the Email Invites. Whether or not it actaully sent emails is unknown and I am thankful I used a fake email/phone number. Is there a check to see how many emails I have sent? Also, there is no way for me tell if the emails were actually sent other than looking at the console log. I would suggest after the button is pressed, have it change colors and disable it so it can't be pressed again. Disable it and restore the colors when the update players button is pressed, or better yet, if a new player was added (requires more logic/work).

__[Deficiency]__ I couldn't tell if the TXT Invites worked. While looking at the console, it spit out a 500 error. I was hoping to see a confirmation that they were (or weren't) sent.

__[Deficiency]__ I was hoping to be able to remove a player that I accidently added to the game. I tried to remove the checkbox next to their name and update players, but it didn't appear to do anything and it gave a 500 error in the console.

__[Defect]__ 
1. Setup: I have an account. I joined a game. After joining, on the "Details" page, I clicked on "Leave Game". I clicked "Yes" on the alert to leave the game.
2. Replication: I replicated it by joining another game and leaving that game.
3. Actual result: At https://elimination.azurewebsites.net/Games/HostDetails/10, I received the error: "The resource you are looking for has been removed, had its name changed, or is temporarily unavailable.".
4. Expected result: I thought it would redirect me to my dashboard. Not tell me the resource was unavailable.
5. Remarks: I think if you redirect to the dashboard, or anywhere valid after a player leaves a game, that should fix this error.

__[ShoutOut]__ Love the site and wish I had some friends to play with.
