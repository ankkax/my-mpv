# my-mpv
## Some information for current setup

when you open your folder it makes automically playlist, when you open video from from that folder it will ask if you want to continue to episode you left of.

## Guide to use my mpv settings
requires
+ [yt-dlp](https://github.com/yt-dlp/yt-dlp) 
+ [ffmpeg](https://github.com/FFmpeg/FFmpeg)
+ [mpv-mpris](https://github.com/hoyon/mpv-mpris) for media controls

## Youtube downloads
+ configs `$HOME/.config/mpv/script-opts/youtube-download.conf`
+ shortcut config `$HOME/.config/mpv/input.conf`
+ current download location `$HOME/Videos/youtube/`

+ CTRL + d	downloads youtube video as mp4
+ CTRL + a	youtube audio only
+ CTRL + a	download subtitle
+ CTRL + i	download embed subtitles

## Videocut
![Horizon](/screenshot/videocutter.png)
* configs ~/.config/mpv/script-opts/videoclip.conf
+ current location for cutted videos `$HOME/Videos/`
+ current location for cutted audio  `$HOME/Music/`
press c to start videocut menu

## Some links to scripts

+ [youtube-download](https://github.com/cvzi/mpv-youtube-download)
+ [videoclip](https://github.com/Ajatt-Tools/videoclip)
