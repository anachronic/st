# st (simple [and suckless] terminal)

This is a fork of [st](https://st.suckless.org/), the suckless terminal.

## Changes

Pretty simple overall.

* [scrollback](https://st.suckless.org/patches/scrollback/) all the way, mouse and keyboard
* [externalpipe](https://st.suckless.org/patches/externalpipe/) for URLs.
* [solarized](https://st.suckless.org/patches/solarized/) with a theme based on
  tomorrow color scheme. This allows me to easily swap between dark and light
  themes. Wee!

## Dependencies

[xurls](https://aur.archlinux.org/packages/xurls/) from the AUR,
[findutils](https://www.archlinux.org/packages/core/x86_64/findutils/files/)
which provides `xargs`. You are most likely to have the latter. For the menu,
I'm using [dmenu](https://tools.suckless.org/dmenu/) but will be changing to
rofi very soon.

## Why?

Been using URxvt for around a year and a half now and I really like it, but
there's some annoying bug that will draw little lines on the screen. `st` not
only does not have that, but it also supports full color. No real reason not to
use it
