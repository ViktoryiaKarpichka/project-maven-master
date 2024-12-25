<h1> Maven Project: JavaFX Game with JavaRush Engine </h1>

This project demonstrates how to build an executable JAR file containing a JavaFX game using the graphical engine provided by JavaRush.
It is part of the Java Professional module for educational purposes.

<h3> 🚀 Project Overview </h3>

The goal is to create a fat JAR (an executable JAR file with all dependencies bundled) for a JavaFX-based game. 
The game leverages the desktop-game-engine library provided by JavaRush.

<h3>🛠️ Steps to Build the Project</h3>
	•	Fork and Clone the repository
 
<h4> Build the Project</h4>
	•	Run the following command to build the project and generate the fat JAR:
 
   mvn clean install
  
  <h4>Run the Game</h4>
	•	Launch the game with Java 18:

  path-to-java18 /java -jar path-to-generated-jar

<h3> 🎮 How to Play </h3>

After successfully building and running the game, follow the on-screen instructions to play the JavaFX-based racing game.

<h3>📂 Folder Structure</h3>


project-maven/

├── lib/                     # Contains external JARs (e.g., desktop-game-engine-1.0.jar)

├── src/                     # Source code of the game and tests

├── pom.xml                  # Maven configuration file

└── target/                  # Output directory for the built JAR

<h3>📝 Notes</h3>

•	The Java version must match 18.0.1.

•	The game engine JAR (desktop-game-engine-1.0.jar) must be manually placed in the lib directory.

•	This project is for educational purposes only.
