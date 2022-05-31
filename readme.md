# Git Experiments

## git init

This is a repository to learn the nuances of git version control system.

Git repo always will have a .git folder created when we run

```
git init

```

If we remove the .git folder, that means, git will no longer monitor our repository. It will just turn out to be a folder.

```
rm -rf .git
```

## git ignore

We need to ensure, we add a .gitignore file at the top of our repository, which will contain specifications to avoid committing certain files we dont care. For example, some files created by Operating system, or some editor extensions.

We can take help of [gitignore.io](https://www.toptal.com/developers/gitignore) app available in internet

## git status

This command `git status` is a command, that will show you what files are changed, what files are in untracked mode, and what files have been placed already in staging area.
