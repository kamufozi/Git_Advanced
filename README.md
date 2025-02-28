## Challenge 1
 ### Missing File Fix:

Run git status and git log to assess the current state of your repository.
From the status you will see that you forgot to add test4.md in the last commit.
Challenge: Recover from this error by staging/adding test4.md and amending the commit message with an appropriate description
 ### Output:
Fozi Chris@DESKTOP-EI6IC2P MINGW64 ~/OneDrive/Desktop/Git_Advanced (main)
$ git log
commit 9a06b617fb5775c1d984379392f49c7c3cfb7245 (HEAD -> main, origin/main)
Author: Fozi Chris <kamufozi679@gmail.com>
Date:   Fri Feb 28 14:03:39 2025 +0200

    chore: Create third and fourth files

commit 158d67503baa9e0f990096663b5255f5298f5c65
Author: Fozi Chris <kamufozi679@gmail.com>
Date:   Fri Feb 28 14:03:39 2025 +0200

Fozi Chris@DESKTOP-EI6IC2P MINGW64 ~/OneDrive/Desktop/Git_Advanced (main)
$ git log --oneline
9a06b61 (HEAD -> main, origin/main) chore: Create third and fourth files
158d675 chore: Create another file
fdd6239 chore: Create initial file
3da3d6c Made a file

Fozi Chris@DESKTOP-EI6IC2P MINGW64 ~/OneDrive/Desktop/Git_Advanced (main)
$ git add .

Fozi Chris@DESKTOP-EI6IC2P MINGW64 ~/OneDrive/Desktop/Git_Advanced (main)
$ git commit --amend -m 'Added the test4.md and the readme.md files'
[main 2a2b03a] Added the test4.md and the readme.md files
 Date: Fri Feb 28 14:03:39 2025 +0200
 3 files changed, 8 insertions(+)
 create mode 100644 README.md
 create mode 100644 test3.md
 create mode 100644 test4.md

