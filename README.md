# Tmux-Shortcut-Cheatsheet
Terminal Multiplexer

## installation
` $ sudo apt install tmux `

## Run Tmux
` $ tmux `

## Some Tmux Features & Shortcuts
Split Vertically
` Ctrl + b + % `
Split Horizontally
` Ctrl + b + " `
Show Time
` Ctrl + b + t `
Move between Panes
` Ctrl + b + Arrow-keys `
Zoom In/Out
` Ctrl + b + z `
Create a new terminal window
` Ctrl + b + c `
Move between Windows/Tabs
` Ctrl + b + [Shell-Number (which is written bottom the page)] `
Detach from a Tmux session
` Ctrl + b + d `
Kill a Window(Tab)
` Ctrl + b + & `
Kill a Pane
` Ctrl + b + x `
Scroll
` Ctrl + b + [Page up/down keys] `
Exit from Scroll mode
` q `
Search on Scroll mode
` Ctrl + s `
Change panes side
To Left: ` Ctrl + b + { `
To Right: ` Ctrl + b + } `
Show Windows List
` Ctrl + b + s `
Tmux Command mode
` Ctrl + b + : `
Help
` Ctrl + b + ? `
Sychronize Panes
1. Go to Command mode
2. Write below command:
` setw synchronize-pane on/off ` 
View list of active Tmux sessions
` $ tmux ls `
Attach to a session
` $ tmux attach -t [session-number] `
Kill a session 
` $ tmux kill-session [session-number] `
Create a session with a name
` $ tmux new -s [session-name] `
` $ tmux new -s ubuntu `
Use `exit` command to exit from panes.

