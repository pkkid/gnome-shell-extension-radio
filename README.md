## Gnome Shell Extension Radio
* Extension for listening to internet radio streams
* Supports Gnome-Shell 3.18, 3.20 and 3.22 (older versions see releases)

![alt text](https://raw.githubusercontent.com/hslbck/gnome-shell-extension-radio/master/radio-extension.png)

### Installation
Prerequisites: gstreamer plugins are installed
##### Using gnome shell extension webpage
https://extensions.gnome.org/extension/836/internet-radio/
##### Manual

You'll need the `glib-compile-schemas` and `msgfmt` commands on your system, available through `libglib` and `gettext`.

* Download source from github (clone repository or download zip)
* From the `gnome-shell-extension-radio` directory:
  * For a user only installation: `make && make install`
  * For a system-wide installation: `make && sudo make install DESTDIR=/`
* Reload the shell using X: Press `Alt+F2` write `r` and press `Enter`  
* Enable via Gnome Tweak Tool

### Features
* Manage radio station list
* Mark stations as favourites
* Middle click to start/stop last played station
* Cyrillic tag support (nielsrune): Usage description in pull request comment https://github.com/hslbck/gnome-shell-extension-radio/pull/18
* Support for multimedia keys
  * Play / Stop
  * Next / Prev cycles through the channels list (X4lldux)
* Support for title notification
* Search online radio directory http://www.radio-browser.info/ (https://github.com/hslbck/gnome-shell-extension-radio/issues/23)

### Translation
* Open your source folder
* Run `make build` in your source directory
* The file `radio@hslbck.gmail.com.pot` should be created in the `po` folder

### Credits
nielsrune  
X4lldux  
zapashcanon  
##### Translations
Chinese: gmg137  
Danish: nielsrune   
French: narzb, BridouZ, thony8  
Hungarian: urbalazs  
Polish: pkomur  
Russian: stmc  
Turkish: marjinal1st  

### License
Gnome Shell Extension Radio  
Copyright (C) 2014 - 2016  hslbck

Gnome Shell Extension Radio is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

Gnome Shell Extension Radio is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see <http://www.gnu.org/licenses/>.
