# Demolition Media Hap

The industry-proven GPU accelerated Hap video codec playback solution for Unity.<br>
This repository contains the demo version and serves as an issue tracker.

![Playing 120 SD videos at once](https://dl.dropboxusercontent.com/s/b2mtso0zza3qq9r/hap_multiple_videos.png "")

# Useful links
## [Asset Store page](https://u3d.as/2W1t)
## [Documentation](https://docs.google.com/document/d/1fck8NRF_h5w_XbArmyuprLz1m2hY27W-sOqQB1cvqZs/edit?usp=sharing)
## [Unity forum thread](https://forum.unity3d.com/threads/released-demolition-media-hap-multi-platform-8k-60fps-gpu-video-playback.456068/)
## [(new) Optimized standalone encoder with new Hap R codec](https://github.com/DemolitionStudios/shutter-encoder)
## [Encoder with new Hap R codec for Abode After Effects/Media Encoder](https://jokyohapencoder.com/)
<!---## [Hap data rate calculator](https://demolitionstudios.github.io/hap-data-rate-calculator.html))--->

## [<span style="color:blue">(updated) Demo version (3.0.0)</span>](https://mega.nz/file/vZYWVaSI#Xe2mdwayDbSFp16Dlddv2JRn9Jxr0sNK9MnYQGQ1AGg)
Note: **glitch effect (shown below) appear only in the demo version**.<br>
In the full Asset Store version the image is without any glitches <br>
![Demo version view](https://am3pap002files.storage.live.com/y4m8hayD8bD3nKWpfxlBTkN8mFHEmT_jELrUUIF_Uc-sduDILVrl99meEAueUIdH9natGUg1_NZncqBa5oPaeH56Ct3GwGUOrCOn_qzlx4n9GAqZYdrA4ubkx7z_k9hOiJAA1ixkVZVds1NwlUQc0wkCV0oWiXBMd21GuxryNEjip91ANM6PkcpCZYjkFqy4DhN?width=1566&height=884&cropmode=none "")



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
