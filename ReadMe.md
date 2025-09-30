### My answers to git exercises

## Getting Started
```
user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git add test1.dm

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git commit -m "chore: Create initial file additional text"
[main c613a5b] chore: Create initial file additional text
 1 file changed, 1 insertion(+), 1 deletion(-)

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git add test2.dm

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git commit -m "chore: Create second file"
[main a8e129d] chore: Create second file
 1 file changed, 1 insertion(+)

n)
$ git commit -m "chore: Create third file"
[main 9051ca5] chore: Create third file
 1 file changed, 1 insertion(+)

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git add test4.dm

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git commit -m "chore: Create fourth file"
[main 7ccab44] chore: Create fourth file
 1 file changed, 1 insertion(+)

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
```
## Challenges: 
# part 1 : Refining Git history (10 challenges)
```

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git add test1.dm

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git commit -m "chore: Create initial file additional text"
[main c613a5b] chore: Create initial file additional text
 1 file changed, 1 insertion(+), 1 deletion(-)

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git add test2.dm

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git commit -m "chore: Create second file"
[main a8e129d] chore: Create second file
 1 file changed, 1 insertion(+)

n)
$ git commit -m "chore: Create third file"
[main 9051ca5] chore: Create third file
 1 file changed, 1 insertion(+)

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git add test4.dm

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git commit -m "chore: Create fourth file"
[main 7ccab44] chore: Create fourth file
 1 file changed, 1 insertion(+)

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 4 commits.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)     
        modified:   ReadMe.md
        modified:   test5.dm

no changes added to commit (use "git add" and/or "git commit -a")

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git log
commit 7ccab44b20fb13fc77c26ea6c32f4e741a05e9b5 (HEAD -> main)
Author: Irael <ellycreativity8@gmail.com>
Date:   Tue Sep 30 16:11:10 2025 +0200

    chore: Create fourth file

commit 9051ca53e0e002a773892be24730ebd175424451
Author: Irael <ellycreativity8@gmail.com>
Date:   Tue Sep 30 16:09:59 2025 +0200

    chore: Create third file

commit a8e129ddbffec7072692f3e874416cd06884f8e6
Author: Irael <ellycreativity8@gmail.com>
Date:   Tue Sep 30 16:09:24 2025 +0200

    chore: Create second file

commit c613a5ba1cee6769abe4e53a8cf3bad2f4a20f3b
Author: Irael <ellycreativity8@gmail.com>
Date:   Tue Sep 30 16:07:20 2025 +0200

    chore: Create initial file additional text

commit d7b7b55dbe50fc12af3122779497668634dbf363 (origin/main, origin/HEAD)  
Merge: 2f416dd 7e55fcd
Author: Irael <ellycreativity8@gmail.com>
Date:   Tue Sep 30 14:13:49 2025 +0200

    Merge branch 'main' of https://github.com/elyse-iradukunda/GitExercisesPhase2

commit 2f416dd2b323b310c5f7a86ec7d7eb4516a0036b
Author: Irael <ellycreativity8@gmail.com>
Date:   Tue Sep 30 14:08:31 2025 +0200

    chore: adding read me file  with answers to git exercises

commit 7e55fcdb21ed591a1895cf7ccfe0cf94a3f9612b
Merge: c4b4a39 226a125
Author: Elyse Iradukunda <ellycreativity8@gmail.com>
Date:   Tue Sep 30 13:50:44 2025 +0200

    Merge pull request #1 from elyse-iradukunda/ft/branch

    Ft/branch

commit 226a12560c6efd1451c373b3d87ac8b71bc91095 (origin/ft/branch, ft/branch)
Author: Irael <ellycreativity8@gmail.com>
Date:   Tue Sep 30 13:49:30 2025 +0200

    Prepare for pull request

commit c4b4a3992697d676c8a2b3f2e1e6c3aa5d40291e
Author: Irael <ellycreativity8@gmail.com>
Date:   Tue Sep 30 08:11:59 2025 +0200

    chore:Implemented test 5

commit c62ab5a64b049734e1284ac78b22f2c71a105920
Author: Irael <ellycreativity8@gmail.com>
Date:   Tue Sep 30 08:11:59 2025 +0200

    chore:Implemented test 5

commit ebf8e4ed3980175067ec49eed26312696ab7d0b6
Author: Irael <ellycreativity8@gmail.com>
Date:   Tue Sep 30 07:43:36 2025 +0200

    Creating fourth file

commit 3563ea5a0890256b421f59716f9695326afeac8f
Author: Irael <ellycreativity8@gmail.com>
Date:   Mon Sep 29 20:04:27 2025 +0200

    fix: forgotten to commit test4.dm

commit 8afa30b0fe3d0759cd0fd134f2aa384ccc7cdd08
Author: Irael <ellycreativity8@gmail.com>
Date:   Mon Sep 29 20:04:03 2025 +0200

    chore: Creating another file

commit 9d51a7baf684d1432e7fadf1416f5731c02dc75e
Author: Irael <ellycreativity8@gmail.com>
Date:   Mon Sep 29 20:02:36 2025 +0200

    chore: Creating initial file

```

# Keeping History tidy - squashing commits

```

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git add unwanted.txt

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git commit -m'Unwanted commit'
[main 0fe6752] Unwanted commit
 1 file changed, 0 insertions(+), 0 deletions(-)    
 create mode 100644 unwanted.txt

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git rebase -i HEAD~2
error: Your local changes to the following files would be overwritten by checkout:
        ReadMe.md
Please commit your changes or stash them before you switch branches.
Aborting
error: could not detach HEAD

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git rebase -i HEAD~2
Successfully rebased and updated refs/heads/main.

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
```

# Splitting a Commit

```
  
user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git checkout ft/branch
error: Your local changes to the following files would be overwritten by checkout:
        ReadMe.md
        test5.dm
Please commit your changes or stash them before you switch branches.
Aborting

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git push origin main
Enumerating objects: 28, done.
Counting objects: 100% (27/27), done.
To https://github.com/elyse-iradukunda/GitExercisesPhase2.git
   d7b7b55..ba67a52  main -> main

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git checkout ft/branch
error: Your local changes to the following files would be overwritten by checkout:
        ReadMe.md
        test5.dm
Please commit your changes or stash them before you switch branches.
Aborting

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git commit -m'change here is made'
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   ReadMe.md
        modified:   test5.dm

no changes added to commit (use "git add" and/or "git commit -a")

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git add .

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git commit -m'change here is made'
[main f73fce7] change here is made
 2 files changed, 36 insertions(+), 2 deletions(-)  

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git checkout ft/branch
Switched to branch 'ft/branch'
Your branch is up to date with 'origin/ft/branch'.  

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/branch)
$ git add test5.dm

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/branch)
$ git commit -m'Implement test5.dm file'
[ft/branch 5467408] Implement test5.dm file
 1 file changed, 1 insertion(+), 1 deletion(-)      

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/branch)
$ git checkout main
Switched to branch 'main'
Auto-merging test5.dm
CONFLICT (content): Merge conflict in test5.dm
error: could not apply 5467408... Implement test5.dm file
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git cherry-pick --continue".
hint: You can instead skip this commit with "git cherry-pick --skip".
hint: To abort and get back to the state before "git cherry-pick",
hint: run "git cherry-pick --abort".
hint: Disable this message with "git config set advice.mergeConflict false"

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main|CHERRY-PICKING)
$ git cherry-pick --continue
error: no cherry-pick or revert in progress
fatal: cherry-pick failed

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)

```
# Visualizing Commit History (Bonus)

``

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git checkout ft/branch
error: Your local changes to the following files would be overwritten by checkout:
        ReadMe.md
        test5.dm
Please commit your changes or stash them before you switch branches.
Aborting

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git push origin main
Enumerating objects: 28, done.
Counting objects: 100% (27/27), done.
To https://github.com/elyse-iradukunda/GitExercisesPhase2.git
   d7b7b55..ba67a52  main -> main

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git checkout ft/branch
error: Your local changes to the following files would be overwritten by checkout:
        ReadMe.md
        test5.dm
Please commit your changes or stash them before you switch branches.
Aborting

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git commit -m'change here is made'
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   ReadMe.md
        modified:   test5.dm

no changes added to commit (use "git add" and/or "git commit -a")

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git add .

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git commit -m'change here is made'
[main f73fce7] change here is made
 2 files changed, 36 insertions(+), 2 deletions(-)  

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git checkout ft/branch
Switched to branch 'ft/branch'
Your branch is up to date with 'origin/ft/branch'.  

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/branch)
$ git add test5.dm

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/branch)
$ git commit -m'Implement test5.dm file'
[ft/branch 5467408] Implement test5.dm file
 1 file changed, 1 insertion(+), 1 deletion(-)      

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/branch)
$ git checkout main
Switched to branch 'main'
Auto-merging test5.dm
CONFLICT (content): Merge conflict in test5.dm
error: could not apply 5467408... Implement test5.dm file
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git cherry-pick --continue".
hint: You can instead skip this commit with "git cherry-pick --skip".
hint: To abort and get back to the state before "git cherry-pick",
hint: run "git cherry-pick --abort".
hint: Disable this message with "git config set advice.mergeConflict false"

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main|CHERRY-PICKING)
$ git cherry-pick --continue
error: no cherry-pick or revert in progress
fatal: cherry-pick failed

error: could not apply 5467408... Implement test5.dm file
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git cherry-pick --continue".
hint: You can instead skip this commit with "git cherry-pick --skip".
hint: To abort and get back to the state before "git cherry-pick",
hint: run "git cherry-pick --abort".
hint: Disable this message with "git config set advice.mergeConflict false"

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main|CHERRY-PICKING)
$ git cherry-pick --continue
error: no cherry-pick or revert in progress
fatal: cherry-pick failed

hint: run "git cherry-pick --abort".
hint: Disable this message with "git config set advice.mergeConflict false"

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main|CHERRY-PICKING)
$ git cherry-pick --continue
error: no cherry-pick or revert in progress
fatal: cherry-pick failed

$ git cherry-pick --continue
error: no cherry-pick or revert in progress
fatal: cherry-pick failed


user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git reset
Unstaged changes after reset:
M       ReadMe.md

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git log --oneline --graph --all
* 99bf625 (HEAD -> main) Implement test5.dm file
* f73fce7 change here is made
* ba67a52 (origin/main, origin/HEAD) Unwanted commit
* 730d1d6 added 5th and read me file
* b7eb315 adding 4th file
* 94c280a add test4.dm with description
* 9051ca5 chore: Create third file
* a8e129d chore: Create second file
* c613a5b chore: Create initial file additional text
*   d7b7b55 Merge branch 'main' of https://github.com/elyse-iradukunda/GitExercisesPhase2
|\
| *   7e55fcd Merge pull request #1 from elyse-iradukunda/ft/branch
| |\
* | | 2f416dd chore: adding read me file  with answers to git exercises
|/ /
* | c4b4a39 chore:Implemented test 5
| | * 5467408 (ft/branch) Implement test5.dm file
| |/
| * 226a125 (origin/ft/branch) Prepare for pull request
| * c62ab5a chore:Implemented test 5
|/
* ebf8e4e Creating fourth file
* 3563ea5 fix: forgotten to commit test4.dm
* 8afa30b chore: Creating another file
* 9d51a7b chore: Creating initial file
(END)
``
# Reflogs

```

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git checkout ft/branch
error: Your local changes to the following files would be overwritten by checkout:
        ReadMe.md
        test5.dm
Please commit your changes or stash them before you switch branches.
Aborting

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git push origin main
Enumerating objects: 28, done.
Counting objects: 100% (27/27), done.
To https://github.com/elyse-iradukunda/GitExercisesPhase2.git
   d7b7b55..ba67a52  main -> main

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git checkout ft/branch
error: Your local changes to the following files would be overwritten by checkout:
        ReadMe.md
        test5.dm
Please commit your changes or stash them before you switch branches.
Aborting

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git commit -m'change here is made'
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   ReadMe.md
        modified:   test5.dm

no changes added to commit (use "git add" and/or "git commit -a")

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git add .

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git commit -m'change here is made'
[main f73fce7] change here is made
 2 files changed, 36 insertions(+), 2 deletions(-)  

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git checkout ft/branch
Switched to branch 'ft/branch'
Your branch is up to date with 'origin/ft/branch'.  

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/branch)
$ git add test5.dm

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/branch)
$ git commit -m'Implement test5.dm file'
[ft/branch 5467408] Implement test5.dm file
 1 file changed, 1 insertion(+), 1 deletion(-)      

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/branch)
$ git checkout main
Switched to branch 'main'
Auto-merging test5.dm
CONFLICT (content): Merge conflict in test5.dm
error: could not apply 5467408... Implement test5.dm file
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git cherry-pick --continue".
hint: You can instead skip this commit with "git cherry-pick --skip".
hint: To abort and get back to the state before "git cherry-pick",
hint: run "git cherry-pick --abort".
hint: Disable this message with "git config set advice.mergeConflict false"

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main|CHERRY-PICKING)
$ git cherry-pick --continue
error: no cherry-pick or revert in progress
fatal: cherry-pick failed

error: could not apply 5467408... Implement test5.dm file
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git cherry-pick --continue".
hint: You can instead skip this commit with "git cherry-pick --skip".
hint: To abort and get back to the state before "git cherry-pick",
hint: run "git cherry-pick --abort".
hint: Disable this message with "git config set advice.mergeConflict false"

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main|CHERRY-PICKING)
$ git cherry-pick --continue
error: no cherry-pick or revert in progress
fatal: cherry-pick failed

hint: run "git cherry-pick --abort".
hint: Disable this message with "git config set advice.mergeConflict false"

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main|CHERRY-PICKING)
$ git cherry-pick --continue
error: no cherry-pick or revert in progress
fatal: cherry-pick failed

$ git cherry-pick --continue
error: no cherry-pick or revert in progress
fatal: cherry-pick failed


user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git reset
Unstaged changes after reset:
M       ReadMe.md

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git log --oneline --graph --all
* 99bf625 (HEAD -> main) Implement test5.dm file
* f73fce7 change here is made
* ba67a52 (origin/main, origin/HEAD) Unwanted commit
* 730d1d6 added 5th and read me file
* b7eb315 adding 4th file
* 94c280a add test4.dm with description
* 9051ca5 chore: Create third file
* a8e129d chore: Create second file
* c613a5b chore: Create initial file additional text
*   d7b7b55 Merge branch 'main' of https://github.com/elyse-iradukunda/GitExercisesPhase2
|\
| *   7e55fcd Merge pull request #1 from elyse-iradukunda/ft/branch
| |\
* | | 2f416dd chore: adding read me file  with answers to git exercises
|/ /
* | c4b4a39 chore:Implemented test 5
| | * 5467408 (ft/branch) Implement test5.dm file
| |/
| * 226a125 (origin/ft/branch) Prepare for pull request
| * c62ab5a chore:Implemented test 5
|/
* ebf8e4e Creating fourth file
* 3563ea5 fix: forgotten to commit test4.dm
* 8afa30b chore: Creating another file
* 9d51a7b chore: Creating initial file
(END)
```
 create mode 100644 test5.dm

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/branch)
$ git log
commit c62ab5a64b049734e1284ac78b22f2c71a105920 (HEAD -> ft/branch)
Author: Irael <ellycreativity8@gmail.com>
Date:   Tue Sep 30 08:11:59 2025 +0200

    chore:Implemented test 5

commit ebf8e4ed3980175067ec49eed26312696ab7d0b6 (main)
Author: Irael <ellycreativity8@gmail.com>
Date:   Tue Sep 30 07:43:36 2025 +0200
commit c62ab5a64b049734e1284ac78b22f2c71a105920 (HEAD -> ft/branch)
Author: Irael <ellycreativity8@gmail.com>
Date:   Tue Sep 30 08:11:59 2025 +0200

    chore:Implemented test 5

commit ebf8e4ed3980175067ec49eed26312696ab7d0b6 (main)
Author: Irael <ellycreativity8@gmail.com>
Date:   Tue Sep 30 07:43:36 2025 +0200

    Creating fourth file

commit 3563ea5a0890256b421f59716f9695326afeac8f
Author: Irael <ellycreativity8@gmail.com>
Date:   Mon Sep 29 20:04:27 2025 +0200

    fix: forgotten to commit test4.dm

commit 8afa30b0fe3d0759cd0fd134f2aa384ccc7cdd08

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/branch)
$ git checkout main
Switched to branch 'main'
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git che
checkout      cherry        cherry-pick   

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git cherry-pick 8afa30b0fe3d0759cd0fd134f2aa384ccc7cdd08
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

You are currently cherry-picking commit 8afa30b.
  (all conflicts fixed: run "git cherry-pick --continue")
  (use "git cherry-pick --skip" to skip this patch)
  (use "git cherry-pick --abort" to cancel the cherry-pick operation)

nothing to commit, working tree clean
The previous cherry-pick is now empty, possibly due to conflict resolution.
If you wish to commit it anyway, use:

    git commit --allow-empty

Otherwise, please use 'git cherry-pick --skip'

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main|CHERRY-PICKING)
$ git checkout ft/branch
Switched to branch 'ft/branch'
warning: cancelling a cherry picking in progress

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/branch)
$ git log
commit c62ab5a64b049734e1284ac78b22f2c71a105920 (HEAD -> ft/branch)
Author: Irael <ellycreativity8@gmail.com>
Date:   Tue Sep 30 08:11:59 2025 +0200

    chore:Implemented test 5

commit ebf8e4ed3980175067ec49eed26312696ab7d0b6 (main)
Author: Irael <ellycreativity8@gmail.com>
Date:   Tue Sep 30 07:43:36 2025 +0200

    Creating fourth file

commit 3563ea5a0890256b421f59716f9695326afeac8f
Author: Irael <ellycreativity8@gmail.com>
Date:   Mon Sep 29 20:04:27 2025 +0200

    fix: forgotten to commit test4.dm

commit 8afa30b0fe3d0759cd0fd134f2aa384ccc7cdd08
Author: Irael <ellycreativity8@gmail.com>
Date:   Mon Sep 29 20:04:03 2025 +0200

    chore: Creating another file

commit 9d51a7baf684d1432e7fadf1416f5731c02dc75e
Author: Irael <ellycreativity8@gmail.com>
Date:   Mon Sep 29 20:02:36 2025 +0200

    chore: Creating initial file
(END)
 *  History restored 


user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/branch)
$ git status
On branch ft/branch
nothing to commit, working tree clean

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/branch)
$ git log
commit c62ab5a64b049734e1284ac78b22f2c71a105920 (HEAD -> ft/branch)
Author: Irael <ellycreativity8@gmail.com>
Date:   Tue Sep 30 08:11:59 2025 +0200

    chore:Implemented test 5

commit ebf8e4ed3980175067ec49eed26312696ab7d0b6 (main)
Author: Irael <ellycreativity8@gmail.com>
Date:   Tue Sep 30 07:43:36 2025 +0200

    Creating fourth file

commit 3563ea5a0890256b421f59716f9695326afeac8f
Author: Irael <ellycreativity8@gmail.com>
Date:   Mon Sep 29 20:04:27 2025 +0200

    fix: forgotten to commit test4.dm

commit 8afa30b0fe3d0759cd0fd134f2aa384ccc7cdd08
Author: Irael <ellycreativity8@gmail.com>
Date:   Mon Sep 29 20:04:03 2025 +0200

    chore: Creating another file

commit 9d51a7baf684d1432e7fadf1416f5731c02dc75e
Author: Irael <ellycreativity8@gmail.com>
Date:   Mon Sep 29 20:02:36 2025 +0200

    chore: Creating initial file

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/branch)
$ git log --oneline
c62ab5a (HEAD -> ft/branch) chore:Implemented test 5
ebf8e4e (main) Creating fourth file
3563ea5 fix: forgotten to commit test4.dm
8afa30b chore: Creating another file
9d51a7b chore: Creating initial file

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/branch)
$ git checkout main
Switched to branch 'main'
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git cherry-pick c62ab5a
[main c4b4a39] chore:Implemented test 5
 Date: Tue Sep 30 08:11:59 2025 +0200
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 test5.dm

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git push origin main
Enumerating objects: 13, done.
Counting objects: 100% (13/13), done.
Delta compression using up to 16 threads
Compressing objects: 100% (9/9), done.
Writing objects: 100% (13/13), 1.09 KiB | 372.00 KiB/s, done.
Total 13 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), done.
To https://github.com/elyse-iradukunda/GitExercisesPhase2.git
 * [new branch]      main -> main

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git checkout ft/branch 
Switched to branch 'ft/branch'

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/branch)
$ git push
fatal: The current branch ft/branch has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/branch

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/branch)
$ git commit -m'first pull request'
On branch ft/branch
nothing to commit, working tree clean

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/branch)
$ git add .

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/branch)
$ git push
fatal: The current branch ft/branch has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/branch

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/branch)
$ git commit -m'first pull request'
On branch ft/branch
nothing to commit, working tree clean

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/branch)
$ git add test5.dm

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/branch)
$ git commit -m'Prepare for pull request'
[ft/branch 226a125] Prepare for pull request
 1 file changed, 1 insertion(+)

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/branch)
$ git push
fatal: The current branch ft/branch has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/branch

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'ft/branch' on GitHub by visiting:
remote:      https://github.com/elyse-iradukunda/GitExercisesPhase2/pull/new/ft/branch
remote:
To https://github.com/elyse-iradukunda/GitExercisesPhase2.git
 * [new branch]      ft/branch -> ft/branch
branch 'ft/branch' set up to track 'origin/ft/branch'.

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/branch)
$ git log --oneline --graph --decorate
* 226a125 (HEAD -> ft/branch, origin/ft/branch) Prepare for pull request
* c62ab5a chore:Implemented test 5
* ebf8e4e Creating fourth file
* 3563ea5 fix: forgotten to commit test4.dm
* 8afa30b chore: Creating another file
* 9d51a7b chore: Creating initial file

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/branch)


### Branching Basics (10 challenges)

## Feature Branch Creation:

```

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git checkout -b ft/new-feature
Switched to a new branch 'ft/new-feature'

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/new-feature)
$ git add feature.txt

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/new-feature)
$ git commit -m'Implemented core functionality for new feature'
[ft/new-feature 013bf9a] Implemented core functionality for new feature
 2 files changed, 359 insertions(+)
 create mode 100644 feature.txt

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/new-feature)
$ git checkout main
error: Your local changes to the following files would be overwritten by checkout:
        ReadMe.md
Please commit your changes or stash them before you switch branches.
Aborting

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/new-feature)
$ git commit -m'Implemented core functionality for new feature'
On branch ft/new-feature
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   ReadMe.md

no changes added to commit (use "git add" and/or "git commit -a")

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/new-feature)
$ git add ReadMe.md

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/new-feature)
$ git commit -m'added read me as well'
[ft/new-feature dbd33a1] added read me as well
 1 file changed, 10 insertions(+)

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (ft/new-feature)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.       

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git add readme.txt

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git commit -m'Updated project readme'
[main cc6afb7] Updated project readme
 1 file changed, 0 insertions(+), 0 deletions(-)    
 create mode 100644 readme.txt

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git push origin ft/new-feature
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 16 threads
Compressing objects: 100% (6/6), done.
ExercisesPhase2/pull/new/ft/new-feature
remote:
To https://github.com/elyse-iradukunda/GitExercisesPhase2.git
 * [new branch]      ft/new-feature -> ft/new-feature

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git pull origin main
From https://github.com/elyse-iradukunda/GitExercisesPhase2
 * branch            main       -> FETCH_HEAD
Already up to date.

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git pull
fatal: unable to access 'https://github.com/elyse-iradukunda/GitExercisesPhase2.git/': Could not resolve host: github.com

user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main)
$ git pull origin main
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (1/1), 903 bytes | 451.00 KiB/s, done.
From https://github.com/elyse-iradukunda/GitExercisesPhase2
 * branch            main       -> FETCH_HEAD       
   99bf625..00304fc  main       -> origin/main      
hint: Waiting for your editor to close the file... Vim: Error reading input, exiting...
Vim: Finished.
error: there was a problem with the editor 'vi'     
Not committing merge; use 'git commit' to complete the merge.


user@Irael MINGW64 /d/Coding/GitExercisesPhase2 (main|MERGING)
$

```
 
```