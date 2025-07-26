# A simple XScreenSaver activate/deactivate icon and toggler for polybar

```
[module/xscreensaver]
type = custom/script

exec = /path/to/xscreensaver-deactivate-daemon
tail = true

label = %output%
click-left = /path/to/xscreensaver-deactivate-toggle
```
