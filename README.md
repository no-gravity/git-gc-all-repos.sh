# git-gc-all-repos.sh
Perform garbage collection on all git repos in a given directory

It uses "git prune -v" to delete obsolete objects.

"git gc --aggressive --prune=all" would result in even smaller
repos, but would also bloat incremental backups as it changes
the content of files.

License: GNU General Public License, version 2
