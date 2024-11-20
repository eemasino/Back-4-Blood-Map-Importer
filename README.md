
1. Decompile the Game Files

Download and set up QuickBMS.
Use it to decompile the Back 4 Blood game files.
Extract Static Meshes and Textures:

Open the decompiled game files in uModel (UE Viewer).
Left-click the root folder and select Export to extract all static meshes and textures.
Repack the Game Files:

Once the meshes and textures are extracted, repack the game files.
Export Maps as JSON Files:

Use FModel to export maps from the game as .json files.

2. Install and Configure the Addon
   
Open Blender.
Install your addon:
Go to Edit > Preferences > Add-ons.
Click Install, locate the addon .zip file, and enable it.
Set up the addon paths:
Specify the path to the decompiled folder (where the models and textures are stored).
Specify the path to the JSON files exported by FModel.

4. Import the Map
   
In Blender, locate the addon panel in the sidebar.
Click Import Map:
The addon will process the JSON files and load the map into Blender.

6. Finalize the Map in Blender

Clean Nodes:
Press the Clean Nodes button to optimize the imported materials and textures.
Apply Materials:
Click Apply Material to ensure textures are correctly assigned.
Fix Normals:
Use the Fix Normals button to correct any shading issues on the meshes.
Important Notes
BSP Meshes Are Not Imported: The addon does not support importing BSP (binary space partition) meshes, so only static meshes will be included.

