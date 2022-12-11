https://www.freecodecamp.org/news/git-diff-command/
- `git diff` (first git add. and changes file again)
Earlier, we ran the git diff command which shows nothing. Because git diff shows the difference between changes in your working directory and staged area. But, we didn't change anything in the working directory after we staged the changes. So, there is nothing different while compared with the staged area. I hope that makes sense.
- Comparing files between two different commits
 `git diff 957fbc92b123030c389bf8b4b874522bdf2db72c ce489262a1ee34340440e55a0b99ea6918e19e7a`
 
 - Comparing files from two branches
 git diff main new_branch ./diff_test.txt
 
 - Comparing two branches(https://www.atlassian.com/git/tutorials/saving-changes/git-diff)
 ```
 git diff branch1..other-feature-branch
 git diff branch1...other-feature-branch
 ```
 
 // checks differnece in file between staging area and repository 
``> git diff --stage`