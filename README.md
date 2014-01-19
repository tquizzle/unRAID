unRAID
======

unRAID Scripts and what-not


### preclear_disk.sh

To use preclear_disk.sh do the following...

* Telnet to your unRAID server
* cd /boot
* wget --no-check-certificate https://raw.github.com/tquizzle/unRAID/master/preclear_disk.sh
* run ./preclear_disk.sh -h


### Dynamix WebGUI

Bergware has a great webGUI for unRAID. https://github.com/bergware/dynamix

* cd /boot/plugins
* wget --no-check-certificate https://raw.github.com/bergware/dynamix/master/plugins/dynamix.webGui-2.0.9-noarch-bergware.plg
* installplg dynamix.webGui-2.0.9-noarch-bergware.plg
* Refresh your unRAID webGUI and see the awesomeness
