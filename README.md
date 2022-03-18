# terrain_simulator
Unstructured Terrain Simulator (ROS Gasebo-based)

## Installation
1. Add Gazebo path in ~/.bashrc

    export GAZEBO_MODEL_PATH=/home/usrg/.gazebo/models # for using custom model. (e.g., \<uri>model://heightmap/materials/~~)

    export GAZEBO_RESOURCE_PATH=/usr/share/gazebo-9 # for using default material textures. (e.g., \<diffuse>file://media/materials/~~)

    ('usrg' should be changed to your PC's user name.)

2. Copy & paste heightmap directory of this package in 'GAZEBO_MODEL_PATH'

    cp -r environment/terrain_gazebo/heightmap /home/usrg/.gazebo/models

## Notice

- Make sure the png file for the height map has alpha channel! (if not, the texture of the height map does not work well.)
