Project Assignments Log
Blue Team: 

Ryan Kendall (Team Lead) 

Sherice Gordon (Programmer) 

Charlotte Armistead (Artist) 

Samantha Lasseigne (Level Designer/World Builder) 

Roxanne Miranda (UI/UX Programmer/Designer) 

The Blue Team game is named “Mouse in Kitchen”, the game is a third-person game. The main character is a mouse who lives inside of a kitchen and has figured out there is cheese somewhere in this kitchen. The mouse will have to face obstacles and enemies for some cheese. The game elements include: 

Moving Enemies: 

AI Mice 

Rolling Cheese Wheel 

Boss Enemy: 

AI Enemy - “Cheese Golem” 

Stationary Enemy: 

Turrets 

Spike buttons 

Stationary Obstacles: 

Door link with overlap key

obstacle drop 

Schedule and Timeline: File added to GitHub repository 


![Timeline (1)](https://github.com/user-attachments/assets/94fdae8a-e41a-4f16-98e3-115a1ea08fee)




  Module Three Project Log - Team Development: QA and Testing Plan.

For the Alpha Stage, the team will work on creating the AI Enemies, Door, Button, Mesh, and Turret for the game. This ensures that they function well before being placed on the map. The team will create a playable version to test elements and find any bugs. The alpha stage is used to complete the core functionality of the game. In the beta stage the team will focus on completing the map for the game this includes all levels, themes, and all elements placed in the map.  This test will require unit testing, to fix all bugs found in the alpha stage. The team will also have multiple game tests for any additional feedback. 

Communication: Meetings will be held every Sunday and Wednesday through voice chat on Discord. The team also has access to the discord chat. The Outlook email is used to send recordings and notes of the meetings. Most of the reports and assigning tasks will be taken in the voice chat meetings. 

For the play stage, we will be testing Item pick-up and drop once it's been implemented in some of the puzzles. Opening and closing doors once it's been implemented into the map and the beginning of the gameplay. Automatic turret once it's been implemented into the map and the final stage to beat the enemy turret. The map is being tested to ensure the gameplay runs smoothly, it is also being tested to ensure all props in the map work fine and all structures are connected.  

For the Demo stage, any bugs that were identified during the play stage should be fixed. This stage is to improve the user experience, this is done by getting any feedback during the gameplay test. The gameplay will be tested by all team members to ensure the functionality of the game works on every device being tested.  

For the code release, the goal is to analyze what in the game should be regularly tested. The objective is to document pass bugs and the strategy used to solve them, such as the test approach used, the test case to cover every possible scenario, the test data, and the test environment to confirm the game's combability.   

We will be using unit testing which will be done: 

Week 3-4 for the alpha stage 

Week 5 for the beta stage 

Week 6 for the final release  

All tests will be done on Friday or Saturday and during building 

How the testing will be done: 

Game Mechanics

•Test level for bugs and perfomance issues

• Progression system works such as points, item unlocks

• Verify difficulty for gameplay is as expected

Movements: (Pass) 

• The movements will be tested based on how fast they respond this includes making sure they respond to the keyboard, when jumping making sure the player lands in the game, and check for glitching  

•Testing for keyboard responses such as w to move foward, s to move backwards, a/d to move sides. The mouse controles the player camera view and the space bar is forjumping

Item Pick up and drop: (Pass/Fail) 

•Health Mesh dissapears after touching and adds to player health by 10% increments

Doors: (Pass)

• Opening and closing the doors repeatedly  

• Doors open when link to a button

Weapons: (Pass/Fail)

• Weapons respond to the players keyboard command and causes damage to AI enemy, and big boss 

• Weapons for AI mice cause damage to player in 10% increments

Automatic Turret: (Pass /Fail) 

• Automatic turrets will be tested to make sure it causes damage, follows the player, and the player will be able hide behind walls and the turret won't shoot through the wall. 

• Automatic Turret causes player damage when hit with turret projectile

Map: (Pass/Fail) 

• The puzzle will be tested to make sure they complete when following instructions, this includes any buttons use to open doors 
 
• All meshes and structures used in the map are well-lit for the player and there are no gaps in between structures. 

•  The Progress bar shows on player screen, it also is accurate with players/AI mice health

• The spikes and and cheese roll cause damage to player when making contact


Button: (Pass/Fail)

• The button will be tested by placing a mesh on top ensuring the button goes down and it unlocks the doors, this process is repeated 

AI Enemy: (Pass/Fail) 

• AI enemy response to game play, insuring it follows the player, and its weapon works 

• AI enemy reponse to player weapon and interaction


Game Completion: (Pass/Fail) 

• The player can successfully complete the game after beating the big boss 

User Interface

• To ensure all menu and buttons are functional 

• test UI responsiveness on different screen sizes and resolutions

Performance Testing

• Monitor the frame rate under different conditions

• Measure load times for levels and menus

•Memory usage checking for memory leaks between game play testing

• Connectivity is testing for lagging, disconnections, and stability

Security Testing

• Test for any vunerabilties such as exploitation

• Data protection by ensuring is store securely and complies with regulations


The test plan will be updated weekly to confirm if the functions pass or fail. Any new testing done will be updated in the “Readme” files. All bugs will be kept in a document for reference in case the bug reappears. The bugs will be kept by the date the bug was found, what was the bug the issues it was causing to the game, and how it was solved including the date. The bugs document will be kept in an Excel sheet which then will be added to the repository. 
