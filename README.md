# Rawley Fowler's ST build
This is a customized build of suckless' [st](https://st.suckless.org). For the best experience please check out my build of [dwm](https://www.github.com/rawleyfowler/dwm) and my [dotfiles](https://www.github.com/rawleyfowler/dotfiles).

![Void Linux](https://cdn.discordapp.com/attachments/635625917623828520/1001229393882001408/2022-07-25-144658_1920x1080_scrot.png)

### st - simple terminal
st is a simple terminal emulator for X which sucks less.

### Requirements
In order to build st you need the Xlib header files.

### Installation
Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

    make clean install

Running st
If you did not install st with make clean install, you must compile
the st terminfo entry with the following command:

    tic -sx st.info

See the man page for additional details.

Credits
Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.
