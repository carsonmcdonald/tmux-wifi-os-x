## WIFI + tmux

Display your WIFI info in a tmux window.

![Screenshot](https://github.com/carsonmcdonald/tmux-wifi-os-x/raw/master/screenshot.png)

## Use

Put something this in your .tmux.conf file:

    set -g status-right: '#(wifi-signal-strength)'


## License

BSD license. See LICENSE for details.
