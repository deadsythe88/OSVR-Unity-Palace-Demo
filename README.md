# OSVR-Unity Palace Demo

Project source hosted at: https://github.com/OSVR/OSVR-Unity-Palace-Demo

1) A recent build of [OSVR-Core](http://osvr.github.io/using/) is required to run this demo.

2) In the OSVR-Core Snapshot download, navigate to the bin folder to find:

osvr_server.exe -- this must be running for OSVR to work.

osvr_server_config.json -- this must be configured for your device. By default it will work with the HDK. See included examples in the bin and share folders for other configurations.

Add any [device plugins](http://osvr.github.io/using/) to the osvr-plugins-0 folder. 

3) Connect your device to and start osvr_server.exe, not necessarily in that order.

# RenderManager / DirectMode
OSVR-Unity supports Direct Mode, Timewarp, and Distortion Correction via OSVR RenderManager. Direct Mode requires Unity 5.2+ and NVIDIA graphics cards with the latest drivers* (364.xx drivers are not working at the time of this edit, revert to 362.00). NVIDIA specifies that a 700 series card or better is required, but our testing indicates that select lower cards may also be compatible. Tested and working on a 560M.

#Android
Here is an [Android apk](https://github.com/OSVR/OSVR-Unity-Palace-Demo/releases/tag/v0.1.1-android) built with this project.

See the [Android branch README](https://github.com/OSVR/OSVR-Unity-Palace-Demo/blob/androidPalace/README.md) for more information.

##Version Changes
### v0.6.10.12 
> (July 18, 2016)

- Update to OSVRUnity v0.6.10.12 (build 424)
- Adds server autostart feature on Windows, toggled by boolean in ClientKit script.
- Adds OSVR Editor Utilities

### v0.6.9
> (June 9, 2016)

- Update to OSVR-Unity v0.6.9, fixes scene switching bug in direct mode.

### v0.6.8.6
> (May 31, 2016)

- Update to RenderManager v00_06_43-81, which includes new distortion mesh

### v0.6.8.5
> (May 23, 2016)

- Update to OSVRUnity v0.6.8.2.
- Update to RenderManager v00_06_43-66
- Fixed colored table bug.

### v0.6.8.2
> (April 22, 2016)

- Update to OSVRUnity v0.6.8.2.
- Fixed bug causing startup hangup on some systems

### v0.6.8 
> (April 6, 2016)

- Update to OSVRUnity v0.6.8.
- Changed to mobile/diffuse shader for most surfaces.
- Removed fire particles and excessive lighting.
