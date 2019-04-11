# Oculus Audio+

## Purpose
This small application was built to make using the Oculus Rift a bit easlier to use. The primary purpose of the script is to allow you to swap between audio devices on the fly without having to navigate through 2-3 menus just to get to the settings you need. The secondary purpose is to allow you to start/stop the OVRService on command (assuming you set it to "Manual" instead of "Automatic" startup, like I have) and finally, it also functions as a shortcut to open the Oculus Rift Debug Tool if you like to enable SuperSampling like I do. 


## How to install
There are 2 ways of using this script. You can install the MSI file, which will copy the .exe automatically to your program files folder, as well as copy the necessary DLL file. The script will import the DLL automatically with this method. Once installed the exe can be moved anywhere on the computer. 

If you do not want to install there is also a portable .exe that requires you to import the DLL permenantly. To use this method simply download the .exe (instead of the .msi) and [follow these steps](https://github.com/frgnca/AudioDeviceCmdlets) to "Import Cmdlet to PowerShell"

### [Download Here](https://github.com/aubsynth/Aubsynth/tree/master/Oculus%20Audio%2B/bin/x64)

## How to use
Unfortunately this app requires admin priviledges to change audio devices and start/stop services. Once opened you can select the audio device from the dropdown list. It will automatically querry all available devices. If the rift does not show up, make sure it's plugged in and recognized by the computer. You can start/stop the oculus services via the appropriate buttons. To enable oversampling, you open the Oculus Diagnostics and enter the desired multiplier in the "Pixels Per Display Pixel Override" field. a number of 1.5 effectively doubles the resolution rendered in the device. Anything above 1.5 can be very taxing with diminished returns, so it is not recommended to go above 1.5. For the Debug Tool shortcut to work, this app assumes that the oculus software is installed on the C drive and in the default Program Files folder. (C:\Program Files\Oculus\Support\oculus-diagnostics\OculusDebugTool.exe) If you have it installed elsewhere please reach out and I can adjust the application to either find it dynamically or customize for your needs.

## Acknowledgements
I built this script myself using PowerShellStudio2018. The AudioDeviceCmdlets were provided by frgnca, repo located [here](https://github.com/frgnca/AudioDeviceCmdlets)
