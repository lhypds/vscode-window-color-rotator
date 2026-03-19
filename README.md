
VS Code Window Color Rotator
============================


Rotate to use different color for VSCode window, for different projects.  


Quick Start
-----------

Ctrl + Shift + P, type `Window Color Rotator` to trigger command.  
It can remember the color for each project.  


How It Works
------------

Basiclly it write a custom color into `.vscode/.settings.json` file, `workbench.colorCustomizations`.  
The configuration file is at `~/.vscode/extensions/gcc3.vscode-color-rotator/colors.json`.  

Rotate color  
To rotate color for the current project.  
Use command:  
`Window Color Rotator: Rotate`.  
It will rotate choose a color for the current project window, and write the color to `settings.json` file.  
And save the project path to the color to `colors.json` file.   

Clear color  
To clear the color for current project winddow. For both in `settings.json` and configuration file (`colors.json`).  
Use command:  
`Window Color Rotator: Clear`.  

Reset all
To clear all the colors for all projects. For both in `settings.json` and configuration file (`colors.json`).
Use command:
`Window Color Rotator: Reset All`.


Local Execute
-------------

Clone the source code to project `.vscode` folder.  
Run `setup.sh` to install dependencies.  

`rotate.sh` to rotate window color.  
`clear.sh` to clear window color.  
`reset.sh` to reset all window colors.  
