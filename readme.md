# foobar

my fb2k config for fb2k 2.x

![image](https://user-images.githubusercontent.com/1000503/200500625-4f4470ab-ef68-47a3-8ba6-c9aa6b9461e2.png)

font: Noto Sans CJK JP

## colors

background 42,42,42
darkbg: 28,28,28
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

