((This is a blender python script to convert textures made for the Sugarcult Project Regalia bodies to the Second Life default body UV.))

((USE RESPONSIBLY! Or don't, I'm not your parent))

Note:
- This is the very ((second)) implementation of this tool and will not work for everyone
- ((No guarantees that I can do anything to improve it because I am not a coder))
- This file uses the female body but it should be able to convert male textures as well
- ((The resulting bake images will have imperfections !!! ESPECIALLY on the feet/toe area, I might come back to that if I can figure out an improvement.))
- The script is made to use GPU rendering on Cycles to speed up baking

Prerequisites:
- Install the Project Regalia development kit Blender file (you get it with the body)
- Install Blender 2.82 or higher (I didn't test it on earlier versions) ((and I haven't tested it on anything earlier than 3.6 lol))
- Although the Regalia rig uses Avastar, this script does not need Avastar to be installed

Quick HOWTO:
- Download the DAE file provided in this repository and copy it into the Regalia devkit folder
- Create a new blend file, do **NOT** use an existing one as this script will clean out everything inside the file
- Create a new script inside the blend file (remember to add the .py extension)
- Copy/Paste the text from the python file in this repository to your script
- Modify the path names at the top of the python script to point to your file locations
- IMPORTANT: Save your .blend file so any relative paths (starting with "//") can work
- Run the script
- Find the SLUV_Bake_Upper.png and SLUV_Bake_Lower.png images in the same folder

((You can leave comments if you get stuck and I'll try to answer, but no guarantees I can solve everything 🥴))
