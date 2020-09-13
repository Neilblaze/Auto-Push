# Auto-Push
Commits every file from a respective folder.

Shell script which basically commits each file from a folder. 

## File Structure to be used
newData (folder)  
Repo (folder)  
execute.sh  

### How it works
- Create 2 empty folders "newData" and "Repo" like shown in File Structure.    
- Initialise git in folder "Repo" (run git init in git bash) and link it to the remote branch.
- Add all new files into a folder "newData"  
- Open git bash and run execute.sh (sh execute.sh)
- On execution of this script, files are moved into the other folder "Repo"     
- This folder "Repo" is committed and files are pushed to the remote branch.  

### Motivation
I get a lot of "lyadh" while developing crazy shits & hence get isolated from Github. But at the same time I don't want my GitHub to feel empty when I'm doing some form of work. So I decided to push the codes while I am getting laid. Instead of committing each code, I felt it would be easier to save all the files in a folder and automate the  committing part.

### To do
Error Handling  
Success/ Failure Messages  

#### -Point :~
Aro besi lyadh lagbe :p 
