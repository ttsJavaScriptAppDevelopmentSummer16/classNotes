## Class 1 - Intro, Variables and Control Flow

###**Due 7/21/2016:**

1. Read the following tutorial [JavaScript Strings](http://www.javascriptkit.com/javatutors/string4.shtml) 
	2. follow the code samples in Node 
2. Join our Slack Channel (javascript_summer16)
3. Send me your GitHub username

*note:<br>when naming your GitHub repo, please use the following naming convention:
`rps_aw_lm`<br>(the project name + your team's initials)*


###**Due 7/26/2016:**

4. Work with your partner to create a game of 'Rock Paper Scissors' that runs until one player has three wins

	- Store the player names and number of wins for each player in variables
	- Use a while loop to run the game until one player has 3 wins
	- Use: 
	  ```
	  var weapons = ['rock' , 'paper', 'scissors'];
		
	  var weaponOfChoice = weapons[parseInt(Math.random()*weapons.length) %3];
	 ``` 
	  to randomly select an item
	- Output each players hand to the console
	- Use an `if` or `switch` statement to determine a winner of the round
	- Output the round winner's name to the console
	- Create a way to track how many rounds each player has won
	- When one player wins 3 rounds, announce that player's name as the game winner
	- Push the code to our class GitHub Repo
	- See below for all possible winning outcomes
	
	  <center>![](images/rockpaper_web.jpg)</center>
