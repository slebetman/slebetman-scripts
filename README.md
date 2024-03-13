Useful personal scripts I always have installed
===============================================

Requires `bash`, `node.js` and `tcl`.

## Git related scripts:

- `c [<message>...]` : Git commit with commit message - you don't have
   to quote your commit message
   
- `c. [<message>...]` : Same as `c` but prepends branch name to commit message

- `gitdir` : Prints the project's root directory

- `thisbranch` : Prints current branch name

- `currentbranch [save]` : Saves current branch to a file called `.current`
  or checks out the branch saved to `.current`


## Useful filesystem scripts:

- `upfind <search>` : Looks for the file in the current directory and then in
  the parent directory and then the parent's parent etc. recursively

- `regexp-rename <regex> <replacement> [ok]` : Renames all files matching the
  regex

- `sshmount <server> <mount_point>` : Nicer sshfs for MacOS


## Misc scripts:

- `cgrep [<regex> <colorspec>]...` : Color your stdouts!
