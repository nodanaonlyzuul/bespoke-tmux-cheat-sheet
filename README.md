# Bespoke TMUX Cheatsheet

"**The (default) bind key is Control b**" - my great, grandfather jotted in his
leather bound journal as the boat entered the Hudson River.

At Ellis Island he was told to bring only one cheat sheet.
This is that cheatsheet...unchanged by time, unrelenting in quality.

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

## Commands

Commands can be used to do some of the same things
keyboard shortcuts can. BIND + :


### `new-window`

* `new-window -c ~/path/to/start/in`

### Monitoring Output

`set-option -g monitor-activity on`


## Customizing Tmux

Add a file like [.tmux.conf](/.tmux.conf)
