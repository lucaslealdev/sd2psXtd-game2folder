# sd2psXtd Game2Folder.ini

This repository offers a pre-compiled Game2Folder.ini including all (I think) ps1 games. The list includes region variants, merge 2+ disc games, but excludes demos and prototypes.

It is possible that some names are too long and might be ignored for that reason even if I tried making them all small names. If you find yourself in that situation, please open an Issue, and remember saying what game and serial it is (there is a tab called Issues [here](https://github.com/lucaslealdev/sd2psXtd-game2folder/issues)).

## General: Game2Folder mapping

There are some games, that share save data for multiple game ids (like the Singstar series etc). For these cases, a custom game to folder mapping can be created.

If a game with a mapped id is loaded, instead of using the game id based folder, the mapped folder is used for storing the card.

The mapping needs to be defined in ```.sd2psx/Game2Folder.ini``` in the following way:

```ini
[PS1]
SCXS-12345=FolderName1
[PS2]
SCXS-23456=FolderName2
```

*Note: Be aware: Long folder names may not be displayed correctly and may result in stuttering of MMCE games due to scrolling.*
*Note 2: Make sure there is an empty line at the end of the ini file.*
