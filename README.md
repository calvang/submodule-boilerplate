# Git Submodule Boilerplate

This boilerplate template implements an example submodule and git aliases for
managing them.

## Setup

After cloning the repo, initialize and fetch the submodule:

```
git submodule update --init
```

Then, ensure you are using the local `.gitconfig file` in this repo:

```
git config --local include.path ../.gitconfig
```

## About Git Submodules

### Adding a Submodule

To add a submodule, run: 

```
git submodule add <repo-url>
```

### Managing Submodules from the Parent Repo



## Git Aliases

To view or edit this repo's git aliases, go to `.gitconfig`.

The `!git` string is a placeholder for the `git` command, and aliases execute
multiple commands.

## Resources

For more information about git aliases, submodules, and subtrees, check out these links:

- https://git-scm.com/book/en/v2/Git-Basics-Git-Aliases
- https://git-scm.com/book/en/v2/Git-Tools-Submodules
- https://martowen.com/2016/05/01/git-submodules-vs-git-subtrees/

Including a Git config file in a repo:
- https://stackoverflow.com/questions/18329621/how-to-store-a-git-config-as-part-of-the-repository

Pulling from submodules:
- https://stackoverflow.com/questions/33714063/how-to-update-submodules-in-git
