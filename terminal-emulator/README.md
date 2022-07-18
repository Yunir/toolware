### Comparison

- Alacritty [Apache-2.0]
    - No ligatures support [alacritty/alacritty#50]
- Kitty [GPL-3.0]
    - Overrides TERM variable to `xterm-kitty` [kovidgoyal/kitty#2192]
        - Leads to problems with backspaces in ssh sessions
        - Possible solution is to use: `kitty +kitten ssh myserver`
            - But this will download some terminfo files (?)
    - No windows support [kovidgoyal/kitty#640]

### Popularity

[![Star History Chart](https://api.star-history.com/svg?repos=alacritty/alacritty,Swordfish90/cool-retro-term,Guake/guake,kovidgoyal/kitty,LukeSmithxyz/st,tmux-python/tmuxp,gnachman/iTerm2&type=Date)](https://star-history.com/#alacritty/alacritty&Swordfish90/cool-retro-term&Guake/guake&kovidgoyal/kitty&LukeSmithxyz/st&tmux-python/tmuxp&gnachman/iTerm2&Date)

