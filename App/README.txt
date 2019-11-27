Project Name: Maze Runner
Language Used: Java
Tool Used: Netbeans IDE

How to run: 
	Run MazeRunner.jar under /MazeRunner/dist/
	Also get the complete path to /MazeRunner/src and paste it in the TOP LEFT TEXT FIELD in the Maze Playing Window (2nd window)

Project:
 - Highly Customisable maze generation (tree based generation) in threaded fashion
 - Maze is playable with GUI and image sprites
 - In GUI, Open Door - You can go to that room
 		   Closed Door - Cant go through
 		   For Dead Ends - All doors closed
 - Parameters/ Customisations of the maze
   - Max Maze Depth - Max depth of the tree used for generation (Maze is modelled as a tree)
   - Dead End Probability - Prob that a node becomes dead end, i.e. no children to the node
   - Max number of doors - Max number of doors at any node -- DO NOT CHANGE -- Fixed at 3 (LEFT, FRONT, RIGHT doors)
   - Probability of Open Door - Prob that a door is open
   - Probability of Looping Back Paths - Prob that a door will loop the player back to a previously visited node -- LIKE TRAP DOORS
   - Number of Win Locations - Number of finish game locations
   
 - Example 
   - Max Maze Depth - 5
   - Dead End Probability - 0.2
   - Max number of doors - 3 (FIXED)
   - Probability of Open Door - 0.5
   - Probability of Looping Back Paths - 0.1
   - Number of Win Locations - 1
   - Click Update Parameters Button
   - In New Window, get the COMPLETE PATH to /MazeRunner/src in project folder and paste it in the TOP LEFT TEXT FIELD in the Maze Playing Window
   - Click Generate Maze Button
   - Now to go to a room, click on any open door and navigate thru the maze and PLAY!
   - Top Right Shows current position in maze S - source, F - Front, R - right, L - left
   - Click on Solution Button to get path to finish room to win the game
   - Restart Maze to restart the maze from start position
   - Generate maze to generate a different maze
 		   
 OS Concepts used:
  - Threading
  - Classes
  
  Group Roll Numbers:
  COE17B010		-		Kausik N
  COE17B015		-		Anurag Natoo
  COE17B036		-		Pranav
