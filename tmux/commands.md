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

Attach to a session
```
tmux a -t James
```

Exit session without killing
```
cmd + space  d
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

Swap the pane with the previous one
```
cmd + space {
```

Show pane numbers 
```
cmd + space q
```

To move the current pane to pane 3 
```
:swap-pane -t 3
```

To move pane 2 to pane 3
```
:swap-pane -s 2 -t 3
```

Convert horizonal panes to vertical panes
```
cmd + space space
```



## Misc
Enter command mode
```
cmd + space :
```

Switch session
```
cmd + space s
```
or
```
cmd + space t
```

Open popup
```
cmd + space e
```








