# Circuit_Superstars_VR

<img src="https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/1097130/header.jpg">
<img src="https://github.com/user-attachments/assets/a29e3970-9058-415d-ac45-daf7e0826084">


# Description

Adds VR support to Circuit Superstars.</br>

Steam page of the game: </br>
[https://store.steampowered.com/app/1097130/Circuit_Superstars/](https://store.steampowered.com/app/1097130/Circuit_Superstars/)</br>

☕ If you wanna show some support you can buy me a coffee : https://www.buymeacoffee.com/astienth4 </br>

# <b>Installation</b></br>

1) Download the zip file: [https://github.com/Astienth/Cloudpunk-VR/releases/download/1.0.0/Cloudpunk_VR.zip](https://github.com/Astienth/Cloudpunk-VR/releases/download/1.0.0/Cloudpunk_VR.zip)</br>
  
2) Extract its content into the game root folder, the folder containing the "circuit-superstars.exe"</br>
3) Launch the game like you usually launch it via steam or the exe file.
4) Enjoy !

# <b>Controls</b></br>
No motion controller support. You need a gamepad or keyboard/mouse.
</br>
- Double press "Start" button on a gamepad or press F1 on the keyboard to toggle first person view
- Hold "Start" button on a gamepad or press F2 on the keyboard to recenter VR view

# <b>Options</b></br>
In the game root folder in /BepInEx/config. You'll find a txt file called "CircuitSuperstars_VR.cfg".
You can disable tunelling effect in first person view in this file (tunneling = true or tunneling = false) </br>
In the game root folder in /BepInEx/config, you'll find a config file named "UnityVR_Bepinex.cfg". 
In this file search for "Decoupled Pitch = true".
This forces the virtual horizon to be horizontal, but then you have to physically look down. It can be deactived with "Decoupled Pitch = false"

# <b>Deactivate the VR mod</b></br>
If you wanna deactivate the VR mod, you just need to rename the file <b>winhttp.dll</b> in the game root folder.</br>
It can be named anything BUT "winhttp.dll".</br>
"winhttp" = mod active </br>
"anythingelse" = mod inactive. </br>
