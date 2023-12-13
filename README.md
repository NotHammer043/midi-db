<img src="https://i.imgur.com/PUR9ROE.png" alt="nanoMIDI" width="200px"/>

> nanoMIDI's Official MIDI Repository
______________________________________________

## Links
Youtube: https://www.youtube.com/@nanoMIDI

Discord: https://discord.gg/QnRctBgagZ

Gitea: https://git.nanomidi.net/nanoMIDI/midi-db

Official Website: https://nanomidi.net

______________________________________________

## Contributing
1. Create a fork
2. Add the MIDI file(s) [`/midis`] and image(s) [`/images`] that you would like to add.
3. Add metadata with correct `json` formatting in `midiData.json`.<br>
   Use `schema.json` as a reference!
4. Make a pull request inside of the fork.


Enjoy!

Example:
```
[
  {
    "name": "World's Smallest Violin",
    "artists": "AJR",
    "midiFilename": "Worlds_Smallest_Violin.mid",
    "imageFilename": "Worlds_Smallest_Violin.png",
    "githubUser": "CrimsonfiedOfficial"
    "arrangement": "F.I.R.E."
  },
  {
    "name": "Left and Right",
    "artists": "Charlie Puth, Jung Kook",
    "midiFilename": "Left_and_Right.mid",
    "imageFilename": "Left_and_Right.png",
    "githubUser": "ThinLiquid"
    "arrangement": "" // Leave blank if unknown
  }
]
```