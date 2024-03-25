$ git remote add origin https://github.com/kchstar/inbrozz.git

# error
Another git process seems to be running in this repository, e.g.
an editor opened by 'git commit'. Please make sure all processes
are terminated then try again. If it still fails, a git process
may have crashed in this repository earlier:
remove the file manually to continue.
$ rm -f ./.git/index.lock

# error
nothing to commit, working tree clean

# 
$ find . -name '.git'
$ rm -rf '.git'
$ git rm -rf --cached

# error 
On branch main

Initial commit

nothing to commit (create/copy files and use "git add" to track)