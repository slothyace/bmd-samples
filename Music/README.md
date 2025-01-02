# Music
## play-file.json (recommended)
By far the most stable of all music playing related commands. Allows user to attach a music file and it will play it in a VC.<br>
This is also the only offical recommended music playing command by Acedia.<br><br>
**Accepts**<br>
`.mp3`, `.flac`, `.wav`, `.ogg` and more, but I can't be arsed to test all of them.<br>
Any file format that starts with `audio/` will work.<br><br>
**Rejects** <br>
`.m4a` audio files seem to not work.<br>

## play-dlp.json (alternative)
Second working music command. It downloads the audio track from youtube using yt-dlp and reads the binary file to a addressable variable.<br>
The variable will then be played using the new "Play Binary Variable" action developed by me.<br>

## disconnect.json (optional)
Purges the queue and makes the bot leave the VC.
