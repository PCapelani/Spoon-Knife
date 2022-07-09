# My code
Pedro@pedropc MINGW64 ~/Projetos Git/Learn Git/spoon-knife (new-file-test)

$ git branch -a

*  new-file-test

  remotes/origin/HEAD -> origin/main

  remotes/origin/change-the-title

  remotes/origin/main

  remotes/origin/new-file-test

  remotes/origin/test-branch

# 

Pedro@pedropc MINGW64 ~/Projetos Git/Learn Git/spoon-knife (new-file-test)

$ git checkout -b main --track origin/main

Switched to a new branch 'main'

branch 'main' set up to track 'origin/main'.

#

Pedro@pedropc MINGW64 ~/Projetos Git/Learn Git/spoon-knife (main)

$ git branch -a

* main

  new-file-test

  remotes/origin/HEAD -> origin/main

  remotes/origin/change-the-title

  remotes/origin/main

  remotes/origin/new-file-test

  remotes/origin/test-branch

# Delete local repository

$rm -rf .git

# Clone specific branch

For clone all branch and set a specific branch as head

$ git clone -b main2 https://github.com/PCapelani/Spoon-Knife.git

For a single branch only

$ git clone -b master2 --single-branch https://github.com/PCapelani/Spoon-Knife.git

# Delete branch

$ git branch -d branch_name