# Demolition Media Hap

The industry-proven GPU accelerated Hap video codec playback solution for Unity.<br>
This repository contains the demo version and serves as an issue tracker.

(new) **Much better quality with the new Hap R codec. It's really close to the original video now!<br>
[Quality comparison & encoder](https://jokyohapencoder.com/jokyo-hap-meencoder-hap-encoder-plugin-for-adobe-media-encoder-and-premiere-pro/)**<br>

![Playing 120 SD videos at once](https://dl.dropboxusercontent.com/s/b2mtso0zza3qq9r/hap_multiple_videos.png "")

# Useful links
## [Asset Store page](http://u3d.as/1Xw5)
## [Documentation](https://docs.google.com/document/d/1fck8NRF_h5w_XbArmyuprLz1m2hY27W-sOqQB1cvqZs/edit?usp=sharing)
## [Unity forum thread](https://forum.unity3d.com/threads/released-demolition-media-hap-multi-platform-8k-60fps-gpu-video-playback.456068/)
## [(new) A better encoder for Abode AfterEffects/Premiere Pro](https://jokyohapencoder.com/)
<!---## [Hap data rate calculator](https://demolitionstudios.github.io/hap-data-rate-calculator.html))--->

## [(updated) Demo version (1.2.0)](https://1drv.ms/u/s!AhRsdPdtJl1uhp0g5pEs0kNHqYZvPQ?e=hV0oYY)
Note: **glitch effect (shown below) appear only in the demo version**.<br>
In the full Asset Store version the image is without any glitches <br>
![Demo version view](https://am3pap002files.storage.live.com/y4m8hayD8bD3nKWpfxlBTkN8mFHEmT_jELrUUIF_Uc-sduDILVrl99meEAueUIdH9natGUg1_NZncqBa5oPaeH56Ct3GwGUOrCOn_qzlx4n9GAqZYdrA4ubkx7z_k9hOiJAA1ixkVZVds1NwlUQc0wkCV0oWiXBMd21GuxryNEjip91ANM6PkcpCZYjkFqy4DhN?width=1566&height=884&cropmode=none "")



# Features:
— (new) Reworked playback loop - even more smooth playback<br>
— (new) Improved stability and performance - can play even more videos now<br>
— (new) Unlocked decode threads number: it scales with the the CPU concurrency capabilities<br>
— (new) Frees your render and main threads: texture updating is done completely in background threads<br>
— (new) Better playback speed control<br>
— (new) Multichannel audio support (5.1 has been tested)<br>
— (new) Only 10Mb required for the plugin DLLs<br>
— Hardware accelerated Hap video playback without any external codecs installation needed. Both Hap and Hap Q are supported.<br>
— Low CPU/memory usage. Frames are decompressed on the GPU.<br>
— Play 4k @ 120 fps or 8k @ 60 fps or 10k @ 50fps videos, play multiple videos at once. Extremely fast frame-precise seeking.<br>
— Transparent videos with Hap Alpha and Hap Q Alpha codecs. First plugin to support Hap Q Alpha in Unity.<br>
— Chunked Hap support for even faster multi-threaded decoding.<br>
— Non-multiple of 2 video resolutions <br>
— Only Windows/DX11 works in the latest version. Request others via demolition.studios.rocks@gmail.com ~~Works with the majority of graphics interfaces: DX9, DX11, OpenGL, Metal on desktop platforms. DX12 on the way!~~<br>
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
