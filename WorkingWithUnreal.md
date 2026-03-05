
###How to rename existing C++ class if it is a parent class of a blueprint.
1.	In Unreal Editor create a new C++ class with appropriate name, go to Visual Studio and move all necessary code from old C++ class to a new C++ class.
2.	Build a project from Unreal Editor.
3.	In Unreal Editor go to blueprint -> Class Settings -> In Details tab change the Parent class to a new C++ class. 
**Note**: You can see a warning it can cause a data loss. If changes seem not reliable, create a copy of your old blueprint.
4.	Test your project. 
5.	If everything is ok, remove a copy of blueprint (if it has been created), inherited from old parent class, close Unreal Editor, in File Explorer go to your project folder and remove old C++ class, then go to Binaries folder and remove content.
6.	In File explorer in your project folder right click on “.uproject” and choose “Generate Visual Studio files” to update Visual Studio project.
7.	Open Unreal Editor with your project, click “Yes”, and test your project again.

###How to move existing C++ class from one folder to another (or how to rename folder with C++ class).
1.	Close Unreal Editor.
2.	In File explorer go to your project and move existing C++ class to another folder, then go to Binaries folder and remove content.
3.	In File explorer in your project folder right click on “.uproject” and choose “Generate Visual Studio files” to update Visual Studio project.
4.	Open Unreal Editor with your project, click “Yes”, and test your project.
