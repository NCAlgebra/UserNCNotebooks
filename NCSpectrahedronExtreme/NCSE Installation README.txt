This is the installation instructions for NCSE, with the assumption that the NC package is installed.

1. Download the NCSpectrahedronExtreme.zip.
2. Extract all files from NCSpectrahedronExtreme.zip into the NC folder in which the NC package is installed. Overwrite init.m when prompted.

Note: The NCSE package is compatible with the 23Aug2018 version of NC. NCSE should be compatible with all NC versions which have the same init.m as the 23Aug2018 version of NC.

A brief version history follows. Detailed lists of changes can be found at the end of the NCSE.m.

Updated 22/2/2021: NCSE 2.3.0
1. Added functions for experiments related to Arveson dilations.
2. Improved code for computing Free tangent plans and Dilation subspaces. 


Updated 14/4/2020: NCSE 2.0.1
1. NCSE now uses the Mathematica SDP by default. The Mathematica SDP requires Mathematica Version 12.0 or later to run. NCSDP may be used instead of Mathematica SDP as an option. 
2. Added several functions for computation of maximal 1-dilations and Arveson dilations for elements of a free spectrahedron.
3. Various bug fixes.
