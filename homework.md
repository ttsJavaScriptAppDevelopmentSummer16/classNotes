## Class 1 - Intro, Variables and Control Flow

###**Due 7/21/2016:**

1. Read the following tutorial [JavaScript Strings](http://www.javascriptkit.com/javatutors/string4.shtml) 
	2. follow the code samples in Node 
2. Join our Slack Channel (javascript_summer16)
3. Send me your GitHub username

	*note:<br>when naming your GitHub repo, please use the following naming convention: `rps_aw_lm`<br>(the project name + your team's initials)*


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

- - - -

## Class 2 - Data Structures - Arrays and Objects

###**Due 7/26/2016**

1. Complete the following class challenges
  - [Exercise 1](https://github.com/ttsJavaScriptAppDevelopmentSummer16/classNotes/blob/master/Lesson%2002%20-%20Data%20Structures%20-%20Arrays%20&%20Objects.md#exercise-1)
  - [Exercise 2](https://github.com/ttsJavaScriptAppDevelopmentSummer16/classNotes/blob/master/Lesson%2002%20-%20Data%20Structures%20-%20Arrays%20%26%20Objects.md#exercise-addressing-objects)
  - push the completed code to GitHub
  - use the naming convention `lesson_2_challenges_YOUR_INITIALS_HERE`

2. Create an object that models the data of your favorite email application. 

  - Open the email application and take a look at the interface.
  - What information do you see? Make a short list (e.g. emails, my name, mailbox list, an email preview...) 
  - Make a detailed outline of the data hierarchy. E.g -
  	- Gmail
  		- mailboxes
  			- inbox
  			- starred
  			- sent
  		- Chat Contacts
  			-  Shane
  			-  Eric
  			-  Katy
  		- Emails
   		
  - For each bullet in your outline, decide if it is a primative, array, or object.
  - Use this information to create an object literal that models the application's data. E.g. -
  
    ```javascript
    var appData = {
    	name: 'Gmail',
    	mailboxes: [
    		'inbox',
    		'starred',
    		'sent',
    	],
    	contacts: [
    		{name: 'Shane', lastMessage: "I wont be in class today"},
    		{name: 'Katy', lastMessage: "You're such a nerd"}
    	]
    	
    	//...
    }
    ```
  
  Add as much detail as you'd like. Experiment and have fun with it. Nest objects inside of arrays and arrays inside of objects multiple levels deep. Ask yourself if some of the primatives you've created could be objects instead.
  
3. Once you've composed your object, write some code to address it.
  
  - Get a list of inbox names
  - Get a list of emails
  - Get the text of the second email in the visible list
  - Mark an email as sent
  - Add a draft email to the drafts mailbox
  - etc. etc. etc.
  
4. push the completed code to our GitHub channel
  - use the naming convention `email_app_YOUR_INITIALS_HERE`
  
- - - -

## Class 3 - Functions - Part 1

###**Due 7/28/2016**
- Complete the new [Rock Paper Scissors Challenge](https://github.com/ttsJavaScriptAppDevelopmentSummer16/classNotes/blob/master/lesson%2003%20-%20Functions%20-%20Part%201.md#exercise-2-rps-revisited)
  - Push completed to GitHub with the name: `RPS_functions_YOUR_INITIALS_HERE`

###**Due 8/2/2016**
-  Complete the [JavaScripting Module](https://github.com/sethvincent/javascripting) at [NodeSchool](http://nodeschool.io/)
	- Upload a completed screenshot to Slack
- Read the [You Don't Know JS](https://github.com/getify/You-Dont-Know-JS/blob/master/scope%20&%20closures/README.md#you-dont-know-js-scope--closures) book on closures. (chapters 1 - 5)
	- Complete the code examples
	- push to github with the name: `YDKJS_closures_YOUR_INITIALS_HERE`
