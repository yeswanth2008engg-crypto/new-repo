creating a new github repo from vs code
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To github.com:yeswanth2008engg-crypto/new-repo.git
 * [new branch]      master -> master
PS C:\Users\yeswa\OneDrive\Desktop\MRM taskphase\task 3\new repo> git push
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\yeswa\OneDrive\Desktop\MRM taskphase\task 3\new repo> git push -u origin master
branch 'master' set up to track 'origin/master'.
Everything up-to-date
PS C:\Users\yeswa\OneDrive\Desktop\MRM taskphase\task 3\new repo> git branch
* master
PS C:\Users\yeswa\OneDrive\Desktop\MRM taskphase\task 3\new repo> git checkout -b feature
Switched to a new branch 'feature'
PS C:\Users\yeswa\OneDrive\Desktop\MRM taskphase\task 3\new repo> git branch
* feature
  master
PS C:\Users\yeswa\OneDrive\Desktop\MRM taskphase\task 3\new repo> git checkout
PS C:\Users\yeswa\OneDrive\Desktop\MRM taskphase\task 3\new repo> git branch
* feature
  master
PS C:\Users\yeswa\OneDrive\Desktop\MRM taskphase\task 3\new repo> git checkout master 
Switched to branch 'master'
Your branch is up to date with 'origin/master'.
PS C:\Users\yeswa\OneDrive\Desktop\MRM taskphase\task 3\new repo> git branch
  feature
* master
PS C:\Users\yeswa\OneDrive\Desktop\MRM taskphase\task 3\new repo> git checkout
Your branch is up to date with 'origin/master'.
PS C:\Users\yeswa\OneDrive\Desktop\MRM taskphase\task 3\new repo> git checkout feature
Switched to branch 'feature'
PS C:\Users\yeswa\OneDrive\Desktop\MRM taskphase\task 3\new repo> git status
On branch feature
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   readme.md

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Users\yeswa\OneDrive\Desktop\MRM taskphase\task 3\new repo> git add .
PS C:\Users\yeswa\OneDrive\Desktop\MRM taskphase\task 3\new repo> git commit -m "just_pass"
[feature 1dcf129] just_pass
 1 file changed, 2 insertions(+), 1 deletion(-)
PS C:\Users\yeswa\OneDrive\Desktop\MRM taskphase\task 3\new repo> git push
fatal: The current branch feature has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin feature

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\yeswa\OneDrive\Desktop\MRM taskphase\task 3\new repo> git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.
PS C:\Users\yeswa\OneDrive\Desktop\MRM taskphase\task 3\new repo> git checkout feature
Switched to branch 'feature'
PS C:\Users\yeswa\OneDrive\Desktop\MRM taskphase\task 3\new repo> git diff feature
PS C:\Users\yeswa\OneDrive\Desktop\MRM taskphase\task 3\new repo> 
PS C:\Users\yeswa\OneDrive\Desktop\MRM taskphase\task 3\new repo> git diff feature
PS C:\Users\yeswa\OneDrive\Desktop\MRM taskphase\task 3\new repo> git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.
PS C:\Users\yeswa\OneDrive\Desktop\MRM taskphase\task 3\new repo> git diff feature
diff --git a/readme.md b/readme.md
index efc10c0..67e5b55 100644
--- a/readme.md
+++ b/readme.md
@@ -1,2 +1 @@
-creating a new github repo from vs code
-lets change some words to check if tis modified in actualgithub repo
\ No newline at end of file
+creating a new github repo from vs code
\ No newline at end of file
PS C:\Users\yeswa\OneDrive\Desktop\MRM taskphase\task 3\new repo> git checkout master
Already on 'master'
Your branch is up to date with 'origin/master'.
PS C:\Users\yeswa\OneDrive\Desktop\MRM taskphase\task 3\new repo> git checkout feature
Switched to branch 'feature'
PS C:\Users\yeswa\OneDrive\Desktop\MRM taskphase\task 3\new repo> git push
fatal: The current branch feature has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin feature

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\yeswa\OneDrive\Desktop\MRM taskphase\task 3\new repo> git push origin master
Everything up-to-date
PS C:\Users\yeswa\OneDrive\Desktop\MRM taskphase\task 3\new repo> git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.
PS C:\Users\yeswa\OneDrive\Desktop\MRM taskphase\task 3\new repo> git 
 *  History restored 
 here i made some changes in the feature branch

