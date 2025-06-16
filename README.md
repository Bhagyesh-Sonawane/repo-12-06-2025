"#My Git Practice (Main Update)"
Bye

--------------------------------------------------------------------------------

Microsoft Windows [Version 10.0.22631.5413]
(c) Microsoft Corporation. All rights reserved.

C:\Users\SBUP\BS>git clone https://github.com/Bhagyesh-Sonawane/repo-12-06-2025.git
Cloning into 'repo-12-06-2025'...
warning: You appear to have cloned an empty repository.

C:\Users\SBUP\BS>cd repo-12-06-2025

C:\Users\SBUP\BS\repo-12-06-2025>echo "#My Git Practice"> README.md

C:\Users\SBUP\BS\repo-12-06-2025>git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\SBUP\BS\repo-12-06-2025>git add README.md

C:\Users\SBUP\BS\repo-12-06-2025>git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md


C:\Users\SBUP\BS\repo-12-06-2025>git commit -m"initial git commit"
[main (root-commit) 566cc6a] initial git commit
 Committer: unknown <SBUP@UGS-LB4-PC013.sbup.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 1 insertion(+)
 create mode 100644 README.md

C:\Users\SBUP\BS\repo-12-06-2025>git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

nothing to commit, working tree clean

C:\Users\SBUP\BS\repo-12-06-2025>git push origin main
info: please complete authentication in your browser...
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 248 bytes | 248.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Bhagyesh-Sonawane/repo-12-06-2025.git
 * [new branch]      main -> main

C:\Users\SBUP\BS\repo-12-06-2025>git branch feature-update

C:\Users\SBUP\BS\repo-12-06-2025>git switch feature-update
Switched to branch 'feature-update'

C:\Users\SBUP\BS\repo-12-06-2025>git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

C:\Users\SBUP\BS\repo-12-06-2025>git switch feature-update
Switched to branch 'feature-update'

C:\Users\SBUP\BS\repo-12-06-2025>git add .

C:\Users\SBUP\BS\repo-12-06-2025>git commit -m "feauture update commit"
[feature-update dfa167d] feauture update commit
 Committer: unknown <SBUP@UGS-LB4-PC013.sbup.local>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 1 insertion(+)

C:\Users\SBUP\BS\repo-12-06-2025>git push origin feature-update
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 286 bytes | 286.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'feature-update' on GitHub by visiting:
remote:      https://github.com/Bhagyesh-Sonawane/repo-12-06-2025/pull/new/feature-update
remote:
To https://github.com/Bhagyesh-Sonawane/repo-12-06-2025.git
 * [new branch]      feature-update -> feature-update

C:\Users\SBUP\BS\repo-12-06-2025>git status
On branch feature-update
nothing to commit, working tree clean

C:\Users\SBUP\BS\repo-12-06-2025>git merge origin/feature-update
Already up to date.

C:\Users\SBUP\BS\repo-12-06-2025>git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

C:\Users\SBUP\BS\repo-12-06-2025>git merge origin/feature-update
Updating 566cc6a..dfa167d
Fast-forward
 README.md | 1 +
 1 file changed, 1 insertion(+)

C:\Users\SBUP\BS\repo-12-06-2025>git push origin main
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Bhagyesh-Sonawane/repo-12-06-2025.git
   566cc6a..dfa167d  main -> main

C:\Users\SBUP\BS\repo-12-06-2025>