# Download links
- [Media Player Classic - Home Cinema 64-bit Installer](https://github.com/clsid2/mpc-hc/releases/latest) ([~~deprectated link~~](https://mpc-hc.org/downloads/))
- [XySubFilter x64](https://github.com/pinterf/xy-VSFilter/releases/latest)  ([~~deprectated link~~](https://github.com/Cyberbeing/xy-VSFilter/releases))
- [madVR](http://madshi.net/madVR.zip)

# Installation
1. Uninstall all codec packs, previous instances of the aforementioned, and the like, and delete their settings if prompted.
2.  Reboot.
3.  Install MPC-HC with default settings.
4.  Extract the XySubFilter archive into a new "XySubFilter" directory in your *"C:\Program Files"* directory.
5.  Right-click on "Install_XySubFilter.bat" in the "XySubFilter" directory you just populated, and then click on "Run as administrator".
6.  Extract "madVR.zip" into a new "madVR" directory in your "C:\Program Files" directory.
7.  Right-click on "install.bat" in the "madVR" directory you just populated, and then click on "Run as administrator".
8.  Start MPC-HC, go to "View" &rarr; "Options..." &rarr; "Playback" &rarr; "Output", and select "madVR" under "DirectShow Video"
    and "XySubFilter" under "Subtitle Renderer".
9.  Go to "View" &rarr; "Options..." &rarr; "Internal Filters", click on "Video decoder", and select "None" in the
    "Hardware Decoder to use" dropdown menu in the "Hardware Acceleration" section. Click on "OK", and click on "OK".
10. Play a video file, go to "Play" &rarr; "Filters", click on "madVR", and click on "Edit Settings".
11. Go to "processing" &rarr; "artifact removal" and check "reduce banding artifacts".
12. Go to "processing" &rarr; "zoom control" and set "move subtitles:" to "... into active video area".
13. Go to "scaling algorithms" and select "Reconstruction" in the "chroma upscaling" submenu, "SSIM" with "2D - strength: 100%",
    "activate anti-ringing filter", and "scale in linear light" in the "image downscaling" submenu, "double luma resolution" with
    "super-xbr, sharpness: 75" in the "image doubling" submenu, "Jinc" with "activate anti-ringing filter" and "scale in sigmoidal light"
    in the "image upscaling" submenu, and "SuperRes" at setting 2 in the "upscaling refinement" submenu.
14. Go to "rendering" &rarr; "general settings" and check "use Direct3D 11 for presentation" and "use a separate device for presentation".
15. Go to "rendering" &rarr; "dithering" and select "Error Diffusion - option 2".
16. Go to "rendering" &rarr; "trade quality for performance" and uncheck all but "optimize subtitle quality for performance instead of quality".
17. Click on "OK", click on "OK", and restart MPC-HC.
