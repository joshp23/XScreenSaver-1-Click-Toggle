# XScreenSaver 1-Click Toggle
by Josh Panter [Unfettered](https://unfettered.net)

A simple script that toggles the XScreenSaver state on/off

## Requirements
1. [XScreenSaver](https://www.jwz.org/xscreensaver/) up and running on your system
2. [pidof](http://manpages.ubuntu.com/manpages/xenial/en/man8/pidof.8.html) - standard on most linux distros
3. [libNotify](https://launchpad.net/ubuntu/precise/+package/libnotify-bin) - standard on many modern linux distros

## Installation and example use
1. Download and extract the files of this repostiory to your home directory. Perhaps append the directory name with a dot in order to hide it from normal use.
2. Either take note of the path to, or place toggle-xscreensaver.sh and power_switch.png in a location of your choosing.
3. Open Toggle-XScreenSaver.desktop and edit lines 7 & 10 to reflect those paths.
4. Save Toggle-XScreenSaver.desktop to .local/share/applications/Toggle-XScreenSaver.desktop (perhaps put a copy on your desktop)
5. Look for new app in your applications list, favorite it, profit.

===========================

    Copyright (C) 2016 Josh Panter

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
