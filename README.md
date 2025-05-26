# CREW OSC Tracker
 CREW OSC Tracker is an Unreal Engine Plugin that creates a link between our [SPIN](https://github.com/CREW-Brussels/SPIN) system and Unreal Engine 5.3. As a reminder, SPIN is a utility hub for streaming spatial peripherals over the network.
***
 ## How to use CREW OSC TRacker Plugin?

This plugin contains a set of blueprints, useful to make the link between the SPIN app and an Unreal project.
***
### OSCServer 

The OSCServer Blueprint, when **put in the scene**(Drag and drop it in the scene), will allow you to receive the log information of the trackers, when the app is open in a headset. That way, you will be able to get the name of the tracker(s) you want to use, since their roles have been created earlier on the webpage of the app. This is possible, because SPIN is broadcasting.
 
### OSCComponentTracker

The OSCComponentTracker Blueprint, when assigned to an actor, will allow you to use the position and orientation of the tracker(s), using its address.

![OSCHierarchy](https://github.com/user-attachments/assets/306dae39-59d7-45a0-a563-f4f2d7a495e7)

In the address section, it should be entered like so: **/Server Name/address**
The Server name and address are the ones you set up in the SPIN Webpage.

 
