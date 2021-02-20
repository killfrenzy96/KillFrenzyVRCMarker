# KillFrenzy's Marker
The marker from KillFrenzy's Avatar Keyboard: https://github.com/killfrenzy96/KillFrenzyVRCAvatarKeyboard

# Prerequisites
- Unity 2018.4.20f1
- VRCSDK3
- An existing working avatar

# Installation to Custom Avatar
1. Import the "KillFrenzyMarker.unitypackage" into your project.
2. Insert the prefab into your scene. The prefab is located in "Assets/KillFrenzy/Animations/Marker/Examples/MarkerExampleParts.unity".
3. Unpack the prefab by right clicking "MarkerExampleParts" and pressing "Unpack Prefab".
4. Move the game object "KillFrenzyMarkerEffects" into the root of your own avatar.
5. Move the game object from "Right wrist/Joint_Marker_R" into your own avatar's right wrist. Position this object over the tip of your avatar's right index finger.
5. Move the game object from "Left wrist/Joint_Marker_L" into your own avatar's left wrist. Position this object over the tip of your avatar's left index finger.
6. Browse to your VRC Avatar Descriptor.
7. Customize your PlayableLayers.
8. Insert the animator controller from "Assets/KillFrenzy/Animations/Marker/VRCAC_MarkerControllerFX" into the FX layer. You may use the Action controller version instead if you are already using the FX layer (or use tools to combine the FX animators).
9. Customize your Expressions.
10. Insert the VRC Expression Menu from "Assets/KillFrenzy/Animations/Marker/VRCEM_MarkerMenu" into the the Menu.
11. Insert the VRC Expression Paramaters from "Assets/KillFrenzy/Animations/Marker/VRCEP_MarkerParams" into the the Parameters.
12. Open the VRCSDK Control Panel and login to your account.
13. Build & Publish your custom model.

# Useful Tools
- VRCAvatars3Tools: This tool can be used to merge multiple animators together. Useful if you wanted to merge the keyboard into an existing animator for the FX layer. https://booth.pm/ja/items/2207020