## Cheat Sheet

Whenever you're confused about git, come read this cheat sheet. Remember that all git commands can be run with the `--help` option. For example:

`$ git branch --help` or `$git log --help`

### Essential Git Commands

####Create a new git repository
`$ git init` - Create a new, local repository

#### Repo Status
`$ git status` - Check the status of your current repository and see which files have changed.

`$ git diff` - __Fill Me Out__

#### Repo History
`$ git log` - __Fill Me Out__

`$ git log --oneline --decorate --color --graph --all` - __Fill Me Out__

`$ git log -p [filename]` __Fill Me Out__

#### Stage files to commit
`$ git add <filename>` - __Fill Me Out__

`$ git add -A` - __Fill Me Out__

#### Commit changes in staged files
`$ git commit -m "<commit message>"` - __Fill Me Out__

#### Branching
`$ git branch <branch name>` - __Fill Me Out__

`$ git branch` - __Fill Me Out__

`$ git checkout <branch name>` - __Fill Me Out__

#### Merging

`$ git merge <branch name>` - __Fill Me Out__

## Commands for working with a remote repository (e.g. Github)

`$ git clone <repo path or URL>` - clone a repository into a new directory.

`$ git remote` - List all remotes for the current repo.

`$ git remote add <remote name> <remote path or URL>` - adds a remote to your repo.

`$ git pull <remote name> <branch name>` - Pull down changes from a remote and integrate them into your repo. Performs `git fetch` and then `git merge`.

`$ git push <remote name> <branch name>` - Send your changes to the remote to be merged.
