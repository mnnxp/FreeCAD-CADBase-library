FreeCAD-CADBase-library
===============

This macro repository is missing for the best CADBase with FreeCAD.
It is not part of a FreeCAD project. The macro  designed to use components from the CADBase in the FreeCAD interface.

The purpose of the macro is to allow users to get components from CADBase in the FreeCAD interface.

Adding and configuring a macro
---------------------------

1. Create an account on the platform [CADBase](https://cadbase.rs/#/register) for yourself
2. Add the necessary components to bookmarks (favorites). The FreeCAD interface will only display components that the user has bookmarked.
3. Download the macro as a zip file using the green "clone or download" button in the top right corner of this page
4. Unzip the file `CADBaseLibrary.FCMacro` to the FreeCAD **macros folder**
5. In FreeCAD, select the "Macro" tab and select the `CADBaseLibrary.FCMacro` macro, then you will be prompted to select the module folder (where the files from the CADBase store will be loaded)
* In FreeCAD, find which is your user **modules folder** by entering or pasting `App.getUserAppDataDir()+"Mod"` and your usr **macros folder** by entering `App.getUserMacroDir()` in the Python console (found under menu View->Panels)
6. In the "CADBase library" window, in the "Options" tab, click the "Config" button, in the "CADBase library configuration" window that opens, you need to set the username (username) and password (password) to gain access to CADBase. Wait for the token to be received after pressing the "OK" button.
7. After successful authorization, click "Update from CADBase" and wait for information about the bookmarked components

**Note**: Please DO NOT use accented characters in your file names, thanks!!!

Using the macro
-------

Clicking "Update from CADBase" only updates the list of components, without downloading component modifications and files.

Double-clicking on a component's folder retrieves the component's modifications.

Getting files of a fileset for FreeCAD occurs after double-clicking on the modification folder.

If you want to share a tip, get involved, report a problem, or anything else, please create a issue or post in this FreeCAD forum thread: http://forum.freecadweb.org/viewtopic.php?f=29&t=68814

License
-------

All Parts in this repository are licensed under CC-BY 3.0 http://creativecommons.org/licenses/by/3.0/
Each Part is copyrighted by and should be attributed to its respective author(s).
See commit details to find the authors of each Part.

The macro is based on
-------

https://github.com/FreeCAD/FreeCAD-library
