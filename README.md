CS455 Module 1 PR3: Collision/Obstacle Avoidance Behaviors Project
Author: Georgiy Antonovich Bondar

Go to https://keshakot.github.io/CS455_M1.PR3/ to play the game :)

# Behaviors
Collision Avoidance: Assets/Scripts/CollisionAvoider.cs  
Obstacle Avoidance: Assets/Scripts/ObstacleAvoider.cs  
 
# Changes from DV3:
1. Fixed some code to reduce compiler warnings to a minimum.  
2. Added two angled RayCasts to each ObstacleAvoider to help avoid collisions and avoid getting stuck on obstacles (the latter *usually* works but is not a complete fix).  
3. Made each ObstacleAvoider generate its own dummyTarget GameObject from a prefab (see code). This makes the ObstacleAvoider much more extensible and modular.  
4. Created a semi-playable game to demonstrate the new obstacle avoidance behavior.  

