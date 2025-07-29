Installation instructions for NCSpectrahedronExtreme: 

As of version 3.1.2, NCSpectrahedronExtreme is now packaged as a paclet and is easy to install by executing the following mathematica command: 

PacletInstall["https://www.wolframcloud.com/obj/ericmevert/NCSpectrahedronExtreme-3.1.2.paclet"]

After installing the user may call NCSpectrahedronExtreme with the command

<< NCSpectrahedronExtreme`

Warning: The command to call NCSpectrahedronExtreme was updated in Version 3.1.2. Older notebooks may need to update this command. 

A brief version history follows. Detailed lists of changes can be found at the end of the NCSE.m.


30 May 25 Version 3.1.2

Added Several functions
 1. ComplexCommutantDimension for checking irreducibility over the complexes.
 2. PolyDual for computing dual free polytopes.
 3. BlockDiagonalize which finds a unitary that block diagonalizes a given tuple.
 4. GenerateStructuredExtremePoint which can be used to generate extreme points whose structure has a specific format.
 5. MinorsForNullDim which can be used to generate equations (based on matrix minors of appropiate size) a matrix polynomial must satisfy to have a specified rank.
 

Fixed an issue in FindExtremePoint that led to a missmatch between the default option settings for CommutantDimension and the options used in CommutantDimension when called with the default  settings of FindExtremePoint.

28 May 25 Version 3.1.1

Updates for paclet compatibility. Removed dependence on NCAlgebra.

Changed NCReplacedRepeated to ReplaceRepeated throughout.

20 Sep 23 Version 3.1.0

Added NullSpacePurification which significantly increases reliability of dilating to extreme points.
Added support for working over complex fields. 

2 October 21 Version 2.4.0

Replaced all instances of EigenSystem[Transpose[A], A] with SingularValueDecompositon[A].

29 July 21 Version 2.3.2.1

Fixed Issue which prevented the NumericsAssessmentTol option in DetermineNull from being able to be set by the user in many places where DetermineNull was called.

4 May 21 Version 2.3.2

Added functions for bean counts. 
Added MatrixExtremeSolutionBasis
Added support for algebraic arithmetic to DilationSubspaceBasis.

16 Apr 2021 Version 2.3.1

Added MatrixExtremeTest function for  determining if a given tuple is a matrix extreme point of a free spectrahedron. 

Updated 22/2/2021: NCSE 2.3.0
1. Added functions for experiments related to Arveson dilations.
2. Improved code for computing Free tangent plans and Dilation subspaces. 


Updated 14/4/2020: NCSE 2.0.1
1. NCSE now uses the Mathematica SDP by default. The Mathematica SDP requires Mathematica Version 12.0 or later to run. NCSDP may be used instead of Mathematica SDP as an option. 
2. Added several functions for computation of maximal 1-dilations and Arveson dilations for elements of a free spectrahedron.
3. Various bug fixes.
