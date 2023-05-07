1 .'git init' -> Power your folder to be managed by git, and initialises a new empty 
 repository. It also creat .git folder that that has all relevent logic to manage
 version of your project.

 2. 'Working area' -> There can be bunch of file that are not currnetly handel by git.
 It means that changes done or to be done in thos file are not manage by git yet
 A file is in  working area it considered to be not in the staging area. When we 
 do git status and we see bunch of file if 'untrack file' the these are actully
 called to be in the working area.

 3 'staging area' -> what all file are going to part of next version that we will creat.
 this staging area is the place where git knows that changes will be done from last version to 
 next version.
 
 4. 'Repository Area' -> This area actully contain the details of all previous registered  version 
 And all the file this area, git already manage them and knows thier version history  

5. 'git add <file name>' -> Move the file working area to staging Area 

6. 'git rm --cached <file>' -> moves the file back frome staging area to working Area 