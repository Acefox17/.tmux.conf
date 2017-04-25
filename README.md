# Installing on Mac or Linux

    git clone git@github.com:castle-dev/.tmux.conf ~/.tmux
    cd ~/.tmux
    ./setup.sh

## Keyboard shortcuts

Run the `tmux` command to start a multi-pane session, `tmux ls` to view active session, and `tmux attach -t #` to attach to a specific session.

    Shortcut | Action
    --- | ---
    `ctrl+a``-` | split window horizontally
    `ctrl+a``\` | split window vertically
    `ctrl+j` | move the cursor down one pane
    `ctrl+k` | move the cursor up one pane
    `ctrl+h` | move the cursor left one pane
    `ctrl+l` | move the cursor right one pane
    `ctrl+a``[` | enable scroll in current pane with arrow keys (q to exit)
    `ctrl+a``d` | detach from session (leave running in background)
