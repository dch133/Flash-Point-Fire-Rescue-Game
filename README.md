# Flash Point Fire Rescue Game
Bonus Roles: 

Structural Engineer, Dog, Veteran, Pyromancer

Credit for the team work: David-Gilbert-cs, Elvric, jz360, simz089s, mathieuvachon2

See Milestones for details on structure of the game

How to Set Up the Game: 
1. Install Gradle
2. In configurations (for both server and client), set the Working directory to *./core/assets/* & classpath of module to *desktop_main*.
3. Start the server and let the window pop up. Then start the client.
4. If Client cannot connect, set a different DEFAULT_SERVER_PORT in NetworkManager.java
5.  If Client still cannot connect:
    - In *core/src/networking/NetworkManager.java*, set the DEFAULT_SERVER_IP to the one of your computer. See comments there.
    - In *core/desktop/DesktopServerLauncher.java*, change the publicIP variable on line 16

Game Screenshots:
See Screenshots folder


