https://github.com/git-guides/git-status
https://michaelheap.com/git-status-untracked/
before git commit use git status
```
> git status 
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   untracked.txt
	new file:   untrackedfile/untrack.pdf
      
> git status -s
A  untracked.txt
A  untrackedfile/untrack.pdf

> git status -v
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   untracked.txt
	new file:   untrackedfile/untrack.pdf

diff --git a/untracked.txt b/untracked.txt
new file mode 100644
index 0000000..0e37c88
--- /dev/null
+++ b/untracked.txt
@@ -0,0 +1 @@
+apple
\ No newline at end of file
diff --git a/untrackedfile/untrack.pdf b/untrackedfile/untrack.pdf
new file mode 100644
index 0000000..e69de29


```