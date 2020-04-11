# st-leiska

My personal fork of [st](https://st.suckless.org/) which has some additional features such as:
* alpha/transparency
* default font is Ubuntu Mono
* a brighter default colorscheme
* clipboard support
  * Highlighting text automatically copies it to clipboard
  * `MB3` pastes from clipboard
* some additional keybindings:
  * scrollback:
    * `Ctrl+Shift+k` scroll up
    * `Ctrl+Shift+j` scroll down
  * resizing:
    * `Ctrl+Shift+l` increase font size   
    * `Ctrl+Shift+k` decrease font size
    * `Ctrl+Shift+n` return to default font size
    

## Installation

    sudo make clean install

In order to build st you need the Xlib header files and the Ubuntu font family,
in case you don't change the default font in config.def.h/config.h.

For alpha you also need a composite manager such as `xcompmgr`

## Credits

[suckless.org](https://suckless.org/philosophy/)
  
