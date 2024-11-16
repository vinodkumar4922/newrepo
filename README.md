
BLDEA-CSE@DESKTOP-GT4620C MINGW64 /
$ cd ...
bash: cd: ...: No such file or directory

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /
$ cd ..

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /
$ cd ..

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /
$ cd d:

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d (master)
$ git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/etc/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
safe.directory=D:/
user.password=49222510@Vk.
user.email=mdhuzaif9036@gmail.com
user.name=nidhi
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.worktree=D:/
core.symlinks=false
core.ignorecase=true
remote.origin.url=https://github.com/Nidhi-05-code/Rajalaxmi.git
remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d (master)
$ git log --author
fatal: Option '--author' requires a value

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d (master)
$ git log
commit 315986ba3e4a44471fb60ee303f0fc6661568487 (HEAD -> master)
Author: nidhi <nidhichabbi06@gmail.com>
Date:   Mon Nov 11 15:37:29 2024 +0530

    edited
    :wq

    ;wq

commit 9f363f4b90f0f8fc3f8707d93d47bb569018ad08 (tag: show)
Author: nidhi <nidhichabbi06@gmail.com>
Date:   Mon Nov 11 15:13:04 2024 +0530

    added

commit 89bed85253e586f8d90e889fc25ca6faa3453e33
Author: unknown <mallikarjunpurani782@gmail.com>
Date:   Wed Nov 6 10:52:28 2024 +0530

    messege

commit 66c186d447e7d8391dd7756210209feda9a209d6 (origin/master, feature)
Author: unknown <mallikarjunpurani782@gmail.com>
Date:   Mon Nov 4 15:23:16 2024 +0530

    commit

commit 184f896524a78d7638354e76a925998c4e8615b3
Author: unknown <mallikarjunpurani782@gmail.com>
Date:   Mon Oct 28 15:46:43 2024 +0530

    added 1 line

commit bef1b86cb1a849cd0c21c6d45c0576b771bccc17
Author: Vinod <vinodjangamashetti8@gmail.com>
Date:   Sat Oct 5 09:48:58 2024 +0530

    first commit

commit ad32cb6e1c44d259b3c955d3ecc167bb1af1e749
Author: VinodJangamashetti <vinodjangamashetti8@gmail.com>
Date:   Mon Sep 30 15:18:50 2024 +0530

    commit1

commit fa1307ad1c5aa6a28415c85c56b80891bc75f09d (new)
Author: VinodJangamashetti <vinodjangamashetti8@gmail.com>
Date:   Mon Sep 23 10:01:24 2024 +0530

    description

commit 35a644a79fea0961e9a7de2fc7d1369f669a2909
Author: VinodJangamashetti <vinodjangamashetti8@gmail.com>
Date:   Mon Sep 23 09:56:32 2024 +0530

    experiment2

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d (master)
$ git log
commit 315986ba3e4a44471fb60ee303f0fc6661568487 (HEAD -> master)
Author: nidhi <nidhichabbi06@gmail.com>
Date:   Mon Nov 11 15:37:29 2024 +0530

    edited
    :wq

    ;wq

commit 9f363f4b90f0f8fc3f8707d93d47bb569018ad08 (tag: show)
Author: nidhi <nidhichabbi06@gmail.com>
Date:   Mon Nov 11 15:13:04 2024 +0530

    added

commit 89bed85253e586f8d90e889fc25ca6faa3453e33
Author: unknown <mallikarjunpurani782@gmail.com>
Date:   Wed Nov 6 10:52:28 2024 +0530

    messege

commit 66c186d447e7d8391dd7756210209feda9a209d6 (origin/master, feature)
Author: unknown <mallikarjunpurani782@gmail.com>
Date:   Mon Nov 4 15:23:16 2024 +0530

    commit

commit 184f896524a78d7638354e76a925998c4e8615b3
Author: unknown <mallikarjunpurani782@gmail.com>
Date:   Mon Oct 28 15:46:43 2024 +0530

    added 1 line

commit bef1b86cb1a849cd0c21c6d45c0576b771bccc17
Author: Vinod <vinodjangamashetti8@gmail.com>
Date:   Sat Oct 5 09:48:58 2024 +0530

    first commit

commit ad32cb6e1c44d259b3c955d3ecc167bb1af1e749
Author: VinodJangamashetti <vinodjangamashetti8@gmail.com>
Date:   Mon Sep 30 15:18:50 2024 +0530

    commit1

commit fa1307ad1c5aa6a28415c85c56b80891bc75f09d (new)
Author: VinodJangamashetti <vinodjangamashetti8@gmail.com>
Date:   Mon Sep 23 10:01:24 2024 +0530

    description

commit 35a644a79fea0961e9a7de2fc7d1369f669a2909
Author: VinodJangamashetti <vinodjangamashetti8@gmail.com>
Date:   Mon Sep 23 09:56:32 2024 +0530

    experiment2

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d (master)
$ git show  9f363f4b90f0f8fc3f8707d93d47bb569018ad08
commit 9f363f4b90f0f8fc3f8707d93d47bb569018ad08 (tag: show)
Author: nidhi <nidhichabbi06@gmail.com>
Date:   Mon Nov 11 15:13:04 2024 +0530

    added

diff --git a/nidhii/027.txt b/nidhii/027.txt
new file mode 100644
index 0000000..f91506a
--- /dev/null
+++ b/nidhii/027.txt
@@ -0,0 +1,4 @@
+#include<stdio.h>
+printf(BLDEACET)
+
+
diff --git a/nidhii/tmp.txt b/nidhii/tmp.txt
index b2c3b41..2e13015 100644
--- a/nidhii/tmp.txt
+++ b/nidhii/tmp.txt
@@ -1,3 +1,4 @@
 nidhiiii
 (data science)
-s
+Rajalaxmi
+

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d (master)
$ git show  35a644a79fea0961e9a7de2fc7d1369f669a2909
commit 35a644a79fea0961e9a7de2fc7d1369f669a2909
Author: VinodJangamashetti <vinodjangamashetti8@gmail.com>
Date:   Mon Sep 23 09:56:32 2024 +0530

    experiment2

diff --git a/pgm/p2.txt b/pgm/p2.txt
new file mode 100644
index 0000000..d6ec0de
--- /dev/null
+++ b/pgm/p2.txt
@@ -0,0 +1,3 @@
+Hi Hello
+Good Morning
+
diff --git a/pgm/two.txt b/pgm/two.txt
new file mode 100644
index 0000000..4bc288f
--- /dev/null
+++ b/pgm/two.txt
@@ -0,0 +1 @@
+rachana

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d (master)
$ +Good Morningmkdir
bash: +Good: command not found

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d (master)
$




BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d (master)
$


BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d (master)
$ mkdir g1

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d (master)
$ cd g1

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/g1 (master)
$ git log -5
commit 315986ba3e4a44471fb60ee303f0fc6661568487 (HEAD -> master)
Author: nidhi <nidhichabbi06@gmail.com>
Date:   Mon Nov 11 15:37:29 2024 +0530

    edited
    :wq

    ;wq

commit 9f363f4b90f0f8fc3f8707d93d47bb569018ad08 (tag: show)
Author: nidhi <nidhichabbi06@gmail.com>
Date:   Mon Nov 11 15:13:04 2024 +0530

    added

commit 89bed85253e586f8d90e889fc25ca6faa3453e33
Author: unknown <mallikarjunpurani782@gmail.com>
Date:   Wed Nov 6 10:52:28 2024 +0530

    messege

commit 66c186d447e7d8391dd7756210209feda9a209d6 (origin/master, feature)
Author: unknown <mallikarjunpurani782@gmail.com>
Date:   Mon Nov 4 15:23:16 2024 +0530

    commit

commit 184f896524a78d7638354e76a925998c4e8615b3
Author: unknown <mallikarjunpurani782@gmail.com>
Date:   Mon Oct 28 15:46:43 2024 +0530

    added 1 line

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/g1 (master)
$ git log +5
fatal: ambiguous argument '+5': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/g1 (master)
$ git log +5 SHOW
fatal: ambiguous argument '+5': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/g1 (master)
$ git log +5 show
fatal: ambiguous argument '+5': unknown revision or path not in the working tree.
Use '--' to separate paths from revisions, like this:
'git <command> [<revision>...] -- [<file>...]'

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/g1 (master)
$ git show -5 show
commit 9f363f4b90f0f8fc3f8707d93d47bb569018ad08 (tag: show)
Author: nidhi <nidhichabbi06@gmail.com>
Date:   Mon Nov 11 15:13:04 2024 +0530

    added

diff --git a/nidhii/027.txt b/nidhii/027.txt
new file mode 100644
index 0000000..f91506a
--- /dev/null
+++ b/nidhii/027.txt
@@ -0,0 +1,4 @@
+#include<stdio.h>
+printf(BLDEACET)
+
+
diff --git a/nidhii/tmp.txt b/nidhii/tmp.txt
index b2c3b41..2e13015 100644
--- a/nidhii/tmp.txt
+++ b/nidhii/tmp.txt
@@ -1,3 +1,4 @@
 nidhiiii
 (data science)
-s
+Rajalaxmi
+

commit 89bed85253e586f8d90e889fc25ca6faa3453e33
Author: unknown <mallikarjunpurani782@gmail.com>
Date:   Wed Nov 6 10:52:28 2024 +0530

    messege

diff --git a/exp12/12nano.txt b/exp12/12nano.txt
new file mode 100644
index 0000000..d0952db
--- /dev/null
+++ b/exp12/12nano.txt
@@ -0,0 +1,3 @@
+hiiii
+helloooooooo
+byeeee

commit 66c186d447e7d8391dd7756210209feda9a209d6 (origin/master, feature)
Author: unknown <mallikarjunpurani782@gmail.com>
Date:   Mon Nov 4 15:23:16 2024 +0530

    commit

diff --git a/nidhii/tmp.txt b/nidhii/tmp.txt
index 561239a..b2c3b41 100644
--- a/nidhii/tmp.txt
+++ b/nidhii/tmp.txt
@@ -1 +1,3 @@
 nidhiiii
+(data science)
+s

commit 184f896524a78d7638354e76a925998c4e8615b3
Author: unknown <mallikarjunpurani782@gmail.com>
Date:   Mon Oct 28 15:46:43 2024 +0530

    added 1 line

diff --git a/nidhii/c b/nidhii/c
new file mode 100644
index 0000000..be49748
--- /dev/null
+++ b/nidhii/c
@@ -0,0 +1,6 @@
+#include<stdio.h>
+void main()
+printf("This is Rajalaxmi")
+
+
+
diff --git a/nidhii/tmp.txt b/nidhii/tmp.txt
new file mode 100644
index 0000000..561239a
--- /dev/null
+++ b/nidhii/tmp.txt
@@ -0,0 +1 @@
+nidhiiii

commit bef1b86cb1a849cd0c21c6d45c0576b771bccc17
Author: Vinod <vinodjangamashetti8@gmail.com>
Date:   Sat Oct 5 09:48:58 2024 +0530

    first commit

diff --git a/gitlabds027/prog3.c b/gitlabds027/prog3.c
new file mode 100644
index 0000000..4353002
--- /dev/null
+++ b/gitlabds027/prog3.c
@@ -0,0 +1,5 @@
+#include<stdio.h>
+void main()
+{
+printf("Data science");
+}

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/g1 (master)
$ git log -5 show
commit 9f363f4b90f0f8fc3f8707d93d47bb569018ad08 (tag: show)
Author: nidhi <nidhichabbi06@gmail.com>
Date:   Mon Nov 11 15:13:04 2024 +0530

    added

commit 89bed85253e586f8d90e889fc25ca6faa3453e33
Author: unknown <mallikarjunpurani782@gmail.com>
Date:   Wed Nov 6 10:52:28 2024 +0530

    messege

commit 66c186d447e7d8391dd7756210209feda9a209d6 (origin/master, feature)
Author: unknown <mallikarjunpurani782@gmail.com>
Date:   Mon Nov 4 15:23:16 2024 +0530

    commit

commit 184f896524a78d7638354e76a925998c4e8615b3
Author: unknown <mallikarjunpurani782@gmail.com>
Date:   Mon Oct 28 15:46:43 2024 +0530

    added 1 line

commit bef1b86cb1a849cd0c21c6d45c0576b771bccc17
Author: Vinod <vinodjangamashetti8@gmail.com>
Date:   Sat Oct 5 09:48:58 2024 +0530

    first commit

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/g1 (master)
$ git revert 9f363f4b90f0f8fc3f8707d93d47bb569018ad08
Auto-merging nidhii/tmp.txt
CONFLICT (content): Merge conflict in nidhii/tmp.txt
error: could not revert 9f363f4... added
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git revert --continue".
hint: You can instead skip this commit with "git revert --skip".
hint: To abort and get back to the state before "git revert",
hint: run "git revert --abort".

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/g1 (master|REVERTING)
$ git revert --continue
error: Committing is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: Exiting because of an unresolved conflict.
U       nidhii/tmp.txt

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/g1 (master|REVERTING)
$ git revert 9f363f4b90f0f8fc3f8707d93d47bb569018ad08
error: Reverting is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: revert failed

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/g1 (master|REVERTING)
$ git revert 66c186d447e7d8391dd7756210209feda9a209d6
error: Reverting is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: revert failed

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/g1 (master|REVERTING)
$

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/g1 (master|REVERTING)
$

BLDEA-CSE@DESKTOP-GT4620C MINGW64 /d/g1 (master|REVERTING)
$
