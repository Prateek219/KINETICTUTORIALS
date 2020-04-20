# KINETIC TUTORIALS
## INTRODUCTION TO KINETIC
Kinect is a motion sensing input device by Microsoft for the Xbox 360 video game console and
Windows PCs. Based around a webcam-style add-on peripheral for the Xbox 360 console, it
enables users to control and interact with the Xbox 360 without the need to touch a game
controller, through a natural user interface using gestures and spoken commands.The project is
aimed at broadening the Xbox 360's audience beyond its typical gamer base. Microsoft released
Kinect software development kit for Windows 7 in June, 2011. This SDK allows developers to
write Kinecting apps in C++/CLI, C#, or Visual Basic .NET.


## REQUIREMENTS
- Kinect for Xbox 360 / Kinect for Windows sensor
- Computer with a dual-core, 2.66-GHz or faster processor
- Windows 7–compatible graphics card that supports DirectX 9.0c capabilities
- 2-GB RAM (4-GB RAM recommended)
- Visual Studio 2010 Express (or other 2010 edition)
- Microsoft .NET Framework 4.0
- For C++ Skeletal Viewer samples:
- Microsoft DirectX SDK June 2010 or later version
- Microsoft DirectX 9
- For Speech sample (x86 only):
- Microsoft Speech Platform SDK and Runtime, version 10.2 (x86 edition)
- Kinect for Windows Runtime Language Pack, version 0.9

## GETTING STARTED WITH MICROSOFT KINETIC SDK 1.5:
Kinect SDK includes drivers, rich APIs for raw sensor streams and human motion tracking,
installation documents, and resource materials. Kinect SDK is a freeware and can be
downloaded at :
http://www.softpedia.com/progDownload/Kinect-SDK-Download-190054.html
Kinect For Windows Developer Toolkit may be downloaded at :
http://www.softpedia.com/progDownload/Kinect-for-Windows-Developer-Toolkit-Download-217211.html
## TO INSTALL THE SDK:
Make sure the Kinect sensor is not plugged into any of the USB ports on the computer.
- If you installed a previous version of the Kinect for Windows SDK, you must uninstall it
before proceeding.
- Remove any other drivers for the Kinect sensor.
- Close Visual Studio. You must close Visual Studio before installing the SDK and then
restart it after installation is complete to pick up environment variables that the SDK
requires.
- Once the SDK has completed installing successfully, ensure the Kinect sensor is plugged
into an external power source and then plug the Kinect sensor into the PC's USB port.
The drivers will load automatically.
- The Kinect sensor should now be working correctly.
- To develop speech-enabled Kinect applications, install the Microsoft Speech SDK.
## TESTING YOUR SDK:
### Go to Start Menu -> Developer Toolkit For Kinect .Now, install and run Kinect Explorer.
When you run this sample, you see the following:
- The depth stream, showing background in grayscale and different people in different
colors. Darker colors mean more distance from the sensor. People are detected only if
their entire body fits within the captured frame
- The skeleton stream, showing tracked skeletons only if the entire body of at least one
person fits within the captured frame.
- The color stream, showing the video being captured.
- The frame rate of the data capture.
