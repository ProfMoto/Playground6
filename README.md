This collection is an update and expansion on the Unity Playground toolkit released by Unity Technologies: https://github.com/Unity-Technologies/UnityPlayground

It is not currently available in the Unity Asset Store.

This package is an updated set of scripts from Unity Playground, prepared to work in Unity 6. Documentation and graphics are not included. Tutorials to learn Unity with this package are forthcoming.
Unity Playground has been a powerful tool for learning for the past years, but migrating to Unity 6 means that Playground will no longer functions. This is largely due to the graphical editor improvement and simplifications present in Playground. I've removed most of those elements, to make this package purely the functional scripts to make Playground work for Unity 6!


NOTE: This toolkit has been prepared for and tested with 6000.1.14f1. If you have any errors, please validate that you are working in 6000.1.14.f1 before submitting any Issues.

Installation Recommendations:
Playground 6 requires modification to your Unity Project Settings, but these settings can be changed most easily by following these steps:
Download the main github package for this repository and unzip it.
Create a new Unity 6000.1.14f1 project of type Universal 2D Core
Allow this project to open, then close the project.
Copy the contents of the github package (folder Assets and folder ProjectSettings) into your new Unity Project folder and OVERWRITE the current files.
This will overwrite your settings and is the easiest possible setup.

If you are unable to overwrite your files as listed above you may also:
Copy the contents of the Assets folder from this github repository into your Assets folder.
Open your Unity Project.
Save your project if you have any work.
Open Project Settings > Player and change Active Input Handling under Configuration to BOTH.
Unity will restart.
In Project Settings > Input Manager open the Axes
Remove Alt Positive and Alt Negative buttons for the first Horizontal and first Vertical
On the second Horizontal change the settings to:

Name: Horizontal2
Negative Button: a
Positive Button: d
Gravity: 3
Dead: 0.001
Sensitivity: 3
Snap: Checked
Type: Key or Mouse Button

and the second Vertical to:
Name: Vertical2
Negative Button: s
Positive Button: w
Gravity: 3
Dead: 0.001
Sensitivity: 3
Snap: Checked
Invert: Unchecked
Type: Key or Mouse Button
