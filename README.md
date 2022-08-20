# Restart computer shutdown


[![Restart computer shutdown](red2.png)](https://github.com/howsworks/restart.computer.shutdown/)

In this tutorial, we will explore various methods to remotely shut down or restart the Windows PC and servers. This is useful when you are connected to a home network on a LAN system and remotely need to perform the tasks on the workgroup computers.

This is also useful for the commercial purposes of LAN and WAN networks.


## Shutdown/Restart Windows PC

Here, we will first emphasize how to enable the remote computer access settings in your Windows PC. Then we will enlist the different methods available in Windows for remote shutdown and restart.


## How To Enable Remote Shutdown On Host Computer



For performing the remote shutdown task for the target computer or group of target systems in the home network or the commercial purpose, all the computers must be in the same network workspace and they all should have one common administrative account with the same username and password.



**Step 1:** First, the user account you are using on both the target and host computer has to be part of the administrator group on the local system. This is ensured by the display information as shown in the below screenshot.



**Step 2:** Follow the path: Control Panel ->Network and Internet -> Network and Sharing Center option. Now choose the Change Advanced Sharing Settings option from the left menu and then select the options Turn on network discovery and Turn on file and printer sharing. Save the changes as shown in the below screenshot.


**Step 3:** Go back to the main control panel menu and select the System and Security option. Navigate to Windows Defender Firewall and then select the Allowed apps and ports feature through the firewall, which is present on the left side menu.


**Step 4:** You have left with only one set which comes in the picture if your target computer’s Windows version is different from the remote computer. For example, If you are using Windows 10 and if the target computer is of Windows 7 or Windows Vista configuration, then you will have to make changes in the registry editor of Windows.


**Step 5:** Change the Value name to local account token filter policy and enter. Also, set the Value data to 1 from 0 which is the default. Now press OK and save settings as shown in the below screenshot to come out of the registry editor.


**Step 6:** To get the names of the computers connected on the network for target shutdown or restart operation, you need to go to Control Panel and select System and Security and then navigate to System. Here you will get the information like computer name, domain name, and workgroup settings as shown in the below screenshot.
