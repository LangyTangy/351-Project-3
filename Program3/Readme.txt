Atticus Birkett, Langston Campbell, Andrew Cota, Carlo Scarpa
______________________________________________________
Group 6 Assignment 3 Submission
College of Information Sciences, University of Arizona
October 6, 2024

Implementation:

This project consists of all four requirement features
(Cutscene Cameras, Player can Kick, Shoot at Targets, and
Dynamic Soundtrack) in addition to the choice feature, Enemies 
Shoot Back, as outlined by the rubric. 

Cutscene cameras were handled using Unity's built in
cinemachine. Player can Kick was animated using provided
kick animations, expanding upon the player's base
animation state machine. Shoot at Targets was implemented
using a self-made bullet prefab, instantiated and deleted by
a self-written script that tracks bullet collisions with
bandit NPCs or exploding barrels, effects for which are sourced 
from Unity's Particle Pack provided for free from the Unity asset 
store, and adjusts values/plays animations accordingly. Dynamic 
Soundtrack uses provided sounds within the sample project and is 
handled in editor. Enemies Shoot Back was implemented using the
same bullet prefab used in Shoot at Targets, with additional
scripting to control for enemies turning, locating, and spotting
the player character before taking a shot, including statements
controling for their y-axis rotation, firing a raycast, and then
offsetting their aim to make it easy for the player to dodge.

Assets Used:

- Particle Pack by Unity Technologies

Made using Unity's Built-In Render Pipeline.

Credits:

- Scripting, modeling, texturing, animating, designing, 
  and compliling done by Langston Campbell
- Storyboarding, designing, and readme file writing done
  by Atticus Birkett
- Additional assistance given by Andrew Cota &
  Carlo Scarpa
______________________________________________________
Program 3 Template (Starter Code) - v. 1.0
School of Information, University of Arizona 
Feb. 12, 2023

This code may modified freely by students of
GAME 351 (Intro to Game Development) for use
in their assignments. Other uses covered by
the terms of the GNU Lesser General Public 
License (LGPL). Note: Some included assets 
may be subject to differing licensing agree-
ments as per the policies of their authors.

To install the project, follow these steps:

1) Create a blank "3D URP" project in Unity Hub.  
   Note: Your project MUST use the Universal 
   Rendering Pipeline for textures and effects
   to render properly.
2) Allow the Unity editor to initialize the project.
3) Save your blank 3D URP project and exit Unity.
4) Navigate to project directory in file system.
5) Drop the "Assets" and "Project Settings" folders 
   into this directory.
6) Open and reload the Unity project you created.
7) In the project navigator, go to the assets directory
   and find the "Scenes" folder.
8) Click on the "WesternTown" to load it.
7) Go to Unity->File->Build Settings and verify that
   the "Cross-Country Scene" is in the "Scenes in Build" 
   list.
8) If the scene is not in the build list, click
   "Add Open Scenes". The scene should appear checked. 
9) The game template then should be ready for building 
   and running.

Key Mapping:

W: Move forward
S: Move backward
A: Turn left
D: Turn right
C: Crouch

Credits:
 
Sample code by Leonard D. Brown, University of Arizona.
This program was developed for educational purposes. Not
for redistribution.

Media assets were used from the following sources:
(1) https://www.gog.com/en/game/outlaws_a_handful_of_missions
(2) https://assetstore.unity.com/
(3) https://www.gameartguppy.com/
(4) https://www.videvo.net/royalty-free-sound-effects/
(5) https://freesound.org/search/
(6) https://www.youtube.com/watch?v=JN8nj2-7G34
