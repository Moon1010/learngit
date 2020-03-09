This project is just a demo how to use git

1. git init
2. git status
3. git add
4. git commit

5. git log
6. git show
7. git diff

8. working directory
9. staging area
10. git repository

12. git checkout -- <file>
13. git reset

14. git checkout -b <branch> (branching)
15. git checkout <branck>
16. git merge

17. git reset --soft <to_commit>
18. git reset --mixed <to_commit>
19. git reset --hard <to_commit>

20. git revert <commit>

21. gitignore

22. git clone
22. git pull

23. Pull request
	1. git checkout -b <feature_branch>
	2. git push origin <branch>
	3. create a pull request on Github
	4. review code
	5. merge to master

//Resolve conflicts
When will conflicts happen?
	1. Changing the same file + same line
	2. A deleted file X, B modified file x

24. Method 1:
	1. Using 'git rebase'
	2. Resole conflict
	3. Push again with -f

25. Method 2:
	1. Merge updated master to feature branch
	2. Resolve conflict
	3. Commit and push