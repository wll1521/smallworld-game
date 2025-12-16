# SmallWorld-Game Space Adventure

Authors:
William Locklier
Kylie Arnett
Jeremy Quijano


---

OVERVIEW
--------
A Java text adventure game built to demonstrate object-oriented design, game state management, and rule-based logic. 
Collect items, solve riddles, and try to escape.

The project was designed to:
- Apply core object-oriented programming principles
- Model non-trivial game rules and player interactions
- Apply a testing suite for compliance 
- Deliver a complete, runnable Java application

---

## Features

- Text based adventure game with point system
- Game state management and rule enforcement
- Interactive GUI
- Modular Java architecture
- Runnable standalone JAR

---

## Built With

- **Java**
- **Eclipse IDE**
- **JUnit** for testing
- Standard Java libraries

---

### Prerequisites

- Java JDK 21 or newer
- Eclipse IDE for Java Developers

### Importing the Project into Eclipse

1. Open **Eclipse**
2. Go to **File → Import…**
3. Select **Git → Projects from Git**
4. Choose **Clone URI**
5. Enter: https://github.com/wll1521/smallworld-game.git
6. Click **Next** through the defaults
7. Select **Import existing Eclipse project**
8. Click **Finish**

### Running the Game in Eclipse

1. Open the project in Package Explorer
2. Find class containing main with GUI:
   edu.southalabama.csc527.smallworld.textui.graphical
3. Right click -> Run As -> Java Application
   or just run included .jar file in "release" folder
   "java -jar GraphicsGame.jar"
5. Game should launch

### JUnit Testing Suite

1. Open project in Package Explorer
2. Find "test" folder package:
3. Right click -> Run As -> JUnit Test
4. Should show results in panel at bottom

### Game Rules Information (type "help" command):

You are controlling a player interacting with a small world created 
within the computer.  The commands you type control what the player 
does within the game.  Some actions add points to your score.  You win 
the game when you obtain enough points through your actions.

The following is a description of the commands the game understands:

"go <north | south | east | west>" moves the player from his or her 
current location in the specified direction to a new location. The word 
"move" may be used to mean "go" within this command. An example is "go 
north" or "go n"

"load <filename>" loads the specified save file into the game.  
Discards the existing game state.  Example "load C:\save1.xml"

"look" examines the player's current location.

"quit" or "exit" terminates the game.

"save <filename>" saves the current game state to the specified 
filename. Example "save C:\save1.xml"

"take <item name>" to pick up an item at your current location. Use 
"take all" to pick up everything.

"drop <item name>" to drop an item from your inventory.

"inventory" (or "inv" or "I") to list the items you are carrying. 
