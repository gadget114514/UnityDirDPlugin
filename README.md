# UnityDirDPlugin: DirD Unity Editor Plugin

DirD is simple folder browsing tool supporting drag and drop to other editor window.

# Install
Download dird.unitypackage from repository (as raw data)
Import dird.unitypackage. 

# Getting Started
[Tools]-[DirD by 2nek] opens Editor window.
You can drag the window as a docking window.

# How to use
Click to open the folder. 
Drag and drop the file to other window.



# Usecase

For example,
When you try to set a material to Mesh renderer, you would specify the mesh renderer 
and lock the inspector.
Then you find the material in project tab, and set the material to mesh renderer.

If there are a lot of mesh renderer which material should be changed, you have to
repeat locking and set. This tool reduces the inspector locking because this is special
file browser which does nothing for folders and other files.
You know Unity editor supports multiple project tabs so you might say that this tool is in vain.
If you want to specify a file then drag and drop it to a inspector slot, you will find
that this tool will reduce your manual procedure a little bit. 



# Licence
MIT


# Third Party
DirD is based on CustomProjectView https://github.com/furkancaglayan/CustomProjectView
Customized Project View for Unity3D made with Editor Windows.
