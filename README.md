# Git-Practice
Git advanced

***  Part 1: Refining Git History (10 Challenges) ***

***  1. Missing File Fix: ***
 git status && git log
On branch main
Your branch is ahead of 'origin/main' by 3 commits.       
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        test4.md

no changes added to commit (use "git add" and/or "git commit -a")
commit 2e700e32f9caa26850e123a64416c76c302a62c4 (HEAD -> main)
Author: Rebecca Mutoni <rbccmtni1@gmail.com>
Date:   Tue May 21 16:28:41 2024 +0200

    chore: Create third and fourth files

commit 306cf5e8dc63b28a8c82a2e3f20e2d3af2d114b2
Author: Rebecca Mutoni <rbccmtni1@gmail.com>
chore: Create third and fourth files
Date:   Tue May 21 16:28:36 2024 +0200

    chore: Create another file

commit ba4e93c6b132a7ae58ca6fbabaa51b2e8db0a6a8
Author: Rebecca Mutoni <rbccmtni1@gmail.com>
Date:   Tue May 21 16:28:35 2024 +0200

    chore: Create initial file

commit 59f37db43f33f594b798aa56fd2d5a5bbc4cbf3f (origin/main, origin/HEAD)
Author: Rebecca MUTONI <82598316+Beccatoni@users.noreply.github.com>

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Git-Practice (main)     
$

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Git-Practice (main)     
$ git add test4.md

The Gym@DESKTOP-FTJIN5G MINGW64 ~/Git-Practice (main)     
$ git commit --amend
[main 0e65535] chore: Create third and fourth files
 Date: Tue May 21 16:28:41 2024 +0200
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 test3.md
 create mode 100644 test4.md


*** 2.Editing Commit History:  ***


