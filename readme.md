# Here are a quick set of fundemental commands that you need to know in GIT.

# Basic Git Commands:

1- Initialize a Repository: 
``` sh
git init
```

2- Clone a Repository: 
``` sh
git clone <repository_url>
```

3- Add Changes to Staging Area: 
``` sh 
git add <file(s)>
```

4- Commit Changes: 
``` sh
git commit -m "Commit message"
```

5- Check Repository Status: 
``` sh
git status
```

6- View Commit History: 
``` sh
git log
```

7- Create a New Branch: 
``` sh
git branch <branch_name>
```

8- Switch to a Branch: 
``` sh
git checkout <branch_name>
```

9- Merge Branches: 
``` sh
git merge <branch_name>
```
10- Pull Changes from a Remote Repository: 
``` sh
git pull
```

11- Push Changes to a Remote Repository: 
``` sh
git push
```

#//////////////Advanced Git Commands//////////////

1-View Remote Repositories: 
``` sh
git remote -v
```

2- Fetch Changes from a Remote Repository: 
``` sh
git fetch
```

3- Create a Tag: 
``` sh
git tag <tag_name>
```

4- Cherry-pick Commits: 
``` sh
git cherry-pick <commit_hash>
```

5- Rebase Commits: 
``` sh
git rebase <base_branch>
```

6- Stash Changes: 
``` sh
git stash
```

7- Apply Stashed Changes: 
``` sh
git stash apply
```

8- Reset to a Specific Commit: 
``` sh
git reset <commit_hash> --hard
```

9- Interactive Rebase: 
``` sh
git rebase -i <base_commit>
```

10- Amend the Last Commit: 
``` sh
git commit --amend
```

11- List Git Configurations: 
``` sh
git config --list
```

12- Remove Untracked Files: 
``` sh
git clean -f
```

13- View the Git Log in One Line: 
``` sh
git log --oneline
```

14- Show the Difference Between Two Branches: 
``` sh
git diff <branch1>..<branch2>
```

15- Search for a Commit by Message: 
``` sh
git log --grep "search_keyword"
```










































