Repository for my customized version of
[official deCONZ add-on](https://github.com/home-assistant/hassio-addons/tree/master/deconz)
for Home Assistant.

This is mostly the same as upstream, but with a few tweaks to simplify my life:
- I usually update deCONZ before upstream
- Add-on stores config in `/config/deCONZ` so it is not wiped on uninstalls
- VNC is enabled by default and device is predefined as `/dev/ttyUSB0`

