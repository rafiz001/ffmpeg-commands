# ffmpeg-commands
## speed up video:
> ffmpeg -i vid.MP4 -filter:v "setpts=PTS/4" -r 30 -an vid_fast.MP4
- Presentation Time Stamps (PTS): each frame is displayed dividing by 4 reduces the time between frames
- r: frame rate: 30fps
- an: audio none

