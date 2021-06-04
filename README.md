# Heatometer
This software is a standalone software developed specially for the automatic analysis of heat transfer in rotary kiln. Submitted to the institutes of fluid dynamics and thermodynamics in fulfilment and completion of masters program at the Otto von Guericke University Magdeburg, by Saheed Afolabi Somoye. Supervised by MSc Claudia Meitzner

Heatometer Executable

# 1. Prerequisites for Deployment 

Verify that version 9.4 (R2018a) of the MATLAB Runtime is installed.   
If not, you can run the MATLAB Runtime installer.
To find its location, enter
  
    >>mcrinstaller
      
at the MATLAB prompt.
NOTE: You will need administrator rights to run the MATLAB Runtime installer. 

Alternatively, download and install the Windows version of the MATLAB Runtime for R2018a 
from the following link on the MathWorks website:

    http://www.mathworks.com/products/compiler/mcr/index.html
   
For more information about the MATLAB Runtime and the MATLAB Runtime installer, see 
Package and Distribute in the MATLAB Compiler documentation  
in the MathWorks Documentation Center.

# 2. Files to Deploy and Package

Files to Package for Standalone 
================================
-Heatometer.exe
-MCRInstaller.exe 
    Note: if end users are unable to download the MATLAB Runtime using the
    instructions in the previous section, include it when building your 
    component by clicking the "Runtime included in package" link in the
    Deployment Tool.
-This readme file 



# 3. Definitions

For information on deployment terminology, go to:

    http://www.mathworks.com/help
		
And select:

MATLAB Compiler >Getting Started > About Application Deployment >Deployment Product Terms

in the MathWorks Documentation Center.

# 4. Create folder

In order to run the software successfully create a folders named:

a) "Alpha" this is where the generated csv file will be located

b) "Figures_pdf" this is where the generated pdf file will be located

c) "Figures_fig" this is where the generated fig file will be located

d) "Figures_eps" this is where the generated eps file will be located


