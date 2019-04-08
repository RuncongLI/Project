1.Software Version:
 - Unity3D: Unity5.6.5
 - Visual Studio: VS2017 Preview

2.Code and how to run it:
 -Interaction_paint:
     paint.cpp:main function and all code

     How to use:
Open FAAST Server->
Run paint.cpp. Clapping to open/close Windows Paint.
Straighten your right hand and start drawing.
Retracting the right hand can't draw, but the cursor can still move.

 - SFML_Interaction(2D):
     Utils3D.h: Structures JOINT3D and Squelette3D
                Function declarationcopyTrkToJoint() and copySqlt2Sqlt()
     Utils3D.cpp: Function implementation
                  sfml_interaction.cpp: Main function
    
     How to use: 
Open FAAST Server->
Run sfml_interaction.cpp. 
It shows a green circle at first.
If right hand is raised, change color to red.If down, change color to blue.
If left hand is raised, change shape to rectangle. If down, change color to circle.
If push your right hand,change texture. 

 - SFML_3D:
     sfml_3D.cpp: Main function
     Texture.cpp: Loading texture
     Utils3d.cpp: Function implementation copyTrkToJoint(),getDistanceAbs() and copySqlt2Sqlt()

     How to use: 
Open FAAST Server.
Run sfml_3D.cpp.
If right hand is raised or down, change color.
If left hand is raised or down, change texture. 

3.Plugins version: Oculus Rift App: 1.33
                   Kinect: 1.8

4.Library versions:
        - VRPN: 0732
        - FAAST: 1.2
        - SFML: 2.5.1
        - Oculus Integration(SDK): 1.32