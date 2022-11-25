# `axyriah/st`

Concise patch collection for [suckless' st] terminal.

[suckless' st]: https://st.suckless.org/

* Zoom - <kbd>alt-plus/minus</kbd>
* Scrollback - <kbd>alt-↑/↓</kbd> or <kbd>alt-mousewheel</kbd>
* Clipboard - <kbd>ctrl-shift-v/c</kbd>, some applications need `xclip` to be installed
* Boxdraw, font2, anysize, alpha, and xresources with signal reloading

The main target platform for this fork is FreeBSD. You may need to tweak `config.mk` to
make it work on other operating systems.
