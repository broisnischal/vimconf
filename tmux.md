
1.  -   `tmux` 
        
    -   **Detach from a session:**
        
        arduinoCopy code
        
        `Press Ctrl-b, then release and press d` 
        
    -   **List sessions:**
        
        bashCopy code
        
        `tmux list-sessions` 
        
    -   **Attach to a session:**
        
        bashCopy code
        
        `tmux attach -t [session-name]` 
        
2.  **Windows and Panes:**
    
    -   **Create a new window:**
        
        cssCopy code
        
        `Ctrl-b, c` 
        
    -   **Switch between windows:**
        
        cssCopy code
        
        `Ctrl-b, [window-number]` 
        
    -   **Split the window horizontally:**
        
        cssCopy code
        
        `Ctrl-b, %` 
        
    -   **Split the window vertically:**
        
        cssCopy code
        
        `Ctrl-b, "` 
        
3.  **Advanced Features:**
    
    -   **Customizing tmux:**
        
        -   Edit the `.tmux.conf` file in your home directory.
    -   **Scripting with tmux:**
        
        -   Use tmux commands in your shell scripts.
    -   **Integration with scripting languages (e.g., Python):**
        
        -   Explore the tmux API for advanced scripting.

Here's the process for detachig, 

1.  **Press `Ctrl-b`:** This is the prefix key that signals tmux to expect a command.
    
2.  **Release `Ctrl-b`:** After pressing `Ctrl-b`, release the keys.
    
3.  **Press `d`:** This key combination (`Ctrl-b`, then `d`) tells tmux to detach from the current session.
    

So, in summary, it's `Ctrl-b`, release, and then `d`.

`tmux kill-server` 


`tmux kill-session -t [session-name]`
