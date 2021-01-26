# Tmux 

tmux is a terminal multiplexer. tmux allow you to open multiple window to do multi tasks,you can also  detach them (they keep running in the background) and reattach them to a different terminal.

#### USAGE : 
Ctrl+b ? :  list of all commands( help ) 

tmux new -s sname : create new session with sname as name 

Ctrl+b d : detach your current session 

tmux ls : show all detached sessions 

tmux attach-session -t sname : attach sname session 

Ctrl+b c : create new window 

Ctrl+b nbr : gow to nbr'eth window (number 0..9)

Ctrl+b , : rename the current window 

Ctrl+b % : split current pane horizontally into two panes

Ctrl+b " : split current pane vertically into two panes

Ctrl+b o : go to the next pane 

Ctrl+b ; : toggle between the current and previous pane 

Ctrl+b x : close the current pane 
