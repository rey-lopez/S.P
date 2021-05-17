# Test Report

## 1. Component Testing
One of the compenents that were done seperate from testing the entire system were the infinite spawning of enemies as well as the main menu features. 
* Infinite spawning
 - In testing implementing the infinite spawning of enemies I first tested by spawning in one individual enemy multiple times to test out its functionality. After finding that this worked I then included the other enemies and insured that it randomly spawned in one of the three different enemies from a selected point. 

* Main Menu
 - In creating the main menu I was sure to test out the functionality of each component as it was created. I first began with ensuring the different selections were clickable. From there I made sure that when clicked each component took the user to the correct following scene. ie clicking highscore took you to the highscores and clicking back returned you to the main menu. 
 
* Tests
Some of the tests I chose to perform in this project included ensuring that the controls were kept as simple as possible. At one point I considered implementing addition attacks for the player but realised this would only add to the complexity of the controls and decided on keeping a simple single attack rather than having different ones. Another test was checking the speed at which the enemies spawned in. The purpose of the game was to test ones reflexes and so I needed to ensure that the enemies had the ability to spawn into the game and move at different speeds. To do this a changeabe speed variable was implemented which allowed me to check that the enemies were able to move at different speeds which would allow for it to be increased as the players score got higher.

## 2. System Testing
System testing was performed each time a new component was introduced. I feel this was the correct decision because had I waited to test the system after multiple implementations it could have lead to a broken system with no ability to pinpoint the exact location of a problem. In testing the system every time a new component was introduced I could check and see that everything was running correctly and performing as it was supposed to up to that point. Meaning that if for some reason I ran into an issue I would know that it was with the last implementation rather than having to go through multiple components to find the problem. The results of me having tested after each new implementation ensured me having to backtrack and check several different components for errors.

## 3. Acceptance Testing
* For the parent user the mechanics of the game were kept simple. The arrows on the keyboard are used for moving forwards, backwards and to jump. The spacebar is used for attacking. 

* For the player the game was implemented to test ones reflexes by allowing for the speed of the enemies to slightly increase as your score increases.

* For the teacher the game contains very simple mechanics such as player movement, the main menu, and the highscore keeper that can be used as a visual for students on what can be done in Unity. 

* For the college student the game was kept simple and due to the increase in speed of the enemies the game length is short. 

* For the group leader the mechanics of the game are very simple although the highscores have not been completely implemented. 

* For the casual player the game is relatively easy to understand although it has not been completed so though it can be started it cannot be ended. 

### Parent
Completely implemented. 

### Player
Not completely implemented. 

### Teacher
Completely implemented.

### College Student
Completely implemented.

### Group Leader
Not completely implemented.

### Casual Player
Not completely implemented.
