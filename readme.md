# foobar

my fb2k config for fb2k 2.x

![image](https://user-images.githubusercontent.com/1000503/200449214-3c742da8-39c6-4a74-ad87-7696de1e92a9.png)

#@ colors

background 42,42,42
red: 255,87,6
playing: 213, 69, 0
alt: 45, 157, 177
alt2: 57, 155, 177
alt3: 45, 122, 138

## lyrics
normal: 255, 128, 0
highline: 255, 85, 0

fallback
```
$rgb(255,85,0)%title%

%artist%
%album%

%playback_time% / %length%

[%search_state%]$rgb(255,85,0)[%search_progress%'%']
```
## special
d3d9 is dxvk-async for better performance of waveform seekbar

