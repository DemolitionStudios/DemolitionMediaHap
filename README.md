![image](https://github.com/DemolitionStudios/DemolitionMediaHap/assets/33001/a15fd165-43eb-4f0e-aefc-704d850d9f19)# Demolition Media Hap

The industry-proven GPU accelerated Hap video codec playback solution for Unity.<br>
This repository contains the demo version and serves as an issue tracker.

![Playing 120 SD videos at once](https://dl.dropboxusercontent.com/s/b2mtso0zza3qq9r/hap_multiple_videos.png "")

# Useful links
## [Asset Store page](https://u3d.as/2W1t)
## [Sample videos](https://mega.nz/folder/DAp1GThA#Iy-KDvLD-io6NOqW6WRKbQ)
## [Documentation](https://docs.google.com/document/d/1fck8NRF_h5w_XbArmyuprLz1m2hY27W-sOqQB1cvqZs/edit?usp=sharing)
## [Unity forum thread](https://forum.unity3d.com/threads/released-demolition-media-hap-multi-platform-8k-60fps-gpu-video-playback.456068/)
## [(new) Optimized standalone encoder with new Hap R/Hap H codecs](https://github.com/DemolitionStudios/shutter-encoder)
## [Encoder with new Hap R codec for Abode After Effects/Media Encoder](https://jokyohapencoder.com/)
<!---## [Hap data rate calculator](https://demolitionstudios.github.io/hap-data-rate-calculator.html))--->

# [(updated) Demo version (3.1.0)](https://mega.nz/file/TQAQCTpJ#NyxGoJYY3aScNIr8-APSqbBcrcZ7AMokvKQE9pzpXVU)
Note: **watermark effect (shown below) appear only in the demo version**.<br>
In the full Asset Store version the image is without any glitches <br>
![image](https://github.com/DemolitionStudios/DemolitionMediaHap/assets/33001/9ba93a1e-f0fd-4050-9c52-cd0ff5b2c199)





# Features:
— (new) Much better quality with the new Hap R codec. It's really close to the original video now!<br>
— (new) Reworked playback loop - even more smooth playback<br>
— (new) Improved stability and performance - can play even more videos now<br>
— (new) Unlocked decode threads number: it scales with the the CPU concurrency capabilities<br>
— (new) Frees your render and main threads: texture updating is done completely in background threads<br>
— (new) Better playback speed control<br>
— (new) Multichannel audio support (5.1 has been tested)<br>
— Hardware accelerated Hap video playback without any external codecs installation needed. Both Hap and Hap Q are supported.<br>
— Low CPU/memory usage. Frames are decompressed on the GPU.<br>
— Play 4k @ 120 fps or 8k @ 60 fps or 10k @ 50fps videos, play multiple videos at once. Extremely fast frame-precise seeking.<br>
— Transparent videos with Hap Alpha and Hap Q Alpha codecs. First plugin to support Hap Q Alpha in Unity.<br>
— Chunked Hap support for even faster multi-threaded decoding.<br>
— Non-multiple of 2 video resolutions <br>
— Audio output through the Unity Native Audio plugin and AudioSource.<br>
— Suits for both programmers and artists: C# API along with IMGUI/uGUI wrappers provided.<br>
— Example scenes with the typical usage scenarios.<br>
— Free demo version available.<br>

# Requirements
— Unity 2019-2022<br>
— Windows 8.1/10<br>
<br>
This software uses code of <a href=http://ffmpeg.org>FFmpeg</a> licensed under the <a href=http://www.gnu.org/licenses/old-licenses/lgpl-2.1.html>LGPLv2.1</a> and its source can be downloaded <a href=https://github.com/DemolitionStudios/FFmpeg>here</a>
