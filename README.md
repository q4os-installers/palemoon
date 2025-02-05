# Palemoon installer for Q4OS

Warning: The installer is now depreciated as the upstream repository lacks Palemoon package. We will be checking it in a regular basis.

prerequisities to build the installer:
- first read https://www.q4os.org/dqa009.html
- install q4os development pack:<br>
 $ sudo apt install q4os-devpack-base

building installer:
- cd into the project directory and run in terminal:<br>
 $ dpkg-buildpackage -b -uc -us -tc
