## Icosa: models a bicolored icosahedron

#### Shows that no more than seven blue faces can be placed on a red dodecahedron such that no two blue faces share an edge. 

The code creates a Triangle class, to model the faces, and an Icosahedron class, to model the regular solid. 

Each face is named with a single-letter string. The names are hard-coded only once in the program.

The number of blue faces can be given as a command-line argument; that number defaults to seven.  

By default, the program tries every combination of seven blue faces and thirteen red faces, until it finds one that 
fulfills the desired condition. It prints this combination as a solution.

If the program is handed the command-line argument eight, it will try every combination of eight blue faces and twelve
red faces. It will find no solution, and print the string "Failure".  
&nbsp;  
&nbsp;  
License: GNU GPLv3
