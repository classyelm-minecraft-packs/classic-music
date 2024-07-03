# classic-music

The Classic Music resource pack is a nostalgia sound pack for Minecraft: Java Edition. It brings back the selection of C418 tracks that existed in the Update Aquatic version (1.13) of Minecraft. It does so by modifying the existing Minecraft sound events to only include music by C418. If you would like to know more about how it works, please read the additional info below.

## How does it work?

Essentially, it boils down to the customization that Minecraft offers regarding sounds in resource packs. I define a list of allowed tracks that can be played per existing music sound event (e.g. the music players here while in creative mode, the music played in specific biomes like the deep dark, swamps, the nether, the end, etc.). This can all be done with the existing music in-game. This means that I do not need to add the music in the resource pack and avoid the copyright/trademark concerns by not distributing copies of the music.

This works technically by overwriting existing sound events for music using the sounds.json file in the minecraft namespace. If you would like to know more about this file, I strongly suggest reading [the information documented on the Minecraft Wiki](https://minecraft.wiki/w/Sounds.json#Java_Edition). If new music sound events are added in future Minecraft versions, the sounds.json list will just have to be extended for those new events.

## Does this overwrite music discs?
No, it does not. I specifically did not modify the music played by music discs since you can choose which music you would like to listen to. The same cannot be said for the newer ambient music tracks added since Minecraft 1.13.

## Is it compatible with other resource packs that modify default music sound events?
Unfortunately, no. In order to prevent other tracks from playing, I had to specifically replace the entirety of the music defined per sound event. That being said, it is possible to support custom tracks if you would like additional music. I would recommend reading more about the sounds.json file on the Minecraft Wiki and updating this resource pack's sounds.json file with the custom music you would like included.

## Related links

* [Post on PlanetMinecraft for Classic Music]()