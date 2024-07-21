# TCT
In order to help readers to read TCT source code quickly, we write the following guide.

## 1.Development tool
The current version of TCT is written in C code and developed in IDE (Microsoft Visual Studio 2010 Professional version). The solution file (TCT.sln) can be found in the root directory. One can open the file TCT.sln by Visual Studio 2010, and generate the solution directly. No further setting is needed for compile the solution. If any errors on lack of basic libraries when compiling the solution, please install them from the IDE.

## 2.Folder structure in the package
**tct_src_20230514:   ----- root directory**

**TCT.sln**----- Microsoft Visual Studio Solution

**TCT:**   ----- Folder for workspace

- DES Procedure: ---- Detailed codes for TCT procedures
- TCT Console: --- Detailed codes for TCT console

	ctct.c: --- main function of TCT; readers can trace the code starting from the main function

- Graphviz: ---- package of dot tool used for drawing figures of DES transition graphs
- TCT.vcxproj   ----- VC++ Project file (auto-generated)
- TCT.vcproj.filters  ---- VC++ Project file (auto-generated)
- TCT.vcxproj.user  ----- VC++ Project file (auto-generated)

## 3.Citing the Software
Since a lot of time and effort has gone into the development, please cite the following publications if you are using the TCT for your own research:
- W. Wonham. Design Software: TCT, Systems Control Group, ECE Dept., University of Toronto, Toronto, ON, Canada, 2023. 


## 4.Contact
If readers have any questions on reading source code, please send email to me (Renyuan Zhang, ryzhang@nwpu.edu.cn).
