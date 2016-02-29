# Hydra-Remote
HYDRA Remote Desktop/Desktop Sharing

A remote desktop and desktop sharing utility being developed as the first application to use HUT (HYDRA UI Toolkit). This uitility is meant to be able to compete with Valve's In-Home Streaming in terms of quality and performance, and work between Windows and Linux, Linux and Linux, Windows and Windows and possibly Linux and Browser, and Windows and Browser (may have a browser based client in the future since HUT will support WebGL)

This utility is most likely going to be heavily based on FFMPEG and loosely based on Synergy and Mumble initially.

It is supposed to support minimal-latency HID sharing (Keyboard, Mouse, Controller and hopefully Tablets), low-latency audio sharing (what Mumble's code will be used for as an example), and low-latency high quality video streaming.

Video Codecs will include VP9, H264 and H265, Audio codecs will include Opus, MP3, FLAC and possibly AAC.

I may also possibly develop file-sharing capabilities to be able to avoid SAMBA and allow for more advanced clipboard sharing, as well as a proof of concept Hydra-Remote-Rendering which would (using HYDRA DE) use the guest PC's hardware to render the host PC's desktop environment and some applications.

This application will support Wayland, and most likely also X11, and will be developed with C and

To Do:

Markup : 
* Create the Hydra Remote base application working through CLI
  * Implement Keyboard and Mouse Sharing (Linux to Windows)
  * Implement Sound Sharing (Windows to Linux)
  * Implement Clipboard Sharing
  * Implement Video Streaming (Windows to Linux)
* Develop HUT and with it create a GUI for Hydra Remote
* Finish Implementing all Video and Audio codecs, and optimize video and sound performance and quality
* Make the code fully compatible between Windows and Linux back and forth
* Provide toggleable overlay tool to measure KB/s bandwidth use and presets for sharing over LAN and over Internet.
* Review and optimize code
* Implement Security
