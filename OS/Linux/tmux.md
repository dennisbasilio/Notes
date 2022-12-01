# tmux
A terminal multiplexer that allows you to run multiple Linux programs over a single connection.

## Session Management
Start a new session
``` shell
tmux
tmux new
tmux new-session
:new
```

Start a new session with a name
``` shell
tmux new -s sessionname
```

List sessions
``` shell
tmux ls
```

Attach to session by name
``` shell
tmux attach -t sessionname
```

Attach to last session
``` shell
tmux attach
```

Kill a session
``` shell
tmux kill-session -t sessionname
```

Switch to next/last session
``` shell
Ctrl+b )
Ctrl+b (
```

Delete a session
``` shell
Ctrl+b d
```

Rename session
``` shell
Ctrl+b $
```

## Window Management
Create a new window
``` shell
Ctrl+b c
```

Move to next/previous window
``` shell
Ctrl+b n
Ctrl+b p
```

Change window name
``` shell
Ctrl+b ,
```

Select window by number
``` shell
Ctrl+b #
```

List windows
``` shell
Ctrl+b w
```

Select window by name
``` shell
Ctrl+b '
```

Kill window
``` shell
Ctrl+b &
```

Change to last used window
``` shell
Ctrl+b l
```

## Split Screen
Create vertical split
``` shell
Ctrl+b %
```

Create horizontal split
``` shell
Ctrl+b "
```
