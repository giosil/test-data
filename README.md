# Test data

Collection of data that can be used for development.

## Update

- `git add .`
- `git commit -m "update"`
- `git push`

## Revert and clean 

- `git reset --hard` to discarde any changes not committed to tracked files in the working tree
- `git clean -fxd` to delete untracked file recursively (f) and directories (d) also in .gitignore (x)
- `git rm -r --cached .` to delete cached files
- `git gc --aggressive --prune=now` Cleanup unnecessary files and optimize the local repository

## Revert a file

- `git checkout -- README.md` to revert file README.md to last commit

## To update git client password

- `git config --global credential.helper wincred`

## Contributors

* [Giorgio Silvestris](https://github.com/giosil)
