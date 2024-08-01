# SolidworksMacros
### Some useful VBA Macros for SolidWorks
In this repository I am collecting some useful macros I've developed to make my life easyer as a Mechanical Designer using SolidWorks almost everyday.
Because _.swp_ files are binary, I've aslo uploaded _.txt_ files with all the code if you want to create your macro from scratch.

## Macros
| Icon | Name | Description | Scope |
| --- | --- | --- |
| ![Ultimaker Cura logo](Open%20In%20Ultimaker%20Cura/cura_logo.bmp) | [Open In Ultimaker Cura](Open%20In%20Ultimaker%20Cura/OpenInCura.txt) | This macro allows you to automatically save any model in .STL format and open it in Ultimaker Cura. | Part and Assembly documents |
| ![Tolerance table icon](ToleranceTableMacroFeature/icon-40x40-transparent.bmp) | [Tolerance table macro feature](ToleranceTableMacroFeature/ToleranceTableMacroFeature.txt) | This macro inserts in a drawing a tolerance table that updates automatically everytime you change the name of a property called _Tolerance_. | Drawing documents | 

## How to use this macros
1. In SolidWorks, go to Tools > Macros > New.
2. Save the .swp file in any folder you want with a descriptive name.
3. Remove all the text that appears by default and copy and paste all code of the macro you want to use.
4. Modify the code to suit your preferences. Some macros will have notes at the begining of the file to customize them to suit your needs.
5. Save the file and close the VBA editor.
6. You can now run the macro by going to Tools > Macros > Run, and selecting the macro wherever you save it.

## License
This project is [MIT Licensed](LICENSE) .
