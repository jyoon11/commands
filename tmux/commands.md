## Sessions

Show all sessions
```
tmux ls
```

Start a new session
```
tmux new
```

Start a new session with the name James
```
tmux new -s James
```

kill/delete session James
```
tmux kill-session -t James
```

kill/delete all sessions but the current
```
tmux kill-session -a
```

Attach to last session
```
tmux a
```

## Windows

Create window
```
cmd + space  c
```

Rename current window
```
cmd + space  ,
```

Close current window
```
cmd + space &
```

Reorder window, swap window number 2(src) and 1(dst)
```
:swap-window -s 2 -t 1
```

## Panes

Close current pane
```
cmd + space x
```

## Misc
Enter command mode
```
cmd + space :
```








