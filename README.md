##xorg.conf
X11 settings for my 6-monitor, 2 nvidia gfx card desktop.

### Notes for me:
Log File Information:

The X.Org log files are in `/var/log/Xorg.#.log`, where `#` is the server number (usually 0).

The configuration file starts loading at the line that says `Using config file`

Use `$ sudo startx -- :1` to test
