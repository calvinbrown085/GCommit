# GCommit

This is a little bash script I wrote to making pushing to your current branch easier.

Steps.

1. Make sure gcommit is part of your bash profile, so it's runnable anywhere in the terminal.
1. `git add` *, * being whatever files you would like to commit
1. `gcommit "Commit Message"`


Notes.

This uses the secure push by github https://help.github.com/articles/managing-commit-signature-verification/ if you don't have this setup

feel free to remove `-S` in the script, and it should work just fine.
