# Git Experiments

This is the readme of this project. We also will add information about git too here.

## git init

This is a repository to learn the nuances of git version control system.

Git repo always will have a .git folder created when we run

```
git init

```

If we remove the .git folder, that means, git will no longer monitor our repository. It will just turn out to be a folder.

You can also create bare repositories that just act as a central repo. Bare repositories will not have any working tree in them. You can not directly work on a bare repository. You need to clone a bare repository into your favourite location and can work on that. You can make any modifications in your working copy of the repository and then can do a git push from there.

```
rm -rf .git
```

## git ignore

We need to ensure, we add a .gitignore file at the top of our repository, which will contain specifications to avoid committing certain files we dont care. For example, some files created by Operating system, or some editor extensions.

We can take help of [gitignore.io](https://www.toptal.com/developers/gitignore) app available in internet

## git status

This command `git status` is a command, that will show you what files are changed, what files are in untracked mode, and what files have been placed already in staging area.

## git remotes

A remote in git, is nothing but a central bare repo possibly hosted by a git server provider such as github
