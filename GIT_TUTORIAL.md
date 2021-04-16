# Getting Started

## Text Editor

You will need a text editor to edit the files.
I suggest using Microsoft's [Visual Studio Code](https://code.visualstudio.com/) because it is lightweight and has good tools built-in.
It is preferred that you have a markdown linter to keep things pretty.
It also has nice graphical tools, so you don't have to deal with git in the command line.

## Install Git

If you don't already have git installed, you can install it with help from this guide:
[https://www.atlassian.com/git/tutorials/install-git](https://www.atlassian.com/git/tutorials/install-git).

## Cloning

You'll need to clone the repository to get started.
You can learn how to use the `clone` command here:
[https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-clone](https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-clone).

After navigating in your file structure to where you want to put the project,
you can download the repository with:

```
git clone https://github.com/cobelu/Long-EZ
```

## Adding Files

You can add a file to the folder on your machine, but git won't it needs to track changes on that file until you add it to the repository.
Use the `add` command to add files to the project.
A tutorial for this is available here:
[https://www.atlassian.com/git/tutorials/saving-changes](https://www.atlassian.com/git/tutorials/saving-changes).

Generally, the command will be:

```
git add <filename>
```

## Committing Files

After you have made changes to the files, you save your work.
When you reach a good checkpoint, you can note your changes with the `commit` command.
Read about that here:
[https://www.atlassian.com/git/tutorials/saving-changes/git-commit](https://www.atlassian.com/git/tutorials/saving-changes/git-commit).

```
git commit -m "<what you did>" <filename>
```

## Pulling Commits

We always perform a `pull` before we push.
This helps avoid problems.

Generally, a pull will look like this:

```
git pull
```

If you have to deal with merges, it's generally much easier to do this in a graphical editor.
Merges are when you have to decide "whose writes win".

## Pushing Commits

After you've done some work and you want to notify everyone else that you made those changes,
you're ready to `push` your results.
[https://www.atlassian.com/git/tutorials/syncing/git-push](https://www.atlassian.com/git/tutorials/syncing/git-push).

```
git push
```

## Branches

Technically, you're supposed to use branches to add changes.
In software, this helps people not push broken code,
which ruins things for everyone else on a team.
We don't have broken code here, so pushing ugly stuff is ok since we're constantly coming back and editing.
That's the point of this project after all!

That said, if you are interested in reading about how branches work,
you can read about it here:
[https://www.atlassian.com/git/tutorials/using-branches](https://www.atlassian.com/git/tutorials/using-branches)

## Questions?

Ask Connor.
