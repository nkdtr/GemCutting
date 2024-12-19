# Gem Cutting Utility
Boolean-based gem cutting utility.
![image](https://github.com/user-attachments/assets/5e013509-593a-4b6d-84d2-4d4121c8b2bf)

## How to Use
Two main types of actors are used:
### Stone (derived from BP_StoneBase)
It is the original stone from which gemstones are quarried.

### Cutter (derived from BP_CutterBase)
By attaching it as a child of Stone, it is cut by And operation.

### Writing out to StaticMesh
1. Prepare a StaticMesh that can be rewritten and assign it to the Output Mesh of the Stone.
2. Clicking on the “Copy to StaticMesh” button in Stone will apply the created geometry to the StaticMesh.

![image](https://github.com/user-attachments/assets/e9b12606-b540-42d8-8696-07b549c6f7da)

## About Crystal Renderer
![image](https://github.com/user-attachments/assets/bede4245-2988-44bd-887b-e720e7ed0d94)  
The resulting gems can be beautifully rendered using the CrystalRenderer plug-in.    
Store:  
https://fab.com/s/05ba8a070b1e  
Videos:  
https://youtu.be/taKkOU8bogA  
https://youtu.be/iw4QpaW6c3E  
