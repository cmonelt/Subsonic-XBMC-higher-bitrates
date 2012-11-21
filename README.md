Subsonic-XBMC-higher-bitrates
=============================

This is a modified version of the subsonic for XBMC plugin that will allow you to choose transcoding bitrates up to 5000k.  The plugin originally only allowed for 320k, which is fine for audio, but not video.


These instructions are for Windows 7, but the only difference for other operating systems are the paths, which I'm sure you'll figure out.  If not, ask me and I'll help you out.

Download Subsonic.py, Subsonic.pyo, and settings.xml (Don't right click and save as; that won't work.  If you're unfamiliar with git, the best thing to do is probably just click each file, view raw, and copy and paste them into your favorite text editor and save them as their appropriate filenames.  When you try to view raw the Subsonic.pyo file, it may offer you a download - that's fine, and you can just save that as Subsonic.pyo)

Backup Subsonic.py and Subsonic.pyo found in C:\Users\YOURUSERNAME\AppData\Roaming\XBMC\addons\plugin.audio.subsonic\resources\lib\Subsonic
Backup settings.xml found in C:\Users\YOURUSERNAME\AppData\Roaming\XBMC\addons\plugin.audio.subsonic\resources

No one but me has tested this, but I'm confident it's safe.  But if, for some reason it doesn't work, it's good to have backed up your files.

Now, replace those files with the ones downloaded here.

The new Subsonic.py and Subsonic.pyo will go to C:\Users\YOURUSERNAME\AppData\Roaming\XBMC\addons\plugin.audio.subsonic\resources\lib\Subsonic
The new settings.xml needs to go into C:\Users\YOURUSERNAME\AppData\Roaming\XBMC\addons\plugin.audio.subsonic\resources