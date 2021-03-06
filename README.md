This is the Unreal Engine Developer course – it started as a runaway success on Kickstarter and has gone on to become one of the bestselling Unreal courses on the internet! Continually updated in response to student suggestions, you will benefit from the fact we have already taught over 360,336 students game development, many shipping commercial games as a result.

You're welcome to download, fork or do whatever else legal with all the files! The real value is in our huge, high-quality online tutorials that accompany this repo. You can check out the course here: Unreal Engine Developer

1 Intro, Notes & Section 4 Assets
Battle Tank is an open world tank fight
This will be a head to head battle
Other player can be human or simple AI
Heavy focus on control systems
Also learning terrains, UI, terrain sculpting & more
Dive right in and enjoy yourself!

1b Battle Tank Overview
An overview of the finished Battle Tank project.

2 S04 Game Design Document (GDD)
The Concept, Rules and (initial) requirements
We’ll iterate around a loop while making this game
Constantly asking “what’s least fun”
Remember we’re not AAA studios
Let’s find the essence of fun of this game.

3 Setting Up a GitHub “Repo”
Creating an online repository for your project
GitHub provides public hosting for free
We will use their default UnrealEngine .gitignore
We’ll then “clone” this repository to our machine
How to use a readme.md with markdown*

4 Creating & Deleting Landscapes
Creating an Unreal project in an existing “repo”
What’s good about Landscapes in Unreal Engine
How to add a Landscape in Unreal
How to delete a Landscape in Unreal.

5 Landscape Setup & Scaling
You can change position & rotation later
Scale will impact terrain size, so set on creation
How to choose your “Section Size”
The effect of the “Number of Components”
Creating a landscape of a specific scale.

6 A Landscaping Process
Sculpt: hills, valleys & flat areas
Smooth, flatten & ramp: create useful features
Erosion & noise: make it more organic
Paint: use layered materials
Details: add details (foliage, trees, etc)

7 Upgrading Engine Version
Epic games launcher helps manage versions
Remember to commit your project first
You can then “Convert in-place”
Check your project runs OK in new version
Close everything and re-commit
How to tag a commit in GitHub.

8 Using Landscape Layers
Create a material for your landscape
Set Usage > Used with Landscape
LandscapeLayerBlend node & Vector Parameters
Add at at least two layers & create LayerInfo
Paint the landscape from the Modes tab
Screenshot and share with us

9 Flat Shading Low Poly Landscapes
Unreal’s tools are setup for photoreal landscapes
Once you set the bar high, the rest must match
An alternative is to opt for a low-poly look...
...then you can focus on gameplay, story, sound
Can be a good choice for smaller teams
How to make low-poly, flat-shaded landscapes.

10 More Landscaping Tools
How to make flat shading optional
Importing and exporting landscape heightmaps
Reducing the resolution of a landscape
Using a texture in a landscape material.

11 Tank Control System
Support keyboard, mouse & gamepad controller
Mapping player intentions to control inputs
Mapping control inputs to actor actuators
Introducing the concept of “fly by wire”.

12 Actors from Multiple Meshes
Import the tank in 4 static mesh parts
Assemble the parts using sockets
Create our Tank_BP and test.

13 Configuring a Tank
Add mass to the tank
Fine-tune track position
Replace root component in Tank_BP
Enable physics and assign a mass
Set the tank as the Default Pawn
Setup PlayerStart and debug start collisions.

14 3rd Person Camera Control
Horizontal Coordinate System
Setup a Camera Spring Arm
Why the Spring Arm alone isn’t enough
How rotations don’t “commute”
Binding mouse and gamepad to camera control.

15 Fixing 3rd Person Camera Rotation
Use a Scene Root as azimuth gimbal
Use the Spring Arm for elevation control
Adjust the Spring Arm length
Set the camera rotation to 0 (down the arm)
Decide if you want the camera to roll or not.
