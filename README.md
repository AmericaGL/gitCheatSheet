## Cheat Sheet 

Whenever you're confused about git, come read this cheat sheet. Remember that all git commands can be run with the `--help` option. For example: 

`$ git branch --help` or `$git log --help`

### Essential Git Commands

####Create a new git repository
`$ git init` - Create a new, local repository

#### Repo Status
`$ git status` - Check the status of your current repository and see which files have changed.

`$ git diff` - - Show changes between commits, commit and working tree, etc.

#### Repo History
`$ git log` - Show commit logs

`$ git log --oneline --decorate --color --graph --all` - __Fill Me Out__

`$ git log -p [filename]` Display the patch representing each commit. This shows the full diff of each commit, which is the most detailed view you can have of your project history.

#### Stage files to commit
`$ git add <filename>` - Add file contents to the index

`$ git add -A` - Tell the command to automatically stage files that have been modified and deleted, but new files you have not told Git about are not affected.

#### Commit changes in staged files
`$ git commit -m "<commit message>"` - Record changes to the repository
#### Branching
`$ git branch <branch name>` - __Fill Me Out__

`$ git branch` - __Fill Me Out__

`$ git checkout <branch name>` - __Fill Me Out__

#### Merging

`$ git merge <branch name>` - __Fill Me Out__