# Doodle Deck

Developed by Ethan Brandt

### Project Purpose
Doodle Deck is being created for a distributed systems project for my university degree. I try to relate every project to my future work and I believe that a networked game has a lot to teach me. I also really wanted an excuse to make a card game (I've never designed one before and it seemed like a lot of fun). (we'll see how much I come regret this given the short timeline) (update I did not regret this) (well maybe a little)

### Prerequisites
- Unity 6000.2.4f1 (https://unity.com/download)

### Project Setup / How to Run
1. Download the source project and improt doodle-deck/unity-project/doodle-deck as a project in Unity
2. Use the Multiplayer Play Mode window to open two other Unity instances and run the projet using Play Mode
3. Create one server and at least two clients
4. Toy around with the project!

### Other Important Info
I added the submission commit as a submodule to the git repo
All source code was written in C# using Unity's engine specific libraries
Each class inherets from a Unity specific class that hooks into various engine systems
All communication between client and server are done through the use of RPCs, provided in Unity's Netcode for GameObjects package
My source code is in: doodle-deck/unity-project/doodle-deck/Assets/Scripts