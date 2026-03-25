Vimba Beam Profiler
===================

Beam profiling software for Allied Vision Alvium USB cameras.

REQUIREMENTS
------------
1. Allied Vision Vimba X SDK
   Download and install from:
   https://www.alliedvision.com/en/products/software/vimba-x-sdk/
   Plug in your Alvium camera via USB before running the installer so
   that the correct drivers are installed automatically.
   This provides the camera drivers required to detect and communicate
   with Alvium cameras.

2. Microsoft Visual C++ Redistributable 2022 (x64)
   Download from: https://aka.ms/vs/17/release/vc_redist.x64.exe

USAGE
-----
1. Connect your Alvium camera via USB 3.0 for best performance.
2. Run VimbaBeamProfiler.exe.
3. Select your camera from the device list and click Start.

NOTES
-----
- USB 3.0 is recommended for full-speed streaming. USB 2.0 connections and
  bandwidth-limited hubs will work but at a reduced frame rate. 
  Hardware decimation may be necessary for USB 2.0.
- Logs are saved to the logs/ subfolder for troubleshooting.
