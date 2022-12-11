# ADD command
1. `git add .`
	First, it only adds files under the current directory. So, if you run git add . within a sub directory, it won't add changes to files outside that sub directory.
	Second, git add . adds both tracked and untracked files.
2. `git add -A`
This will add all changes to all files within the Git repository, regardless of our current directory.
adds both tracked and untracked files.

3. `git add -u`
skip untracked files and only add tracked files.

4. `git add -p`
 gather all changes in tracked files and allow you to review them interactively.
 
 5. `git add fileName`
 add ubtracked file too
 
 6. 
 ``` console
$ git add *.txt

$ git add *.js
```

# Note
`mkdir addCommand commitCommand`
`touch addCommand/gitadd.md`
`git add addCommand commitCommand`
addCommand is tracked but commitCommand is untracked
