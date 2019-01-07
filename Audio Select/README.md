# Oculus Audio+

## Purpose
This small application was built to make using the Oculus Rift a bit easlier to use. The primary purpose of the script is to allow you to swap between audio devices on the fly without having to navigate through 2-3 menus just to get to the settings you need. The secondary purpose is to allow you to start/stop the OVRService on command (assuming you set it to "Manual" instead of "Automatic" startup, like I have) and finally, it also functions as a shortcut to open the Oculus Rift Debug Tool if you like to enable SuperSampling like I do. 


## How to use
There are 2 ways of using this script. You can install the MSI file, which will copy the .exe automatically to your program files folder, as well as copy the necessary DLL file. The script will import the DLL automatically with this method. 

If you do not want to install there is also a portable .exe that requires you to import the DLL permenantly. To use this method simply download the .exe (instead of the .msi) and [follow these steps](https://github.com/frgnca/AudioDeviceCmdlets) to "Import Cmdlet to PowerShell"

### [Download Here](https://github.com/aubsynth/Aubsynth/tree/master/Audio%20Select/bin/x64)

## Acknowledgements
I built this script myself using PowerShellStudio2018. The AudioDeviceCmdlets.dll were provided by frgnca, repo located [here](https://github.com/frgnca/AudioDeviceCmdlets)
