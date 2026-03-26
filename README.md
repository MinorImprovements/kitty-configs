This is personal configs for kitty preferences.

to get PS1 to show colors add  : xterm-kitty

it should look like this : 
case "$TERM" in
    xterm-color|*-256color|xterm-kitty) color_prompt=yes;;
esac

added dark-cat optional png for desktop icon. 
May not work but the docs suggest moving it to the config file will auto update on restart.

