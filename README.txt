1.'git init' -> Power your folder to be managed by git, and initialises a new empty 
 repository. It also creat .git folder that that has all relevent logic to manage
 version of your project.

2. 'Working area' -> There can be bunch of file that are not currnetly handel by git.
 It means that changes done or to be done in thos file are not manage by git yet
 A file is in  working area it considered to be not in the staging area. When we 
 do git status and we see bunch of file if 'untrack file' the these are actully
 called to be in the working area.

3. 'staging area' -> what all file are going to part of next version that we will creat.
 this staging area is the place where git knows that changes will be done from last version to 
 next version.
 
4. 'Repository Area' -> This area actully contain the details of all previous registered  version 
 And all the file this area, git already manage them and knows thier version history.  

5. 'git add <file name>' -> Move the file working area to staging Area.

6. 'git rm --cached <file>' -> moves the file back frome staging area to working Area. 

7. 'commit' ->  commit is perticuler version of project. it capture snapshot of the project's
 stage  changes and creat the version out of it. 

8. 'git commit' -> registered stage changes to a commit.

9. 'git log' -> list down all the commit of the repository. If you want to exist out of git log prompt 
press 'q'.

10. 'git restore' -> it remove the all file changes from stage area to be committed. This can
be usefull , if you did dirty piece of code and now no more want it. instead of of deleting every 
changes line by line. we can restore it or you can say last clean version of file.   

11. 'git restore --stage<file>' -> it remove the file from  changes form stage area to working area.
This is only work if changes are in your staging area.

12. diff between git git rm and git restore 
ans: if you want to move the whole file back to the untrack state. the we do git rm. otherwise if
we just want the changes to be moves working area or staging are then we git restore.

13. 'git diff commit1 and commit2' -> gives the differance of all file changes between two commit.

14.' git commit -m "This is my 5th commit" '-> if we want to avid opening  the txt editior like vim/nano 
to add commit message we can use this following command. 