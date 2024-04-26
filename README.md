This work was created in partial fulfillment of Arizona State University Capstone Course “SER401″. The work is a result of the Psyche Student Collaborations component of NASA’s Psyche Mission (https://psyche.asu.edu). “Psyche: A Journey to a Metal World” [Contract number NNM16AA09C] is part of the NASA Discovery Program mission to solar system targets. Trade names and trademarks of ASU and NASA are used in this work for identification only. Their usage does not constitute an official endorsement, either expressed or implied, by Arizona State University or National Aeronautics and Space Administration. The content is solely the responsibility of the authors and does not necessarily represent the official views of ASU or NASA.

|||
|--|--|
|Developers|Gavin Beaudry<br>Esaias Glasco<br> Grant Kelsay<br>Will Mastronardi<br>Chris Rogers|
|Academic Guidance|Vijay Suthar<br>Abdallah Moubayed<br>Kyle Cenatiempo|
|Sponsor|Cassie Bowman|
<br>

# Psyche Explorer VR
This project seeks to offer an educational VR experience of what it might be like to expore the surface of an asteroid like 16 Psyche. Users will be able to learn about its composition, and engage in learning modules about NASA's Psyche Mission, Stereoscopic Images in Space Exploration, and other Asteroid Missions.

||||
|---|---|---|
|Developer Platform|Unreal Engine 5.3|[Unreal Engine](https://www.unrealengine.com/en-US/download)|
|Packaging||[Packaging Project](https://dev.epicgames.com/documentation/en-us/unreal-engine/packaging-unreal-engine-projects?application_version=5.3)|
<br>

## Game Settings
||||
|---|---|---|
|Default Game Mode|VRGameMode|Game starts with the player in control of a VR Pawn. Compatible with multiple platforms:<br>-- Valve Index<br>-- Oculus Quest<br>-- HTC Vive<br>-- HP Mixed Reality|
|Alternate Game Mode|BP_FirstPersonGameMode|Game starts with the player in control of a First Person character. Designed for PC compatibility.|
|Window Mode| Default: Full Screen| Changeable in Game Settings Menu when playing|
|Resolution| Default: 1280| Options in Game Settings Menu:<br>-- 1280<br>-- 1600<br>-- 1920<br>-- 2560<br>-- 3840|
Graphics|Default: Epic|Options in Game Settings Menu:<br>-- Low<br>-- Medium<br>-- High<br>-- Epic<br>-- Ultra|
<br>

## VR Game Play
Upon selecting 'Enter Psyche' from the starting menu lobby, the player will begin near the landing craft and an interactive widget about the Psyche Mission. The player can walk around and explore the surface of the asteroid.<br><br>On their own, they may find the other Info Points, or they can press 'A' (on Occulus, or its equivalent on other headsets) to bring up the pause menu. Selecting the Teleport button will open a menu with options to teleport to a specific zone.
- Psyche Info Zone
  - Starting location, Psyche Mission interactive widget
- Satellite Info Zone
    - Satellite probe and asteroid mission interactive widget
- Stereo Images Zone
    - Stereo image interactive widget and gallery

<br>

## PC Game Play
Similar to the VR Game Play.<br>
To use the Teleport option, press "T" on the keyboard. To bring up the Pause Menu press "P" on the keyboard.<br>
<br>
PC players will have an opportunity to collect samples from the surface of the asteroid and return them to the landing craft to bring back to Earth for testing. <br>
Collectible samples will have a pop-up when near enough to them. Press "B" on the keyboard to collect the sample. Press "I" on the keyboard to see your inventory. Once samples have been collected, approach the landing craft and press "B". Your inventory and the craft storage will open. Drag and drop from your inventory to the storage. Press "B to close.