# st - simple terminal
st is a simple terminal emulator for X which sucks less.


# Requirements
In order to build st you need the Xlib header files.


# Installation
Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

    make clean install


# Running st
If you did not install st with make clean install, you must compile
the st terminfo entry with the following command:

    tic -sx st.info

See the man page for additional details.

# Credits
Originally developed by the [suckless team](https://suckless.org/)

Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.

## Patches

alpha patch:
- Eon S. Jeon <esjeon@hyunmu.am>
- pr <protodev@gmx.net>
- Laslo Hunhold <dev@frign.de>
- Ivan J. <parazyd@dyne.org>
- Matthew Parnell <matt@parnmatt.co.uk>
- Johannes Mayrhofer <jm.spam@gmx.net>
- Alex Ramirez <aramirez@posteo.net>

anysize patch:
- Augusto Born de Oliveira <augustoborn@gmail.com>

blinking cursor patch:
- Genki Sky
- Steve Ward <planet36@gmail.com>
- jvyden

catppuccin color palette:
- Jazil T S <@tsjazil>

delkey patch:
- Roberto E. Vargas Caballero <k0ga@shike2.com>
- Laslo Hunhold <dev@frign.de>
- Matthew Parnell <matt@parnmatt.co.uk>
- clyme <theclyme@gmail.com>
