# Overview
This documentation provides an overview of intended workflow and best practices when using Orbit Ligts for Unreal.
![image](https://user-images.githubusercontent.com/63724445/210605095-0167c31e-3a10-4f79-b37d-da2582401bd9.png)


# Installation
After Downloading the plugin from the marketplace, add the plugin to your project. When done with that, open your project and make sure that the plugin is enabled in the plugin manager (Edit - Plugins):
![image](https://user-images.githubusercontent.com/63724445/210607391-7a9ac921-1cfd-4476-847e-329b73f02705.png)

The 'Orbit Lights' content folder should now be visible in the content browser:
![image](https://user-images.githubusercontent.com/63724445/210607920-f4c35f1a-d667-4948-8ae7-9a6197b68a7c.png)


# Workflow
Bring up the UI by starting the 'UI_OrbitLights' editor utility widget:
![UE4Editor_GkTk8mcs0s](https://user-images.githubusercontent.com/63724445/210610047-b2ad139c-772c-4749-b465-0f531f3d143c.gif)

In the viewport, select the actor around the lights should be placed. Click on the 'Initialize' button to set this actor as a target for the lights. The first light will be automatically created for you:
![UE4Editor_ybvXxpF12h](https://user-images.githubusercontent.com/63724445/210610206-c284e30a-4f0e-422e-af58-4d0102264542.gif)

Start adjusting the light via the menu as needed.
![image](https://user-images.githubusercontent.com/63724445/210875495-d66e6472-a2aa-47d5-9d24-4945eab32902.png)

# Presets
Once you found a pleasing light setup, you can store the arrangement as preset and use that for other actors. The preset files are stored inside the 'Presets' folder in the plugin folder. Keep in mind that you can't see them in the content browser!
To save a new preset, change the preset name in the according text field and click on 'Save Preset': <br>
![UE4Editor_JJrfYvNIn8](https://user-images.githubusercontent.com/63724445/210876488-4e9c1a73-7ff3-4801-a53d-2342e2d73ebf.gif)

To load a preset, simply select the UI entry and click on 'Load Preset': <br>
![UE4Editor_8mAVg22xv4](https://user-images.githubusercontent.com/63724445/210876510-c2ad9278-a53e-4d2e-820c-31597aecf195.gif)


# Known Issues
- undo/redo: some slider values don't show the changes to the actual light values. This is fixed as soon as you change the slider value again.
