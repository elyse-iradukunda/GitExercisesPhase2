### My answers to git exercises

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
```
