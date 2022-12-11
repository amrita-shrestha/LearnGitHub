A tag points to a specific commit on any branch. You cannot add more code to a tag — it is a reference to a specific commit, kind of like a snapshot.

When would you want something like this? It is useful to create tags when releasing versions. When checking out a tag you can always be sure you’ll be getting the same code each time.

A branch is an active line of development whereas a tag is a an immutable reference to a specific commit on a branch.

```
> git tag <tagname>

// add description while creating tag
> git tag <tagname> -a
```