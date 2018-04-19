# 2018_NatComm_MxB
All code used in image analysis for Crameri, et al. 2018 Nat Comm. MxB is an interferon-induced restriction factor of human herpesviruses

Fig. 3b:
This file was used to simulataneously analyse nuclear signal intensity from two distinct channels for each individual cell.
In order to run the macro on ImageJ, source folders should contain RGB files with three active channels, the nuclear channel being at position 3.
Please adjust the parameters where indicated.

Fig. 4b:
This file was used to analyse nuclear signal intensity from one channel for each individual cell.
In order to run the macro on ImageJ, source folders should contain RGB files with two active channels, the nuclear channel being at position 3.
Please adjust the parameters where indicated.

Fig. 5a:
This file was used to count the number of objects (i.e. HSV-1 capsids exposing VP5) per cell within cell boundaries defined by a cellular stain.
In order to run the macro on ImageJ, source folders should contain RGB files with two active channels, the cellular stain channel being at position 3. 
Please adjust the parameters where indicated.

Fig5.cppipe; 
open in CellProfiler (this was created in CellProfiler v2.1.1); 
this was used to analyze maximum projections of fluorescence images (.tif) taken on a Leica microscope; parameters need to be adjusted to ensure proper segmentation
  
MB_HSV_capsid_genome_analysis; 
Import into KNIME (this was created in KNIME v2.12.2); 
this pipeline works with Fig5.cppipe output from CellProfiler;
