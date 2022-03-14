# VRUnited_Builds

# Install

1. Download the latest build from the [Releases](https://github.com/eventlab-projects/VRUnited_Builds/releases) section. 
2. Uncompress the __Builds.rar__ file. You will see that a folder for each supported platform is generated. Select the build that matches your system requirements:
* __Quest__: It contains a compatible .apk for _Oculus Quest (1/2)_. You must enable the developer mode on your _Quest_ (see [here](https://developer.oculus.com/documentation/native/android/mobile-device-setup/)). Then you must sideload the .apk on your device using [SideQuest](https://sidequestvr.com/setup-howto) (recommended, see Appendix A) or by directly using the corresponding adb commands through the console.
* __Pico__: sideload the .apk on your device using [SideQuest](https://sidequestvr.com/setup-howto) (recommended, see Appendix A) or by directly using the corresponding adb commands through the console. No further action is required as _Pico_ devices already have the developer mode enabled.
* __PC_Oculus__: This build works with the following devices: Oculus Rift family, Oculus Quest (1/2) + Link. You need to install the [Oculus software](https://www.oculus.com/setup/) on your computer.
* __PC_SteamVR__: This build works with any platform supporting SteamVR, which includes (but not limited to) HTC Vive (Pro), Valve Index as well as all the platforms in PC_Oculus. It is necessary to install [Steam](https://store.steampowered.com/) in your PC, as well as the [SteamVR](https://store.steampowered.com/app/250820/SteamVR/) application.

If you don’t have an HMD, you also can use the VRUnited application as a normal desktop application by using either the __PC_Oculus__ or __PC_SteamVR__ executables. In that case, __no additional software is required__, so simply start the executable.

Also take into consideration that, if you are running the application through the PC (with VR support or not), you need to make sure beforehand that your microphone is correctly detected as the default audio input device, that is properly working and that your applications are allowed to access to the microphone.

Finally, for future releases, probably the PC_Oculus build will be deprecated, as all the platforms supported by PC_Oculus are already supported by PC_SteamVR. So it is convenient you start installing the Steam and SteamVR if you want to keep using VRUnited on desktop with VR support.

Follow the [Wiki](https://github.com/eventlab-projects/VRUnited_Builds/wiki) for more in depth information. 

# Appendix A: Installing an APK from your computer using SideQuest

This step is necessary only if you are going to run VRUnited in a mobile platform, like _Quest_ and _Pico_. [SideQuest](https://sidequestvr.com/) is a third-party application that makes sideloading content onto your Android VR Headset (tipycally Oculus Quest and Pico families) really easy. To start with, simply [download](https://sidequestvr.com/setup-howto) the version that matches your system.

Once it is installed on your system, open SideQuest. Connect your VR device to the computer using the USB-C cable that goes with it. If the device is properly connected, at the top left corner it should appear the type of the device that you have connected and some information like the local IP address and the battery level.

If the button does not turn green but it keeps red, it means that it has not been possible to connect to the HMD. It usually happens on _Quest_ and it is because the developer mode has not been activated correctly. Check the following video to make sure that you are following all the steps to activate the developer mode:
https://www.youtube.com/watch?v=pdm54MRXWgk

Next in the bar menu that is located at the top right corner of the screen, select the icon that looks like a box with an arrow pointing down.

A file explorer window will appear. Look for the APK that you want to install in your device. Make sure to select the corresponding APK for your device, as APKs from Oculus Quest and Pico devices are different and one does not work on the other device.

If the installation process succeeds, you will see the following message at the bottom of your screen:
