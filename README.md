# Le-Rythme-Du-Sabre
VR BeatSaber-like including level editor.
We worked on this project as a team of 8 students for 4 weeks (aside our usual schedule).

## Content

The game holds 3 scenes : 
  - the main menu;
  - the play scene;
  - the level edition scene;

## Features

Once in edition scene, the player is supposed to use 2 VR controllers to build a level. 

The right controller is for cube placements, the player can :
- put cubes on one of the prepared placement points (trigger - pression)
- Change the current cube color (Grip - pression)
- Change the current cube rotation (Touchpad - slide)

The left controller is for music and progressing in the level, the player can :
- Play the music from the current position (trigger - pression)
- Stop the music (Grip - pression)
- Visualize the level by going forwards or backwards (Touchpad - slide)
    
A pause menu is also available with the menu button of any of the controllers.

Once a level is completed, the player can save it and this level will be available from the main menu : the aim of the game being to break the blocks in the right direction with the corresponding saber.

## My Participation

I coded the cube placement (*CubePlacement.cs*) and the interaction of the saber with cubes (*Saber.cs*).
