## WIFI + tmux

Display your WIFI info in a tmux window on OS X.

![Screenshot](https://github.com/carsonmcdonald/tmux-wifi-os-x/raw/master/screenshot.png)

## Usage

Put the wifi-signal-strength script in your PATH somewhere and then add something this in your .tmux.conf file:

    set -g status-right '#(wifi-signal-strength)'


## License

BSD license. See LICENSE for details.
