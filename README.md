# Stackable Face Shield/Visor for 3D Printing On Single Nozzle Printer

Based on the [3dverkstan's](https://3dverkstan.se/protective-visor/) 3 hole US version face shield, this is a stackable design that you can use to print multiple shields on top of each other. The design has a small gap between the rows which allows a weak bond to form between consecutive face shields which can be snapped apart into invididual shields.

![Image of the 5 stack model](https://raw.githubusercontent.com/therealrakib/3dprinted-face-shield/master/5%20Stack.JPG)

**I have the 3 stack, 5 stack & 10 stack STL versions uploaded to this repository**

***If you want to create a stackable version of any other face shield versions or adding a custom number of stacks I have the instructions outlined below***

*I used Fusion360 for editing. You can get Fusion360 license free for a year for personal use from this [link](https://www.autodesk.com/campaigns/fusion-360-for-hobbyists)*

## Creating a stacked version of the Faceshield ##

- Download the face shield stl from this [link](https://github.com/Cederb/Faceshield.nu/blob/master/North%20America%203-hole/3D%20Printing%20Files%20(STL)/Thicker%20brow/Visor_Frame_NORTH_AMERICA_letter_3-hole_v4-solid_front.stl)
- Open Fusion 360 and create a new design
- Click the "Insert" down arrow (under "Solid" menu) and select "Insert Mesh"
- Select the 3-hole_v4-solid_front stl file to insert
- On the Browser right click on the top node of the tree (should be named "Unsaved") and click on "Do not capture Design History"
- A warning will pop up but click "continue"
- No right click on the model and select "Mesh to BRep"
- Once that is done right click on Body1 from the tree in the Browser and select "Move Copy"
- On the menu that pops up select "Create Copy"
- On the "Z Distance" type "5.35 mm" and click "OK"
- Now you can click on Body2 repeat the above steps to create another copy
- You can finally go ahead and create as many copies as you want
- Once done right click on the top node of the tree under "Browser" and select "Save as STL" to save the version

## Printing details ##
I use Cura as my slicing software but you could use any that you are comfortable using. 
I have printed the stacked versions on Ender 3 Pro with a 0.4mm nozzle and using PETG

*Settings changed to speed up:*
- Profile: Standard Quality
- Layer height: 0.3mm
- Infill: (Lines pattern)
- Printing Temperateure 240
- Build Plate Temperature: 75
- Build Plate Temperature Intitial Layer: 90
- Print Speed: 80
- Outer Wall Speed: 40
- Inner Wall Speed: 60
- Initial Fan Speed: 0
- Regular Fan Speed at Layer: 3
