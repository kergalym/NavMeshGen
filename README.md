# NavMeshGen
Renewed NavMesh Generator for Panda3D was taken from 
[run4life repo](https://github.com/fnadalt/run4life/) and modified for Python 3 support. 

## Requirements

* Panda3D 1.10.x
* Python 3.x
* Regular and collision meshes in EGG format

## How to use
This script creates a 'navmesh.csv' (which is used by the pathfinder in PandAI)
from meshes exported by [YABEE for Blender 2.8.x](https://github.com/kergalym/YABEE).


To run the script, do: (Please use the correct syntax in the command line) 

`python3 NavMeshGen.py fullMesh.egg collMesh.egg`
