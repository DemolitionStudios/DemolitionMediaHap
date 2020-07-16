# Demolition Media Hap 2020

The industry-proven GPU accelerated Hap video codec playback solution for Unity.<br>
This repository contains the demo version and serves as an issue tracker.

![Playing 120 SD videos at once](https://dl.dropboxusercontent.com/s/b2mtso0zza3qq9r/hap_multiple_videos.png "")

# [Asset Store page](http://u3d.as/1Xw5)
# [Demo version (1.0.0 beta)](https://dl.orangedox.com/4ZxeAJ)
Note: **glitch effect (shown below) appear only in the demo version**.<br>
In the full Asset Store version the image is without any glitches <br>
![Demo version view](https://dl.dropboxusercontent.com/s/u1xl4a03bm39xim/unity_demo_2020_glitch.png "")

# [Demo version (0.9.6) - deprecated](https://dl.orangedox.com/P0jMYbmwyFxigMDQ8j)
Note: **pink stripes effect (shown below) appear only in the demo version**.<br>
In the full Asset Store version the image is without any glitches <br>
![Demo version view](https://dl.dropboxusercontent.com/s/4nrp0k5945fkhi9/unity_demo_pink_stripes.png "")

# [(new) Hap data rate calculator](http://demolition-studios.net/hap-calculator)
# [Documentation](https://docs.google.com/document/d/1fck8NRF_h5w_XbArmyuprLz1m2hY27W-sOqQB1cvqZs/edit?usp=sharing)
# [Unity forum thread](https://forum.unity3d.com/threads/released-demolition-media-hap-multi-platform-8k-60fps-gpu-video-playback.456068/)

# Features:
— (new) Reworked playback loop - even more smooth playback
— (new) Improved stability and performance - can play even more videos now
— (new) Unlocked decode threads number: it scales with the the CPU concurrency capabilities
— (new) Frees your render and main threads: texture updating is done completely in background threads
— (new) Better playback speed control
— (new) Multichannel audio support (5.1 has been tested)
— (new) Only 10Mb required for the plugin DLLs
— Hardware accelerated Hap video playback without any external codecs installation needed. Both Hap and Hap Q are supported.<br>
— Low CPU/memory usage. Frames are decompressed on the GPU.<br>
— Play 4k @ 120 fps or 8k @ 60 fps or 10k @ 50fps videos, play multiple videos at once. Extremely fast frame-precise seeking.<br>
— Transparent videos with Hap Alpha and Hap Q Alpha codecs. First plugin to support Hap Q Alpha in Unity.<br>
— Chunked Hap support for even faster multi-threaded decoding.<br>
— Non-multiple of 2 video resolutions <br>
— Only Windows/DX11 works at the moment in 2020 version ~~Works with the majority of graphics interfaces: DX9, DX11, OpenGL, Metal on desktop platforms. DX12 on the way!~~<br>
— ~~Both 32-bit and 64-bit builds supported! Even on OS X!~~<br>
— Audio output through the Unity Native Audio plugin and AudioSource.<br>
— Suits for both programmers and artists: C# API along with IMGUI/uGUI wrappers provided.<br>
— Example scenes with the typical usage scenarios.<br>
— Free demo version available.<br>

# Requirements
— Unity 2019-2020.x<br>
— Windows 8.1/10<br>
— ~~OS X 10.9 and above~~<br>
<br>
This software uses code of <a href=http://ffmpeg.org>FFmpeg</a> licensed under the <a href=http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html>LGPLv2.1</a> and its source can be downloaded <a href=https://github.com/DemolitionStudios/FFmpeg>here</a>
