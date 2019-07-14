# FriendFinder
Homework 11

Friend Finder has you matched up with a potential (boy)friend based on how you respond to ten questions on a quiz. I wanted to go with something more fictional than the example given so even though it says Friend Finder, the quiz is more like the anime boyfriend match-up quizzes you used to see in the early 2000s. 

Friend Finder has a server javascript that runs the code and an app folder with most of the code. The app has three folders: data, public and routing. Data holds the friends info (AKA the results of the code). Public holds the HTML pages with the css styling folder. Routing as the api routes needed for the programs to work and link to different results on the html.

Friend Finder starts you on the home page with a link to the survey. The survey will ask for your name and photo. The survey asks 10 questions. Some questions are based on personal preference and some are odd ones. When the submit button is pressed, the program will calculate the numbers and then match with one of the 10 (boy)friends pictures. Afterwards, the information will be asked to be saved on the website. 

Instructions on how to use/install Friend Finder: 
I. Make sure visual studio code is downloaded onto your computer. 
II. Clone this repo (click the clone or download button and copy the link) 
III. Install the package using the terminal. npm init creates package.JSON. npm install creates the locked package.JSON. 
IV. Install the node modules. 
V. The code won't work unless you install express, body-parser and path. The code will remind you that it's not installed. 
VI. Heroku should be the last thing installed. Heroku create will allow you access to the website online.

Technology used: Visual Studio Code: 
--> Javascript 
-> Express
--> Body-parser
--> Path
-> Heroku