# :computer: tmux

### Ressources :
https://www.hamvocke.com/blog/a-quick-and-easy-guide-to-tmux/  
https://www.redhat.com/sysadmin/introduction-tmux-linux  
  
### Comand line  
new session simple : `tmux`  
new session with name : `tmux new -s <name>`
rename session : `tmux rename-session -t <num_session> <new_name>`  
Attach running session : `tmux attaach -t <num / name session>`
  
    
### Key comand  

display all keybindings : `C-b ?`

Close session / pane : `C-d`
detach session : `C-b d` 


## Save output to a file  

- save output to a buffer : `c-b + :`, `capture-pane -S -`, `return key`  
- save buffer to a file : `c-b + :`, `save buffer filename.txt`, `return key`
