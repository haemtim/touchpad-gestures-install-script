# touchpad-gestures-install-script
Bash installation script for touchpad gestures on Linux. Uses apt.

# Usage

Clone in your user directory: \
`git clone https://github.com/haemtim/touchpad-gestures-install-script.git` <br>

Change directory into the new, cloned directory: \
`cd touchpad-gestures-install-script/` <br>

Edit the script: \
`sudo nano install-touch-gestures.sh` <br>

Replace "YOUR_USERNAME" in the first line with your username. Exit by pressing control+x, confirm with "y", then enter. \

Update permissons of the file so it can be executed: \
`sudo chmod +x install-touch-gestures.sh` <br>

Execute the file: \
`sudo ./install-touch-gestures.sh`<br>

You will now find a programm called "gestures". There you can configure the effect of certain gestures. You can use xdotool to assign keystrokes or keyboard shortcuts to gestures. To do so, use <br>
`xdotool key Examplekey1+Examplekey2+...` <br>
as the command. \
You can find a full list of xdotool keycodes here: https://gitlab.com/cunidev/gestures/-/wikis/xdotool-list-of-key-codes
