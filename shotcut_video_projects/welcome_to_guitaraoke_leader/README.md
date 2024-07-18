
How to add a `cover art` to a mp4 file with ffmpeg

download ffmpeg for windows : <https://www.ffmpeg.org/>  


ffmpeg -i "Welcome - guitaraoke.mp4" -i Poster.png -map 1 -map 0 -c copy -disposition:0 attached_pic out.mp4
