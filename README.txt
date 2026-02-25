Vimba Beam Profiler
===================

Beam profiling software for Allied Vision Alvium USB cameras.

REQUIREMENTS
------------
1. Allied Vision Vimba X SDK
   Download and install from:
   https://www.alliedvision.com/en/products/software/vimba-x-sdk/
   This provides the camera drivers required to detect and communicate
   with Alvium cameras.

2. Microsoft Visual C++ Redistributable 2022 (x64)
   Download from: https://aka.ms/vs/17/release/vc_redist.x64.exe

USAGE
-----
1. Connect your Alvium camera via USB 3.0 (required for full-frame streaming).
2. Run VimbaBeamProfiler.exe.
3. Select your camera from the device list and click Start.

NOTES
-----
- The camera MUST be connected to a USB 3.0 port with a USB 3.0 cable.
  USB 2.0 does not provide enough bandwidth.
- Logs are saved to the logs/ subfolder for troubleshooting.
