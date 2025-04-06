Project Assignments Log

"Mouse In Kitchen"

Game Version: Unreal Engine 5.3.2

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

Game Mechanics(Pass)

•Test level for bugs and perfomance issues

• Progression system works such as points, item unlocks

• Verify difficulty for gameplay is as expected

•Player respawns to player start point

Movements: (Pass) 

• The movements will be tested based on how fast they respond this includes making sure they respond to the keyboard, when jumping making sure the player lands in the game, and check for glitching  

•Testing for keyboard responses such as w to move foward, s to move backwards, a/d to move sides. The mouse controles the player camera view

•The mouse for camera control, checking for any glitches

Item Pick up and drop: (Pass) 

•Health Mesh dissapears after touching and adds to player health by 10% increments

• Cheese Key mesh can be picked up and player can carry mesh around map without it dropping

• Cheese Key opens intented door 

Doors: (Pass)

• Opening and closing the doors repeatedly  

• Doors open when link to a button

Weapons: (Pass)

• Weapons respond to the players keyboard command and causes damage to AI enemy, and big boss 

• Weapons for AI mice cause damage to player in 10% increments

Automatic Turret: (Pass) 

• Automatic turrets will be tested to make sure it causes damage, follows the player, and the player will be able hide behind walls and the turret won't shoot through the wall. 

• Automatic Turret causes player damage when hit with turret projectile

•Turret projectile doesnt get stuck to map and destroys after being shot

Map: (Pass) 

• The puzzle will be tested to make sure they complete when following instructions, this includes any buttons use to open doors 
 
• All meshes and structures used in the map are well-lit for the player and there are no gaps in between structures. 

•  The Progress bar shows on player screen, it also is accurate with players/AI mice health

• The spikes and and cheese roll cause damage to player when making contact

• The Mesh in the map will block player from getting in to certain parts in the map

• The Structures in the map have the intended color mesh 



Button: (Pass)

• The button will be tested by placing a mesh on top ensuring the button goes down and it unlocks the doors, this process is repeated 

AI Enemy: (Pass) 

• AI enemy response to game play, insuring it follows the player, and its weapon works 

• AI enemy reponse to player weapon and interaction

• AI enemy respawns in map/ check for respawn time 

Game Completion: (Pass) 

• The player can successfully complete the game after beating the big boss 

User Interface: (Pass)

• To ensure all menu and buttons are functional 

• test UI responsiveness on different screen sizes and resolutions

Performance Testing: (Pass)

• Monitor the frame rate under different conditions

• Measure load times for levels and menus

•Memory usage checking for memory leaks between game play testing

• Connectivity is testing for lagging, disconnections, and stability

Security Testing: (Pass)

• Test for any vunerabilties such as exploitation

• Data protection by ensuring is store securely and complies with regulations


The test plan will be updated weekly to confirm if the functions pass or fail. Any new testing done will be updated in the “Readme” files. All bugs will be kept in a document for reference in case the bug reappears. The bugs will be kept by the date the bug was found, what was the bug the issues it was causing to the game, and how it was solved including the date. The bugs document will be kept in an Excel sheet which then will be added to the repository.


4-2 Project Log : Team Reflection and Alpha Release


Testing the game resulted in most of the team functions working well and little issues were found in them. The problems found were missing functions in the components class such as damage. These bugs were identified by testing the game, this included making sure weapons, AI Mice, Cheese Wheel, and the Spikes in the map caused damage to the player. The solution was to go into an unreal engine and see what was missing in the functions in the class. Another solution to the bugs was using the debugging tool provided with an unreal engine. A good example is when we tested the AI Mice and realized the laser gun was not causing any damage to the player, the solution was that the “set health” function min and max were wrongly connected.  After all fixes are done in the game it's essential to retest the affected areas to ensure it works, also documenting all bugs and solutions for future reference. The documentation is also kept for analysis of patterns of bugs occurring frequently.    

The reason for QA is to prevent any errors from occurring when building the game.  The goal is to understand the definition of quality in the game. When testing the game, we realized more testing needed to be done towards the game, so our testing documentation was updated with the test done. Finding the solutions to the problems when it came to developing the game became a lesson for the team.  The team learned to be more organized when it came to game files to provide more storage. The tools and techniques used for the game development were overly complex and it complicated communication. This was solved by making one application the source of communication, and it prevents extensive documentation. A methodology was chosen for the game development to ensure good tools and techniques to which all members agree. The team approached the initial analysis by understanding the game’s vision, mechanics, story, and overall design. The second step was to identify the key requirements to accomplish the aspects of the game, also taking into account the existing tools provided such as the game engine, project management, and form of communication. The next step was to provide a prototype and the testing documentation with a feedback loop to assess the defectiveness of the game and its solutions. 


5-2 Project Log: Team Reflection and Beta Release 

The plan created in Module Three is well-structured and the team has done a good job outlining the technical and programming requirements for the game QA and testing. The team felt that the overall development of the game went well. We identified key components and developed a cohesive plan for implementing the game features. The plan was broken into a manageable task and then assigned based on roles, the use of methodologies was one of the team's strengths and helped the team to respond and adapt to changes needed. One area that proved challenging in the plan is that it could be more detailed when it came to what is being tested in the map and its functions, this resulted in editing the plan the following week and making it more detailed which caused a delay in the testing.  The team has taken all the feedback from earlier stages into account, such as adding a menu to the game which is integrated into the beta stage.   

To improve the collaboration and development process the team added an extra meeting to the week and implemented more frequent check-ins. The team also explored additional tools together when facing a problem, this taught new approaches, such as learning new commands in git bash and being able to fix deleted files. The tools being used in the project are being tested for effectiveness if the current ones are not helpful then they can try new approaches. A technique we added is to reduce the excessive focus of the visual gameplay and focus more on the game mechanics and functions. The beta stage will have all functions in the map completed, the beta stage has added a menu for the player to access the gameplay, instructions, credits, and controls. This will include the map to have its intended color meshes, the game play will be more enhanced since the map truly looked like a kitchen environment. This includes the development of the final boss being the cheese golem, this will increase the difficulty of the game since it's the final stage to beat the game.  A menu was added to help players start/end the game, instructions of the game, the controls, and the credits which includes everyone who was involved in the game development.  The project schedule reports that we are on track to meet the “Final Release” deadline. The game will be constantly testing to ensure we make any necessary adjustments to ensure we deliver a high-quality final game on schedule.  
