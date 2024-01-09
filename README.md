# PlottingStyle
Luxe guidelines for plotting using root

Simple adaptation of the LUXE style used in the CDR/TDR, 
for usage by the ECALp for the TB2022 analysis.

Following 
https://confluence.desy.de/pages/viewpage.action?spaceKey=LUXE&title=Information+for+speakers

It uses the traditional rootlogon.C file, although it is not mandatory to have it, if the line

> SetLuxeStyle();
is included in your main macro.

rootlogon.C tutorial --> https://root.cern/doc/master/rootlogon_8C.html

## Example of application:

> root -l LuxeExample.C

Should work with root 6 (and probably root 7... to be checked!)


