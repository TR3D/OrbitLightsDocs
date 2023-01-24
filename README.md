# Overview
Orbit Lights is an editor utility widget that lets you pick a target object and place lights around it. Quickly adjust every light's position, intensity, color, etc., in one central place - no property hunt in the details panel is needed. This is especially useful for (portfolio) renderings because you can look through the render camera and adjust every light via the widget!
Light setups can also be stored as presets and used for different objects (to use the presets across various Unreal projects, manually duplicate the preset file and move it to the other project).<br>
![fghju657k](https://user-images.githubusercontent.com/63724445/213887822-c8e2c300-eee1-41ca-be38-e03259dece4a.jpg)

<br>
<br>

# Installation
Install the plugin from the marketplace and open the Unreal editor. 
Double check that the 'Blueprint File Utilites' plugin is enabled!
![212990043-782d0773-ed1b-4edb-bd5a-05f8a32e216f](https://user-images.githubusercontent.com/63724445/213887701-1571744f-063e-40ce-b6d8-b66035e77dc2.png)


The 'Orbit Lights' content folder should now be visible in the content browser: <br>
![image](https://user-images.githubusercontent.com/63724445/214223870-4c46d3d0-b391-4d98-bbe1-f95f0210e449.png)

<br>
<br>


# Workflow
## Bring up the UI
Navigate to the 'UI_OrbitLights' widget in the 'OrbitLights' folder. Right click the widget and choose 'Run Editor Utility Widget'. <br>
![image](https://user-images.githubusercontent.com/63724445/214224104-627c60f4-22fc-4f00-8b05-6b7681ddb517.png)

## Choose a target actor and add the first light
In the viewport, select the actor around the lights should be placed. Click on the 'Initialize' button to set this actor as a target for the lights. The first light will be automatically created for you:
![UnrealEditor_G1QwnXyUeT](https://user-images.githubusercontent.com/63724445/212994516-19772094-4a24-494a-a9ec-700266e09037.gif)

## Start adjusting the light
![sRqu2424xKDba1](https://user-images.githubusercontent.com/63724445/213887461-36158e25-096f-41ce-aa38-7465548da364.jpg) <br>
![UnrealEditor_nju2323BO9s0tQ](https://user-images.githubusercontent.com/63724445/213865345-4455e19c-1451-4e60-a8aa-e5751702c3e7.gif) <br>
![UnrealEditor_gIU7t516541XyoL8](https://user-images.githubusercontent.com/63724445/213865589-5f5582af-1931-4956-b3b0-df4b81f66b09.gif)<br>

<br>
<br>
  
# Presets
Once you find a pleasing light setup, you can store the arrangement as a preset and use that for other actors. The preset files are stored inside the 'Presets' folder in the plugin folder. Keep in mind that you can't see them in the content browser!
To save a new preset, change the preset name in the according text field and click on 'Save Preset': <br>
![UnrealEditor_sXNsW234214EZeAL](https://user-images.githubusercontent.com/63724445/213876360-a33292c2-5c1d-4162-bd4c-c201c9ba64f7.gif)  <br>

To load a preset, simply select the UI entry and click on 'Load Preset': <br>
![UnrealEditor_FdG65787U14L2yF](https://user-images.githubusercontent.com/63724445/213876427-581912d2-2e9c-47f9-8876-a150c3ef662e.gif) <br>

<br>
<br>

# Known Issues
- Undo/redo: some slider values don't reflect the changes to the actual light values. This is fixed as soon as you change the slider value again.
- UE 5.0: Changes to the lights are just applied when the user stops dragging the sliders. The lights are updated in all other supported versions while the slider dragging happens. 
