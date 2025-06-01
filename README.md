# CREW OSC Tracker
 CREW OSC Tracker is an Unreal Engine Plugin that creates a link between our [SPIN](https://github.com/CREW-Brussels/SPIN) system and Unreal Engine 5.3. As a reminder, SPIN is a utility hub for streaming spatial peripherals over the network.
***
 ## How to use CREW OSC Tracker Plugin?

This plugin contains a set of blueprints, useful to make the link between the SPIN app and an Unreal project.
***
### OSCServer 

The OSCServer Blueprint, when **put in the scene**(Drag and drop it in the scene), will allow you to receive the log information of the trackers, when the app is open in a headset. That way, you will be able to get the name of the tracker(s) you want to use, since their roles have been created earlier on the webpage of the app. This is possible, because SPIN is broadcasting.
 
### OSCComponentTracker

The OSCComponentTracker Blueprint, when assigned to an actor, will allow you to use the position and orientation of the tracker(s), using its address.

![OSCHierarchy](https://github.com/user-attachments/assets/306dae39-59d7-45a0-a563-f4f2d7a495e7)

In the address section, it should be entered like so: **/Server Name/address**
The Server name and address are the ones you set up in the SPIN Webpage.


 ***



## About
<img src="https://github.com/user-attachments/assets/2ffa225b-2966-4f68-8106-3fd403fd6988" alt="CREW-LOGO" width="130"/>  
<img src="https://emil-xr.eu/wp-content/uploads/2022/10/logo_emil-272x300.png)" alt="EMIL-XR-LOGO" width="100"/>

> SPIN, a submodule of EXP, is being developed by [CREW](http://crew.brussels) as part of [EMIL](https://emil-xr.eu/), the European Media and Immersion Lab, an Innovation Action funded by the European Union and co-funded by Innovate UK. 

## Funding
<img src="https://emil-xr.eu/wp-content/uploads/2022/10/EN-Funded-by-the-EU-POS-1024x215.png)" alt="EU" height="100"/>

> This project has received funding from the European Union's Horizon Europe Research and Innovation Programme under Grant Agreement No 101070533 EMIL.
