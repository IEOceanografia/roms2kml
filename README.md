Matlab scripts to create KML/KMZ files to use in Google Earth from output files 
coming from a Regional Ocean Modelling System (ROMS) configuration. 

These scripts require:

http://code.google.com/p/googleearthtoolbox

Below there are some comments about the used of the GoogleEarth toolbox:

The GoogleEarth toolbox needs to be added to the MATLAB path before use.

This can be accomplished by running the 'addpath' command from the 
matlab command prompt. For example:

>> addpath('/home/sdavis/googleearth')

Make sure to insert your the location of the GoolgeEarth toolbox on your 
own system. 


To make optimal use of the documentation, run the following command from 
the command prompt (after having added the toolbox to the path):

>> googleearth -docinstall
