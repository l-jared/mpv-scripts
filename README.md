# My Lua scripts:

## after-playback
Sends commands to nircmd (windows only) on playback finish. Commands include sleep, hibernate, shutdown, lock. Full list is in the file

## change-refresh

Uses nircmd (windows only) to change the resolution and refresh rate of the monitor to match the playing video.

Saves the original monitor resolution and reverts changes on exit and when hotkey is pressed.

Full description in file.

## coverart
Automatically scans the directory of the currently loaded file and loads any valid cover art into mpv as additional video tracks.
Has options for selecting what file names and types are considered valid.

## cycle-commands
Cycles through a series of commands on a keypress. Each iteration of the cycle can contain as many commands as one wants. Syntax details are at the top of the file.

## cycle-profile
Cycles through a list of profiles sent via a script message and prints the profile-desc to the OSD. More details at the top of the file

## editions-notification
Prints a message on the OSD if editions are found in the file, and temporarily switches the osd-playing-message to the editions-list property when switching. This makes it easier to tell the number and names while navigating editions.

## music-mode
Switches to a music profile when an audio file is being played and switches back when a non-audio file is played

## playlist-shuffle
shuffles the playlist and moves the current file to the start of the playlist

# Modified scripts:

## autoload
Exactly the same as the script available here:
https://github.com/mpv-player/mpv/blob/master/TOOLS/lua/autoload.lua

However, instead of loading automatically it only loads when a keybind is pressed (Ctrl+f8 by default)

# Other scripts

betterchapters: https://github.com/mpv-player/mpv/issues/4738#issuecomment-321298846

nextfile: https://github.com/jonniek/mpv-nextfile 