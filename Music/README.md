# Music
## play-file.json (recommended)
By far the most stable of all music playing related commands. Allows user to attach a music file and it will play it in a VC.<br>
This is also the only offical recommended music playing command by Acedia.<br>
| **Accepts** |
| :--- |
| Any audio attachment with the format starting with `audio/`. |

| **Rejects**|
| :--- |
`.m4a` files seem to not work. |

## play-yt.json (recommended)
After the YouTube audio fix released on 06Jan2025, it has become more stable and thus, can be recommended for use.<br>
A new updated version of the command has been added.

## play-dlp.json (alternative)
Second working music command. It downloads the audio track from youtube using yt-dlp and reads the binary file to a addressable variable.<br>
The variable will then be played using the new "Play Binary Variable" action developed by me.<br>



## disconnect.json (optional)
Purges the queue and makes the bot leave the VC.
