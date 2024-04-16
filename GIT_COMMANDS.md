1. git config --global user.email , git config --global user.name
2. -git status(shows if changes staged for commit or not staged for commit or nothing to commit)
3. in  a repo git bash there and do (git init)  to make folder a repo makes it a (master)
4. git add --a (stage all) (or) || git add first.txt (stage individual files) or use git add .
5.  snapshots taken once committed
6. git commit -m "comments heree"
7. git diff -> compares difference between working directory and staging area
7. git log -> check all previous commits ( CONTAINS git identifier long list of numbers and digits , head master, author name and email (me), date and time, commit message)
8. mkdir checks-> makes a new difrectory
9. cd checks -> changes directory to git dir ( change directory command(to get into one file or go to directory of that folder))
10. pwd(present working directory) tells which is the location 
11. ls(list content) will list down content of our current directory.
12. git remote add origin + your ssh link ( this is for telling where to push your folders to in ssh link of git repo from github )
13. git push  -u origin master 
14. git config -l   (tells all info about git rep username emial)
15. q -> exit out of command running 
16. git config-> tells about To configure global or repository-specific settings
17. git checkout / git restore <file name> -> roll back changes not yet added to staging area rolls back once to the head or previous and lates change only  almost same but checkkout deletes resotre just restore the change
Primarily used to switch branches, but also has other uses like discarding changes in the working directory.
18. git checkout -p
19. git reset -> removes files from staging area(unstage/ move head pointer and unstage changes)
20. git reset -p > git asks what to unstage
21. tocuh <file name.txt/md/py> creates a new file in that repo
22. git commit --amend --> modifies lates commit
23. git revert commit_id
24. git log -p(patch) --> tells what has been added or removed similar to diff -u since more lines scroll up or down
25. git show - will take commit id as parameter and shows what changes made there 
26. git log --stat will show how many lines addedd or removed from  each fil in commit
27. git add -p
28. git diff - shows chnages in unstaged files   
29. git diff --staged shows chnages in files in staging area
(changes are staged but not commited)
30. git rm (removes from tracking)
31. git mv old_file new_file  and then commmit it  ... it can also be used to move fiels
32. .gitignore
33. ls -la
34. 1. git commit -a  - a shortcut to stage any change to tracked files and commit them in one step( DOSENT WORK ON NEW FILES) you cant add new files   
When you run git commit -a, Git will open the default text editor for you to write a commit message. The new file will not be listed among the changes to be committed.
After you save and close the editor, Git will create a commit that includes only the modifications to tracked files, excluding the new untracked file.
35. git branch-> list all brnaches
36. git branch <new branch name> -> creates new branch
37. git checkout branch_name->checks out latest snapshot for both files and (switches to new braneche)
38. git checkout -b new_branch (create new branch and switch to it)
39. 
