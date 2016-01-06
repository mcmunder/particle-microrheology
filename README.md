# particle-microrheology.R

---

*Matthias Christoph Munder*
*@mcmunder*     
*http://matthiasmunder.de*

---

## Description
Simple R-code for MSD analysis of particle trajectories. Written by a biologist ;-)

## Dependencies
Under Mac OSX the newest version of XQuartz has to be installed. Free download under: http://xquartz.macosforge.org/landing/

## Input
The script expects result files generated by the MosaicSuite particle tracker plugin in Fiji (http://mosaic.mpi-cbg.de) as input. Result files generated by the tracker (all trajectories to table) have to be saved as .txt files.

## Output
The script saves dataframes and plots generated during the run into an output directory of choice. Additionally, the complete environment.R file is saved. This file contains all variables functions etc. generated during the run and can be reloaded for further analysis. 

---
