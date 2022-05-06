# Audio-Modding-Template
This is a template UE project for audio modding. 

All of the assets are reconstructed from the unpacked asset data meaning that they have the same properties as the original assets. 

Use is as simple as opening the `FSD.uproject`!

Thanks to the real MVP, `LongerWarrior` for creating the script bytecode in `UAssetGUI` that allows us to reconstruct the assets, and `Archengius` for creating the `UEAssetToolkit` plugin that generates the assets inside the project.

## Main branch
Most audio modders will want to use the template project on this branch. This does not include the sound cues and sound waves, but includes everything else. It means that you just need to make the sound cues yourself like normal.

## All-assets branch
This branch contains every sound asset in the Audio folder in the game, including sound cue graphs and sound waves. Switch to this branch if you want to copy the reconstructed sound cues with the reconstructed node graphs.