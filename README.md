# Ruby Scripts by Patrick Goodwin

## Table of Contents
- [Count Files](#count-files)
- [Update Git](#update-git)

## Count Files
This script counts the number of files in the current directory and its subdirectories. It can optionally exclude the `node_modules` directory.

### Arguments
- `--includenode`: Include files in the `node_modules` directory.

### Example Usage
```
ruby count_files.rb
```

## Update Git
This script updates the current Git branch by fetching the latest changes and merging them from a specified branch (default is `master`).

### Arguments
- `-branch`: The branch to merge into the current branch. If not specified, `master` is used.

### Example Usage
```
ruby update_git.rb -branch develop
```
