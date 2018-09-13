# MediaInfoExtractor
Extract MediaInfo data from video strips in the Blender Video Sequencer.

###Usage:
Download MediaInfo Command Line(CLI): https://mediaarea.net/en/MediaInfo/Download 
Unpack it.

In Blender install MediaInfoExtractor.py trough User Preferences > Add-ons > Install Add-on from file...
In the add-on preferences, select the folder button to open file browser.
Uncheck 'Relative Paths' and locate MediaInfo.exe where you unpacked it.
A button will be added to VSE strip editor > Properties > Edit Strip (Panel): Match Strips
Select a video strip in the Sequencer.
Click Match Strips.
The Properties > Render Settings > Ratio and Frame Rate will be set strip properties.
A file will be opened in the Text Editor with the full MediaInfo data.

Video tutorial:
https://youtu.be/_ynfs3JkYTo
