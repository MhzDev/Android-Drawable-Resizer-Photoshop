# Android-Drawable-Resizer-Photoshop
A script for Photoshop to resize automatically Android image resources


<img src="https://github.com/MhzDev/Android-Drawable-Resizer-Photoshop/blob/master/Github%20Art/IconDensity.png" width="400">
## Features
- Supported density: XXHDPI, XHDPI, HDPI, MDPI.
- Smartphone and Tablet folders support.
- Automatic folder sorting (Each version is stored in its "drawable-..DPI" folder).

##### Compatibility: All photoshop versions are compatible with this script

## Configuration
- Put the main folder "Android Drawable Resizer" in C:\
- Open the .atn script file, the script will be added to photoshop.

## How to use
The script is composed by 2 actions, for smartphone and tablet, each action put the output resources in the relative folders.
- Put the resources (in its XXHDPI resolution) you want to resize in C:\Android Drawable Resizer\(smartphone or tablet)\input 
- In Ps open the menu "File -> Automate -> Batch...".
- Configure the Batch like the screen below selecting the action and the folder.
<img src="https://github.com/MhzDev/Android-Drawable-Resizer-Photoshop/blob/master/Github%20Art/BatchSetting.png" width="600">
- Press ok to start the batch, the resources will be saved in the respective folders.

### How the script work
The script take all the resource in the "input" folder one at a time, resizes and saves the images for each resizing.
