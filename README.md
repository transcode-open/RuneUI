
## RuneAudio with satellite mode.

This is a forked version of: RuneAudio
Free and open source Hi-Fi music player for embedded hardware


## Satellite mode

In satellite mode your local instance of MPD forwards most calls to an instance of MPD running
on another (probably more powerful) machine. The larger machine takes care of indexing your music
collection and making it available on a Samba share. The MPD satellite reads music files from the
Samba share and plays them locally.

The second machine needs:

    1. MPD
    2. A hard drive with the music collection
    3. Samba

Setting that up is currently outside the scope of this project!

The job of this project is to extend the RuneUI MPD web frontend with an optional MPD settings mode
in which MPD's smbclient and proxy plugins are used to configure the device as a satellite. 


Copyright (C) 2013-2014 RuneAudio Team
http://www.runeaudio.com

RuneUI
copyright (C) 2013-2014 - Andrea Coiutti (aka ACX) & Simone De Gregori (aka Orion)

RuneOS
copyright (C) 2013-2014 - Simone De Gregori (aka Orion) & Carmelo San Giovanni (aka Um3ggh1U)

RuneAudio website and logo
copyright (C) 2013-2014 - ACX webdesign (Andrea Coiutti)

This Program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 3, or (at your option)
any later version.

This Program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with RuneAudio; see the file COPYING.  If not, see
<http://www.gnu.org/licenses/gpl-3.0.txt>.
