# git reset (back in time) 


## Why ? 

  * Back in time -> reset
  * e.g. git reset –-hard e2d5  
  * attention: only use it, when changes are not published (remotely) yet.
  * → It is your command, IN CASE your are telling yourself, omg, what's that, what did i do here, let me undo that

## Example 

```
git reset --hard 2343 
```

## Example (Arbeitsumgebung auf den Stand des letzten Commits setzten)

```
# linux befehl -legt leere datei an. 
touch myfile
git add myfile 
# ich will dieses file nicht !!!!! 
git reset --hard HEAD 
```
