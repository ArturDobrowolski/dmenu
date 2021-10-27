# Artur's build of dmenu
Suckless [dmenu](https://tools.suckless.org/dmenu/) build with several patches applied:

- Xresources: adds the ability to configure dmenu appearance via Xresources. Allowed options are:
`dmenu.font:` - set custom font\
`dmenu.background:` - set bg color\
`dmenu.foreground:` - set fg color\
`dmenu.selbackground:` - set selected bg color\
`dmenu.selforeground:` - set selected fg color
- Line height: adds a '-h' option to set the minimum height of a dmenu line.
- Highlight: higlight individual characters of matched text.
- Border: adds a border around the dmenu window.
- Center: adds a '-c' option to center dmenu window in the middle of the screen.

## Requirements
In order to build slock the Xlib header files are needed.

## Installation
To install dmenu simply run:
```
make clean install
```

## Running dmenu
Consult the manual page: `man dmenu`.