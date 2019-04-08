<p align="center">
<b>OpenCast 3D Printable Brace</b><br>
oOpen Source<br><br>
<br>🐦 <a href="https://twitter.com/mkmeorg">Twitter</a>
| 📺 <a href="https://www.youtube.com/mkmeorg">YouTube</a>
| 🌍 <a href="https://mkme.org">mkme.org</a><br>
<br>
Support this project and become a patron on <a href="https://www.patreon.com/EricWilliam">patreon.com/EricWilliam</a>.<br>
Chat: <a href="https://discord.gg/j9S4Fgv">Discord</a></b>!
</p>


# OpenCast
3D Printable medical casts and braces using XBox 360 Kinect Camera/scanner

<p align="center">
  <img src="https://github.com/MKme/OpenCast/blob/master/Pics/CURA%20Preview.PNG" width="700"/>
</p>

This project will contain the instructions, examples and files for the OpenCast DIY 3D prinable casts & braces using an XBOX Kinect camera. 


### The goal:

Allow anyone, anywhere to easily create a viable cast or brace with a cheap camera and 3D printer. The cast is perfectly formed to the patients body, breathes and can even be worn while bathing. This method can also be used for creating a form-fitted prosthetic device for patients as well.

Most printed casts online seem to be proprietary and closed source- this instruction and files I make freely available for anyone.

### Prerequisite Software Installs

Install KinectSDK-v1.8 - IMPORTANT you use version 1.8 

Install Skanect-1.9.1 

Install Meshmixer

Plug in your Kinect camera. Windows will mess around installing drivers for awhile. If it still doesnt show up in Skanect- go in to
Windows Device manager and expand the sections for the Kinect. This seems to nudge windows into finishing the install (it did for me)

## Scan and print as per the video here:
--------------video forthcoming---------------


## In MeshMixer:

Import your scan

Slice top and bottom as needed for fingers/toes etc (Important to select NO FILL when cut)

Offset whole model 5mm

Separate shells

Delete inside one

Select whole model

Reduce 50%

Create your Pattern- If pattern too tigh- reduce further untill patern suits you

Set pattern width to around 4mm

Select all and Reduce 50%

Analyze and repair

Export to stl

Use Netfab if needed to further repair or make stl smaller in file size
