# Version Control Systems
It's a software used to keep track of the history of files in your codebase and the modifications applied to them.
Git is an example of a VCS.
It keeps track of:
- What changes were made to files?
- Who made those changes?
- When were those changes made?

Staging is adding files to be tracked and ready for commit.
Commit is taking a snapshot of the current state of the repository.
---
# LEARNING GIT
## git basic commands
- `git init` - Initializes a brand new Git repository and begins tracking an existing directory. Adds a hidden subfolder that houses the internal data structure required for version control
- `git clone` - creates a local copy of a project that already exists remotely.
- `git add` - stages a change
- `git commit` - saves a snapshot to the project history and completes the change tracking process.
- `git sttus` - shows the status of changes as untracked , modified or staged
- `git branch `- shows the branches being worked on locally
- `git merge` - merges lines of development together. Typically used to combine changes made on two dinstinct branches.
- `git pul` - Updates the local line of development with updates from its remote counterpart.
- `git push` - Updates the remote repository with any commits made locally.