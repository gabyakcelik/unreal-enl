Resources:
I predominantly used resources from the ThirdPerson template given by Unreal Engine along with content from the LearningKit Games content and FirstPerson template. 

Environment:
The level is based on the ThirdPersonExampleMap given by the third person template. 
I converted the player from a third person camera to a first person camera since the first person camera was more for FPS games.
To mess around with the controls, I created a platformer where the player has to jump on each cube after going on the moving cylinder. I would definitely want to add a cube that moves from left to right to make it a bit more difficult which I know can be done with a blueprint. 
There is also some decor I set up and added textures to existing objects. I also tried making a mini house for the player to chill in once they complete the platforming.
I also added in music! I added one of my favorite soundtracks from Super Mario Galaxy: Rosalina's Observatory.

Interactables (and what they do):
- Shape_Sphere: Can kick it around like a ball since it has gravity
- TriggerBox_Blueprint: When the player is in the specified area, text will display to jump on the cylinder to complete the mini platforming created.
- MovingCylinder: When the player lands on the cylinder, it will rise up so that the player can jump on the cubes. Without going on this platform, they will not be able to complete the platforming. 
- PlayerButton_BP2: When the button is pressed, it will print out saying that the button was pressed, and once the player is off the button, it print saying the button has become inactive. This is called from the level's blueprint so a process could be triggered when this happens. I couldn't think of something to connect this to but thought it was interesting. 

What We Learned:
I learned a lot about blueprints and how they can be used to make interactables and used to create multiple instances of the same object. They also give a nice 'blueprint' for other interactables one may want to create. I also got a nice idea of how to create environments with the scaling and movement options. I also figured out how to group items together, for example CubeMesh has a PointLight connected to it so if the CubeMesh moves, so does the PointLight. In regard to the Content Browser, I learned how to efficiently look for certain materials using filters and search functions. Also previewing objects within the browser is useful. 