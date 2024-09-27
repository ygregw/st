# st - simple terminal

st is a simple terminal emulator for X which sucks less ([suckless.org](https://st.suckless.org/)).

# This build

Based on version 0.8.5.

Patches:

* [alpha](https://st.suckless.org/patches/alpha/): changes opacity of the background
* [font2](https://st.suckless.org/patches/font2/): adds spare font besides default; allows terminal to render emoji correctly (with a suitable font added)
* [anysize](https://st.suckless.org/patches/anysize/): removes unsightly gaps that result from st's window auto snapping
* [scrollback](https://st.suckless.org/patches/scrollback/): allows you to scroll back through terminal output - must have!
* [xresources](https://st.suckless.org/patches/xresources/): adds the ability to configure st via Xresources.

# Installation

```
make
sudo make install
```

# Credits

Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.

