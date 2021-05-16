# Dances by No Logic David

Dances by No Logic David
recorded for the metagen project (http://metagen.ai) using lox9973's shadermotion tool in VRChat

Released with a CC BY license.

## Reproduction steps

How to recreate?

`youtube-dl https://www.youtube.com/playlist?list=PLmwqDOin_Zt4WCMWqoK6SdHlg0C_WeCP6  --prefer-free-formats --audio-format wav  --recode-video webm`

Import bvh into a recent Blender with sync fps and scene time.

Run script to generate a mesh from bones.

Bake actions.

Only check overwrite current action and clean curves.

Bake Data of Pose.

Export as gltf.

At this point the glb cannot be imported into Blender.

Open Godot Engine 4.0 custom engine and then export a glb.

