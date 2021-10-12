# tmux

Terminal multiplexer. 

## cheat table

| category | command | description
| :------- | :------ | -----------
| session  | tmux new -s "session name" | creates and connects to created session.
| | ctrl+b | leader key. 
| | leader + d | detach from current session
| | tmux ls | lists all sessions
| | tmux attach -t "session" | attach to *target* session
| window | leader + c | create new window
| | leader + n | move to next window
| | leader + p | move to previous window
| | leader + , | rename window
| | leader + w | list all windows
| pane | leader + % | vertical split
| | leader + " | horizontal split
| | leader + o | rotate focus clockwise
| | leader + arrow keys | shift focus according to arrow
| | leader + z | zoom in
| | leader + q | display pane numbers
| | leader + x | kill pane
| scrollback buffer | leader + [ | switches to tmux scrollback buffer. scrollback back and forth using arrow keys.
| set-window-option | :setw synchronize-panes | sync commands on all panes