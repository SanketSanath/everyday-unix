# everyday-unix
**Unix (especially MacOS) Tools and Scripts**

I am trying to document the tools and scripts I use on my \*nix (MacOS) system on daily basis.

---
List of tools and scripts
1. [03.27 Amethyst](#03.27)


# Details
### 1. <a name="03.27"></a>Amethyst- Tiling Window manager for MacOS
[github repository](https://github.com/ianyh/Amethyst/blob/development/README.md) 
There are other window managers are also available such as spectacle, rectangle, magnet. But all those are either not free or doesn't resize and rearrange the windows automatically and also doesnot provide a way to navigate through the windows or tiles. If automatically rearraging is not a big deal for you then rectangle is best for you. It is easy and hassle free. 

Amethyst is similar to dwm, i3 and bspwm. Install using Homebrew
```brew cask install amethyst```

#### Keyboard Shortcuts
Amethyst uses two modifier combinations
1. `mod1` => ⌥⇧
2. `mod2` => ⌃⌥⇧

Defaults keymaps defined by Amethyst

| Default Shortcut | Description |
|---|---|
| `mod1 + space` | Cycle layout forward |
| `mod1 + h` | Shrink the main pane |
| `mod1 + l` | Expand the main pane |
| `mod1 + ,` | Increase main pane count |
| `mod1 + .` | Decrease main pane count |
| `mod1 + j` | Move focus counter clockwise |
| `mod1 + k` | Move focus clockwise |
| `mod2 + j` | Swap focused window counter clockwise |
| `mod2 + k` | Swap focused window clockwise |
| `mod1 + enter` | Swap focused window with main window |
| `mod1 + t` | Toggle float for focused window |
| `mod1 + i` | Display current layout |
| `mod2 + t` | Toggle global tiling |
| `mod1 + a` | Select tall layout |
| `mod1 + d` | Select fullscreen layout |

Full list of shorcuts are available on github page.
