# Overview
This documentation provides an overview of intended workflow and best practices when using Orbit Ligts for Unreal. <br>
![image](https://user-images.githubusercontent.com/63724445/212989663-9e1c1c82-b397-4f2b-b690-03ec4f25ccad.png)

<br>
<br>

# Installation
Install the plugin from the marketplace and open the Unreal editor. 
Double check that the 'Blueprint File Utilites' plugin is enabled!
![image](https://user-images.githubusercontent.com/63724445/212990043-782d0773-ed1b-4edb-bd5a-05f8a32e216f.png)


The 'Orbit Lights' content folder should now be visible in the content browser:
![FO4KqdYIJ1](https://user-images.githubusercontent.com/63724445/212994610-5cb475f8-0d3b-4a70-8b11-8dd9e15cb2c7.jpg)




<br>
<br>
 
# Workflow
Bring up the UI by starting the 'UI_OrbitLights' editor utility widget:
![UE4Editor_GkTk8mcs0s](https://user-images.githubusercontent.com/63724445/210610047-b2ad139c-772c-4749-b465-0f531f3d143c.gif)

In the viewport, select the actor around the lights should be placed. Click on the 'Initialize' button to set this actor as a target for the lights. The first light will be automatically created for you:
![UnrealEditor_G1QwnXyUeT](https://user-images.githubusercontent.com/63724445/212994516-19772094-4a24-494a-a9ec-700266e09037.gif)

Start adjusting the light via the menu as needed.
![image](https://user-images.githubusercontent.com/63724445/210875495-d66e6472-a2aa-47d5-9d24-4945eab32902.png)

<br>
<br>
  
# Presets
Once you found a pleasing light setup, you can store the arrangement as a preset and use that for other actors. The preset files are stored inside the 'Presets' folder in the plugin folder. Keep in mind that you can't see them in the content browser!
To save a new preset, change the preset name in the according text field and click on 'Save Preset': <br>
![UE4Editor_JJrfYvNIn8](https://user-images.githubusercontent.com/63724445/210876488-4e9c1a73-7ff3-4801-a53d-2342e2d73ebf.gif)

To load a preset, simply select the UI entry and click on 'Load Preset': <br>
![UE4Editor_8mAVg22xv4](https://user-images.githubusercontent.com/63724445/210876510-c2ad9278-a53e-4d2e-820c-31597aecf195.gif)

<br>
<br>

# Known Issues
- undo/redo: some slider values don't reflect the changes to the actual light values. This is fixed as soon as you change the slider value again.
