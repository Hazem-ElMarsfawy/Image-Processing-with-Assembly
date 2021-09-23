# ASM.ImageProcessingPackage
Some Image Processing Filters (Linear, Spatial, Gaussian, ..) Implemented in Assembly Language and integrated with a C# Interface.

## Solution Structure
The solution contains three projects as follows:
1. Project: assembly language dynamic link library (DLL) project.
2. CsharpGUI: is a C# Windows form application which will be the main presentation layer to the user. It also will call all the functions from the DLL file produced by the the assembly DLL project.
