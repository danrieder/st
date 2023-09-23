## ST: the simple terminal - or - the suckless terminal

This build my build of the [suckless terminal (st)](https://st.suckless.org/).  It is based on the excellent build by [Luke Smith](https://lukesmith.xyz).
My changes are mostly cosmetic. I recommend you check out Luke's build, and README [here](http://github.com/LukeSmithxyz/st/).
My build makes the following changes:
- colors: tokyo-night color scheme
- fonts: using some that I prefer. Luke's build sticks with the standard system mono font.  This is probably best for most new installs, or if you are not sure how to work with fonts on your system. Here are the fonts this build currently requires:  
  - JetBrainsMono Nerd Font
  - NotoColorEmoji
  - Font Awesome

---

## Key Bindings:
In some cases there are multiple ways to do the same action.

### Cut and Paste:
- `Alt+c:                copy`
- `Alt+p:                paste`
### Font Size (zoom)
- `Alt+Shift+k:          increase font size (zoom in)` 
- `Alt+Shift+j:          decrease font size (zoom out)`
- `Alt+Shift+u:          increase font size (zoom in)` 
- `Alt+Shift+d:          decrease font size (zoom out)`
- `Alt+Shift+UpArrow:    increase font size (zoom in)` 
- `Alt+Shift+DownArrow:  decrease font size (zoom out)`
### Terminal Scroll Control
- `Alt+k:                scroll up (slowly)`
- `Alt+j:                scroll down (slowly)`
- `Alt+UpArrow:          scroll up (slowly)`
- `Alt+DownArrow:        scroll down (slowly)`
- `Alt+PageUp:           scroll up (page at a time)`
- `Alt+PageDown:         scroll down (page at a time)`
- `Alt+u:                scroll up (page at a time)`
- `Alt+d:                scroll down (page at a time)`
- `Shift+MouseWheel:     scroll up or down`
### Transperancy (alpha) Control 
- `Alt+a:                increase transperancy`
- `Alt+s:                decrease transperancy`
### Special dmenu features
- `Alt+l:                send urls to dmenu - select one to follow`
- `Alt:y:                copy urls`
- `Alt+o:                send output from commands to dmenu`

## Installation

Requirements:
- xlib header files 
- libharfbuzz build files 
- make
- fontconfig
- libX11
- libXft

```
git clone https://github.com/LukeSmithxyz/st
cd st
sudo make install
```





