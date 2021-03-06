## Cheat Sheet

Whenever you're confused about git, come read this cheat sheet. Remember that all git commands can be run with the `--help` option. For example:

`$ git branch --help` or `$git log --help`

### Essential Git Commands

####Create a new git repository
`$ git init` - Create a new, local repository

#### Repo Status
`$ git status` - Check the status of your current repository and see which files have changed.

`$ git diff` - Show changes between commits, commit and working tree, etc

#### Repo History
`$ git log` - Show commit logs

`$ git log --oneline --decorate --color --graph --all` - adds format and decoration

`$ git log -p [filename]` - Shows git log with file contents visible

#### Stage files to commit
`$ git add <filename>` - Add file contents to the index

`$ git add -A` - Adds all files' contents to the index

#### Commit changes in staged files
`$ git commit -m "<commit message>"` - adds staged changes to commited changes

#### Branching
`$ git branch <branch name>` - Creates a new branch

`$ git branch` - List, create, or delete branches.

`$ git checkout <branch name>` - Switch branches or restore working tree files

#### Merging

`$ git merge <branch name>` - Join two or more development histories together

Edit to push to GitHub 
