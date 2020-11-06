# NavMeshGen
Renewed NavMesh Generator for Panda3D was taken from 
[run4life repo](https://github.com/fnadalt/run4life/) and modified for Python 3 support. 

## Requirements

* Panda3D 1.10.x
* Python 3.x
* Regular and collision meshes in EGG format

## How to create navigation mesh in Blender 2.8+
<img src="https://i.imgur.com/aU2elwA.png" />

Create grid with **64** X and **64** Y subdivisions. Rotate it to **90** degrees by X. Set scale to **70**. 
Then export it as `fullMesh.egg` and `collMesh.egg`, using [YABEE for Blender 2.8.x](https://github.com/kergalym/YABEE). 

## How to use
This script creates a 'navmesh.csv' (which is used by the pathfinder in PandAI)

To run the script, do: (Please use the correct syntax in the command line) 

`python3 NavMeshGen.py fullMesh.egg collMesh.egg`
