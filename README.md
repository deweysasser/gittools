GIT utilities
=============

A couple of small utilities to extend git


* git-ignore --  add the given file to the project .gitignore file

* git-foreach -- prefix for other git commands to run them in the
  current directory and each subdirectory that contains a git module.
  Rather like `git submodule foreach` except it does not require
  submodules.

* git-remerge-as-branch -- Retroactively create a feature branch.
  For any commits that have not, yet, been pushed, move them onto a
  branch, reset the current branch to the pushed status and merge the
  branch using --no-ff.
