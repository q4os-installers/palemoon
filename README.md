# Palemoon installer for Q4OS

prerequisities to build the installer:
- first read https://www.q4os.org/dqa009.html
- install q4os development pack
 $ sudo apt install q4os-devpack-base

building installer:
- cd into the project directory and run in terminal:
 $ dpkg-buildpackage -b -uc -us -tc
