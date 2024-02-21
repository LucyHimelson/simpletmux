# simpletmux
### This recipe will teach u the basics of tmux. as I guess

> [!NOTE]
> Well we have two parts
 - I before run tmux to enter seesion
 - II after run tmux and enter session

##  I tmux .

### Create new & name for session
```
tmux new -s (Name of session)
```
### Check session
```
tmux ls
```
### Rename session
```
tmux rename-session (Name of session)
```
### Back to detached session
```
tmux -t (Name of session)
```

### Delete session
```
tmux kill-session
```


## II tumx

###  Create a new window 
```
press (ctrl+b) + c
```
###  Move to another window
```
press (ctrl+b) + N°umber of window 
```
### Rename window
```
press (ctrl+b) + ,
```
### Create Horizontal pin
```
press (ctrl+b) + " 
```
### Create Vertical pin
```
press (ctrl+b) + %
```
### Move from to another pin
```
press (ctrl+b) + keyarrows
```
### Move pin
```
holding (ctrl+b) + keyarrows
```
### Session dismissal
```
holding (ctrl+b) + d
```
