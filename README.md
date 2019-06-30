### **ReadMe**

### **![Gis Weather](https://github.com/RingOV/gis-weather/raw/master/icon.png)**


### **Dependencies**
Used Python3 and GTK3
- python3-gi (python-gobject)
- python3-gi-cairo
- gir1.2-gtk-3.0 (gtk3)


Recommends:
- gir1.2-rsvg-2.0 (librsvg)

### **Features**
- View weather for several days
- Detailed weather forecast for today and tomorrow
- Fast switching between cities
- Select the background and theme weather icons
- "Compass" with the wind direction, with adjustable angle of rotation
- Highlighting the high wind
- Support weather services:
  - Gismeteo.com
  - OpenWeatherMap.org
  - Yr.no
- Support SVG and widget scale
- Indicator to panel
- Presets


### **How to Install**
- Download package from [http://sourceforge.net/projects/gis-weather/files/gis-weather/](http://sourceforge.net/projects/gis-weather/files/gis-weather/)
  - deb
  - rpm
  - exe
- AUR
  - Stable [https://aur.archlinux.org/packages/gis-weather/](https://aur.archlinux.org/packages/gis-weather/)
  - Testing [https://aur.archlinux.org/packages/gis-weather-git/](https://aur.archlinux.org/packages/gis-weather-git/)
- For Debian based distro 
  - use Noobslab ppa:
    - `sudo add-apt-repository ppa:noobslab/apps`
    - `sudo apt-get update`
    - `sudo apt-get install gis-weather`
  - build git version
    - `sudo apt-get install git fakeroot`
    - First build `cd && git clone https://github.com/RingOV/gis-weather.git && cd gis-weather/scripts && python3 build_deb.py && cd ../DEB && sudo dpkg -i *.deb`
    - or (after First build) `cd && cd gis-weather && git pull https://github.com/RingOV/gis-weather.git && cd scripts && python3 build_deb.py && cd ../DEB && sudo dpkg -i *.deb`
- For any distro:
  - Download [https://sourceforge.net/projects/gis-weather/files/latest/download](https://sourceforge.net/projects/gis-weather/files/latest/download)
  - Unpack
  - Run
  - `python3 gis-weather.py`


### **What's New**

[https://github.com/RingOV/gis-weather/wiki/What's-New](https://github.com/RingOV/gis-weather/wiki/What%27s-New)


### **Feedback**

If you find bug, want translate, have issues?

Please mail to ringov.gisweather@gmail.com


### **Links**

Source Code (GitHub) - [https://github.com/RingOV/gis-weather](https://github.com/RingOV/gis-weather)

deb, rpm, exe, tar.gz - [https://sourceforge.net/projects/gis-weather/](https://sourceforge.net/projects/gis-weather/)

AUR - [https://aur.archlinux.org/packages/gis-weather/](https://aur.archlinux.org/packages/gis-weather/)

NoobsLAB - [http://www.noobslab.com/2014/05/gis-weather-widget-for-linux-desktop.html](http://www.noobslab.com/2014/05/gis-weather-widget-for-linux-desktop.html)


### Donations:

If you like the software, don't forget to donate to further development of it!

[https://github.com/RingOV/gis-weather/wiki/Donate](https://github.com/RingOV/gis-weather/wiki/Donate)
