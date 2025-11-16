# About

dmenu ([tools.suckless.org/dmenu/](https://tools.suckless.org/dmenu/)) + fuzzy search + delete left word using ctrl+backspace and delete right word using ctrl+delete

# Requirements

In order to build dmenu you need the Xlib header files

# Build

Using `make` in `dmenu-5.3` directory

and do something like this

```
ln -s ~/projects/dmenu-fuzzy/dmenu-5.3/dmenu ~/.local/bin/dmenu
ln -s ~/projects/dmenu-fuzzy/dmenu-5.3/dmenu_run ~/.local/bin/dmenu_run
ln -s ~/projects/dmenu-fuzzy/dmenu-5.3/dmenu_path ~/.local/bin/dmenu_path
ln -s ~/projects/dmenu-fuzzy/dmenu-5.3/stest ~/.local/bin/stest
```

(ensure `~/.local/bin` is in your PATH)
