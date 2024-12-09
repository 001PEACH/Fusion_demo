

# Fusion_demo

This is an implementation of "Visibility Enhancement in Challenging Conditions: Perceptual Dehazing with HDR System". The code details will be released after the paper is accepted.

The code has been tested with Matlab R2021b. Higher versions of Matlab should also work well. Given an image pair or a video sequence, our code supports generating prediction results of fusion

 The package includes:

Input: Input multiple exposure image sequence;

demo_exe: packaged independent executable files;

## fusion_demo Executable

1. #### Prerequisites for Deployment 

Verify that version 9.11 (R2021b) of the MATLAB Runtime is installed.   
If not, you can run the MATLAB Runtime installer.
To find its location, enter

    >>mcrinstaller

at the MATLAB prompt.
NOTE: You will need administrator rights to run the MATLAB Runtime installer. 

Alternatively, download and install the Windows version of the MATLAB Runtime for R2021b 
from the following link on the MathWorks website:

    https://www.mathworks.com/products/compiler/mcr/index.html

For more information about the MATLAB Runtime and the MATLAB Runtime installer, see 
"Distribute Applications" in the MATLAB Compiler documentation  
in the MathWorks Documentation Center.

2. #### Files to Deploy and Package

Files to Package for Standalone 

-fusion_demo.exe
-MCRInstaller.exe 
    Note: if end users are unable to download the MATLAB Runtime using the
    instructions in the previous section, include it when building your 
    component by clicking the "Runtime included in package" link in the
    Deployment Tool.
-This readme file 

3. #### Definitions

For information on deployment terminology, go to
https://www.mathworks.com/help and select MATLAB Compiler >
Getting Started > About Application Deployment >
Deployment Product Terms in the MathWorks Documentation
Center.
