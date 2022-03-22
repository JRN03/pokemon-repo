# pokemon-repo
Mock Pokemon battle using JAVA.
Twist on classic pokemon games using my teacher's face in place of original images.
Created using Java's swing libraries and JFrames. In the future, I could likely implememt a more 
efficient method via LibGDX or OpenGL.

# Import
Pull the repository to local device. When importing via Eclipse, select file -> import -> project.
Select the pokemon you wish to use in the console and a corresponding gui will be created.

# Custon Pokemon
To create custom pokemon, create a new class that implements the Aggie interface. Then go into the main class function and add 
new *name*(new Sprite("*sprite*"),"*display name*",int health,int speed,int damage,int defense)
