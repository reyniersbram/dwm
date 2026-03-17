# dwm - Dynamic window manager

My build of dwm.

## Used patches

- [systray](https://dwm.suckless.org/patches/systray/dwm-systray-6.7.diff) shows
a systray in the top right corner. (bb3be59)
- [swallow](https://dwm.suckless.org/patches/swallow/dwm-swallow-6.3.diff)
allows windows launched from the terminal to swallow the terminal. (39269d7)

## Usage

### Applications
| Keybind | Action |
| --- | --- |
| `Super+Return` | Spawn terminal |
| `Super+p` | Spawn desktop launcher |
| `Super+Shift+p` | Spawn program |
| `Super+Alt+p` | Spawn password menu |

### Window Navigation

| Keybind | Action |
| --- | --- |
| `Super+j` | Cycle to next window |
| `Super+k` | Cycle to previous window |
| `Super+i` | Increase number of windows in master pane (tiling layout) |
| `Super+d` | Decrease number of windows in master pane (tiling layout) |
| `Super+h` | Decrease size of master pane (tiling layout) |
| `Super+l` | Increase size of master pane (tiling layout) |
| `Super+Shift+Return` | Push window to master pane or swap master pane with first in stack |
| `Super+b` | Toggle status bar |
| `Super+Tab` | Toggle between last used tabs |
| `Super+Shift+c` | Kill window |
| `Super+t` | Set tiling layout |
| `Super+f` | Set floating layout |
| `Super+m` | Set monocle layout |
| `Super+Space` | Toggle between last used layouts |
| `Super+Shift+Space` | Toggle window to be floating |
| `Super+,` | Focus on previous monitor |
| `Super+.` | Focus on next monitor |
| `Super+Shift+,` | Move window to previous monitor |
| `Super+Shift+.` | Move window to next monitor |
| `Super+Shift+q` | Quit dwm |
| `Super+<1-9>` | Focus on tab |
| `Super+Control+<1-9>` | Toggle focus on tab |
| `Super+Shift+<1-9>` | Move window to tab |
| `Super+Control+Shift+<1-9>` | Toggle window on tab |
| `Super+0` | Focus on all tabs |
| `Super+Shift+0` | Move window to all tabs |

### Mouse actions

| Mouse binding | Action |
| --- | --- |
| `Left Click` layout | Toggle between last used layouts |
| `Right Click` layout | Set monocle layout |
| `Middle Click` window title | Push window to master pane or swap master pane with first in stack |
| `Middle Click` status text | Spawn terminal |
| `Super+Left Click+<movement>` window | Move floating window around |
| `Super+Middle Click` window | Toggle window to be floating |
| `Super+Right Click+<movement>` window | Resize window in floating mode |
| `Left Click` tab | Focus on tab |
| `Right Click` tab | Toggle focus on tab |
| `Super+Left Click` tab | Move window to tab |
| `Super+Right Click` tab | Toggle window on tab |

## Configuration

### Xresources

These settings can be modified using Xresources:

- `Dwm.font`: font used by dwm
- `Dwm.color.normal.foreground`: foreground color for normal element
- `Dwm.color.normal.background`: background color for normal element
- `Dwm.color.normal.border`: border color for normal window
- `Dwm.color.selected.foreground`: foreground color for selected element
- `Dwm.color.selected.background`: background color for selected element
- `Dwm.color.selected.border`: border color for selected window
