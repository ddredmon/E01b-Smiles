# E01b-Smiles
An exercise exploring variables and loops using Python Arcade.

This repository has a few files that each do variations of the same thing.

main1.py contains code for a program that creates a smiley face in arcade by loading its components (circle, outline, eyes and eyecatches) in certain points on a grid. It started in the corner, but through trial and error the coordinates of each object now line up to make a proper smiley face.

main2.py does much of the same, but now the coordinates of the face are saved as their own variable, so instead of typing in individual coordinates for each object, they can instead be mapped to where the main circle of the smile is, with additions/subtractions to those coordinates to factor in the spacing between the eyes and such.

main3.py does what main2.py did, but now variables are listed for each object's position instead of just for the face. This allows the user to view and alter the variables in one spot and have the code call these variables in place of manually entering the equations and coordinates for each object.

main4.py does what main3.py did, but now the code is in a repeating function that makes multiple smiley faces appear in an overlapping grid.

main5 is bonus credit stuff that frankly, I didn't want to mess with.