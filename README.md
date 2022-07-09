### Well hello there!

This repository is meant to provide an example for *forking* a repository on GitHub.

Creating a *fork* is producing a personal copy of someone else's project. Forks act as a sort of bridge between the original repository and your personal copy. You can submit *Pull Requests* to help make other people's projects better by offering your changes up to the original project. Forking is at the core of social coding at GitHub.

After forking this repository, you can make some changes to the project, and submit [a Pull Request](https://github.com/octocat/Spoon-Knife/pulls) as practice.

For some more information on how to fork a repository, [check out our guide, "Forking Projects""](http://guides.github.com/overviews/forking/). Thanks! :sparkling_heart:

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