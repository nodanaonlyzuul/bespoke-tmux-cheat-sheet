# Bespoke TMUX Cheatsheet

"**The bind key is Control b**" - my great, grandfather jotted in his
leather bound journal as the boat entered the Hudson River.

At Elis Island he was told to bring only one cheat sheet.
This is that cheatsheet...

## Windows

| Key | Action           |
|:----|:-----------------|
| ,   | name window      |
| c   | new window       |
| n   | next window      |
| p   | previous window  |
| l   | last window      |
| &   | list window      |
| w   | show all windows |

## Panes

| Key             | Action                               |
|:----------------|:-------------------------------------|
| "               | split pane horizontaly               |
| %               | split pane vertically                |
| o               | toggle panes                         |
| ;               | toggle to last pane                  |
| !               | promote pane into its own new window |
| x               | kill pane                            |
| BIND B + BIND O | swap content of panes                |

## Sessions

| Key | Action          |
|:----|:----------------|
| d   | dettach session |
| $   | name session    |
| s   | list sessions   |

see sessions: `tmux ls`  
attach to session: `tmux attach -t [IDENTIFIER]`  
kill session: `tmux kill-session -t [IDENTIFIER]`
