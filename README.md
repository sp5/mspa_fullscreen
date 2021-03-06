# Fullscreen Flash Objects

This userscript adds fullscreen buttons to Flash movies and games that otherwise
wouldn't allow it. Works much more reliably on simple animations, such as the
ones on Homestuck, than on games, many of which assume their object will be a
certain size. Pixel art games are especially bad, not only because they rarely
work with this script, but also because they're often near-unplayable on high
DPI displays. 

If you really want to play a non-scaling pixel art game in fullscreen, you can
download the source code of `xrandr`, modify every instance of `"bilinear"` to
`"nearest"`, then use the `--scale-from` option to change your screen resolotion
to the exact height required. Then, you can use this script to make it fit
nicely in the screen. 

Flashes with the same aspect ratio as your screen will have a 1-pixel gap placed
to their left. This gives you a way to get the focus away from the flash, which
it would otherwise refuse to give up.

Download: [hdstuck.user.js][1]

[1]: https://github.com/Samuel-Phillips/mspa_fullscreen/raw/master/hdstuck.user.js
