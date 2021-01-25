# first-x (first-cross)
This project is an experiment for VS Code browser development/debugging on Windows 10 WSL & CMD & GIT-Bash (Windows terminal) and Ubuntu 20.04 (bash).

Testing VS Code launch/attach debuggability of Windows-Chrome, Ubuntu-Chromium, Windows-Edge, Ubuntu-Edge (dev),
Windows-Firefox, Ubuntu-Firefox and Ubuntu-Firefox developer edition.

## Windows 
All browsers seems to work fine with VS Code debugging. (the current launch.json is only fit for Ubuntu)

## Ubuntu 
Surprisingly, best so far is the dev preview edition of edge for linux. Firefox and Firefox developer edition crashes using "action": "launch" but can be made to work for "attatch". 

### Questions asked 
Is it possible to have one .vscode/launch.json config that work  equally well on window & linux? 

*Allmost, not quite there yet.*

Can we mix and match the development platforms we use? 

*Allmost. Possibly soon. Browsers have converged and the platforms are going in that direction as well.*


