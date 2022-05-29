# Audio-Modding-Template
This is a template UE project for audio modding. 

All of the assets are reconstructed from the unpacked asset data meaning that they have the same properties as the original assets. 

Use is as simple as opening the `FSD.uproject`!

Thanks to the real MVP, `LongerWarrior` for creating the script bytecode in `UAssetGUI` that allows us to reconstruct the assets, and `Archengius` for creating the `UEAssetToolkit` plugin that generates the assets inside the project.

## Main branch
Most audio modders will want to use the template project on this branch. This does not include the sound cues and sound waves, but includes everything else. It means that you just need to make the sound cues yourself like normal.

## All-assets branch
This branch contains every sound asset in the Audio folder in the game, including sound cue graphs and sound waves. Switch to this branch if you want to copy the reconstructed sound cues with the reconstructed node graphs.

## Commit Tags
There are 3 types of commits that will be made to inform when you might want to upgrade to the newest version of the template:
* **MAJOR**: When you absolutely MUST upgrade to the newest. This will likely be for major game updates.
* **MINOR**: When you should consider updating as there are fixes or improvements, but you don't have to.
* **PATCH**: When the change is so small that you can have a look at what changed to see if you should bother to update, but doesn't really matter if you don't want to.
* **README**: Just an update to the README.md file.