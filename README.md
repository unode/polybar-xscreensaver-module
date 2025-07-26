# A simple XScreenSaver activate/deactivate icon and toggler for polybar

```
; In your bar configuration add
modules-right = <other-modules> xscreensaver <other-modules>

[module/xscreensaver]
type = custom/script

exec = /path/to/xscreensaver-deactivate-daemon
tail = true

label = %output%
click-left = /path/to/xscreensaver-deactivate-toggle
```
