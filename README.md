mp3-to-mp4
==========================

Convert mp3 and png image to mp4 for upload on youtube thanks mmpeg.

Convert mp3 to mp4 directly using mp3 id3 image + 720p upscale

Thanks user ron999 in this tread http://ubuntuforums.org/showthread.php?t=1502537


## Usage

`./mp3-png-to-mp4.sh "my image.png" "my sound.mp3"`

`./mp3-to-mp4.sh "my sound.mp3"`

To convert entire folder from mp3 to mp4, use:

`for f in ./folder-name/*; do ./mp3-to-mp4.sh "$f"; done`

## Requirements

mmpeg, sox (http://sox.sourceforge.net/sox.html) and unix-like machine :)


