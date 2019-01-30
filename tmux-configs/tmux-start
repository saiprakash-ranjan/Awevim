#!/bin/bash

# Make sure tmux shows correct colors
export TERM=xterm-256color

# attach to existing tmux session or create a new session
if ps ax | grep -v grep | grep -v tmux-start | grep tmux > /dev/null
then
   tmux attach
else
   tmux new-session
fi
