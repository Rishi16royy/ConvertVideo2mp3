# ConvertVideo2mp3
Download youtube playlist/video and convert it to mp3
## Setup
1. ```brew install youtube-dl```
2. ```brew install ffmpeg```

## Command
 ```youtube-dl -f bestaudio --embed-thumbnail -x --audio-format mp3 --audio-quality 0 -o '%(title)s.%(ext)s' url```
