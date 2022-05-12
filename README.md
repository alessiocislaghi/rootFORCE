## rootFORCE v.1.3 (May 2022)

This software is programmed as a Matlab App (@MATLAB R2020a).
The software rootFORCE estimates the probability distribution of root reinforcement over a forested stand as function of its tree species identity, tree density and average DBH.
For more details, please see the scientific references.
 
## References

1] Bischetti, G. B., Chiaradia, E. A., Epis, T., & Morlotti, E. (2009). Root cohesion of forest species in the Italian Alps. Plant and Soil, 324(1), 71-89.

2] Cislaghi, A., Chiaradia, E. A., & Bischetti, G. B. (2017). Including root reinforcement variability in a probabilistic 3D stability model. Earth Surface Processes and Landforms, 42(12), 1789-1806.

3] Cislaghi, A., Alterio, E., Fogliata, P., Rizzi, A., Lingua, E., Vacchiano, G., ... & Sitzia, T. (2021). Effects of tree spacing and thinning on root reinforcement in mountain forests of the European Southern Alps. Forest Ecology and Management, 482, 118873.

## How to run

rootFORCE Executable

1. Prerequisites for Deployment 

Verify that version 9.12 (R2022a) of the MATLAB Runtime is installed.   
If not, you can run the MATLAB Runtime installer.
To find its location, enter
  
    >>mcrinstaller
      
at the MATLAB prompt.
NOTE: You will need administrator rights to run the MATLAB Runtime installer. 

Alternatively, download and install the Windows version of the MATLAB Runtime for R2022a 
from the following link on the MathWorks website:

    https://www.mathworks.com/products/compiler/mcr/index.html
   
For more information about the MATLAB Runtime and the MATLAB Runtime installer, see 
"Distribute Applications" in the MATLAB Compiler documentation  
in the MathWorks Documentation Center.

2. Files to Deploy and Package

Files to Package for Standalone 
================================
-rootFORCE.exe
-MCRInstaller.exe 
    Note: if end users are unable to download the MATLAB Runtime using the
    instructions in the previous section, include it when building your 
    component by clicking the "Runtime included in package" link in the
    Deployment Tool.
-This readme file 



3. Definitions

For information on deployment terminology, go to
https://www.mathworks.com/help and select MATLAB Compiler >
Getting Started > About Application Deployment >
Deployment Product Terms in the MathWorks Documentation
Center.

