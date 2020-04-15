# git-easy README

Git Easy makes is really easy to use Git with your project. This is inspired by the git plugin of Sublime Text.

## Manual install on Ubuntu
```
rm -rf extension && mkdir extension && rsync -av --exclude='extension/' --exclude='.git/' --exclude='.vscode/' ./ extension/ && zip -r git-easy-frogconn.vsix extension && rm -rf extension

code --install-extension git-easy-frogconn.vsix
```
## Features

It currently supports these commands -

 - Git Easy: Init
 - Git Easy: Add Origin
 - Git Easy: Add Remote
 - Git Easy: Add File/Directory
 - Git Easy: Add All Modified
 - Git Easy: Commit
 - Git Easy: Pull Current Branch from Origin
 - Git Easy: Push Current Branch to Origin
 - Git Easy: Push Current Branch (to any remote)
 - Git Easy: Status
 - Git Easy: Create New Branch
 - Git Easy: Change/Checkout Existing Branch
 - Git Easy: Log All
 - Git Easy: Log Current File

## Requirements

Currently it has just one requirement - `simple-git`, that will get installed along with the extension.

## Release Notes

### 1.8.0

Fixed bug with log command

### 1.7.0

Added command to add remote.

### 0.0.6

Added Git Log. Clicking a log opens the details of that commit.

### 0.0.5

Minor bugfixes and updated logo

### 0.0.1

Initial release of Git Easy.