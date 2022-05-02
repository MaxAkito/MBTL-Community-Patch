# MBTL-Community-Patch
A community translation patch for MBTL

Credits to Petrikow, Comun and fumei

## Editing guidelines

The behavior of how the game interprets the files differs on the category of file.

### Scripts & Win-quotes

The chatbox for the story-mode scripts and the win-quotes function the same.
The amount of characters possible to be parsed in a single line before overflowing is around 60-70 (the actual amount depends on difference in character width, hence the variability). Going over this amount will cause the text to clip outside the frame.
The chatbox supports 3 lines. However, the 3rd line needs to be shorter than the first 2. This is because otherwise it clips into the "click to read next" button. Try to keep it within 40-50 characters.

### Command list (cmddef.ini)

The command list is fairly simpke. There is however still a character limit to adhere to. An approximate character limit is around 40-45, but keeping under 40 is recommended.

### Battle voices (stringfile_battlevoice.xml)

The file marks the beginning and start of the battle voice strings with commas, so in order to use commas in the middle of text, that text must first be wrapped in quote ("") marks.
The amount of characters supported by the battle voice format is remarkably long, easily over 100 characters. Realistically speaking, it should be able to contain most translations without any problems.

###

## Progress

### Scripts

| Character       | Status                       | 
| :-------------- |:---------------------------- | 
| Arcueid   (000) | Initial editing done (Petri) |
| Hisui     (001) | Initial editing done (Petri) |
| Akiha     (002) | Initial editing done (Petri) |
| Shiki     (003) | Initial editing done (Petri) |
| Kohaku    (004) | Initial editing done (Petri) |
| Roa       (005) | Initial editing done (Petri) |
| Kouma     (006) | Initial editing done (Petri) |
| Maids     (007) | Initial editing done (Petri) |
| Noel      (008) | Initial editing done (Petri) |
| Vlov      (009) | Initial editing done (Petri) |
| Warc      (010) | Initial editing done (Petri) |
| Ciel      (011) | Initial editing done (Petri) |
| Saber     (012) | Initial editing done (Petri) |
| Miyako    (013) | Initial editing done (Petri) | 
| Boss Rush (013) | Initial editing done (Petri) |
| DA Noel   (014) | Initial editing done (Petri) |
| Aoko      (015) | Initial editing done (Petri) |

### Win-quotes

| Character       | Status                       | 
| :-------------- |:---------------------------- | 
| Arcueid   (000) | Initial editing done (Petri) |
| Hisui     (001) | Initial editing done (Petri) |
| Akiha     (002) | Initial editing done (Petri) |
| Shiki     (003) | Initial editing done (Petri) |
| Kohaku    (004) | Initial editing done (Petri) |
| Roa       (005) | Initial editing done (Petri) |
| Kouma     (006) | Initial editing done (Petri) |
| Maids     (007) | Initial editing done (Petri) |
| Noel      (008) | Initial editing done (Petri) |
| Vlov      (009) | Initial editing done (Petri) |
| Warc      (010) | Initial editing done (Petri) |
| Ciel      (011) | Initial editing done (Petri) |
| Saber     (012) | Initial editing done (Petri) |
| Miyako    (013) | Initial editing done (Petri) | 
| DA Noel   (014) | Initial editing done (Petri) |
| Aoko      (015) | Initial editing done (Petri) |

### Strings

| Subset                    | Status                 |
| :-------------------------| :----------------------|
| Command List (cmddef.ini) | Started editing (Petri)|