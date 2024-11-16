- 👋 Hi, I’m @vijetasn
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
vijetasn/vijetasn is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/vv (master)
$ cd ..

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d (master)
$ cd ..

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /
$ cd ..

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /
$ cd d:

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d (master)
$ mkdir vv
mkdir: cannot create directory ‘vv’: File exists

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d (master)
$ mkdir v

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d (master)
$ cd v

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/v (master)
$ git init
Initialized empty Git repository in D:/v/.git/

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/v (master)
$ nano a.txt

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/v (master)
$

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/v (master)
$ git add .
warning: in the working copy of 'a.txt', LF will be replaced by CRLF the next time Git touches it

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/v (master)
$ git commit -m "c1"
[master (root-commit) 6a56d38] c1
 1 file changed, 1 insertion(+)
 create mode 100644 a.txt

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/v (master)
$ nano a.txt

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/v (master)
$ git add .
warning: in the working copy of 'a.txt', LF will be replaced by CRLF the next time Git touches it

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/v (master)
$ git commit -m "c2"
[master eb20e9e] c2
 1 file changed, 1 insertion(+), 1 deletion(-)

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/v (master)
$ git branch
* master

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/v (master)
$ git branch featurebranch

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/v (master)
$ git checkoutfeaturebranch
git: 'checkoutfeaturebranch' is not a git command. See 'git --help'.

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/v (master)
$ git checkout featurebranch
Switched to branch 'featurebranch'

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/v (featurebranch)
$ git log
commit eb20e9e333d59727526ae099cd357200cc1a2778 (HEAD -> featurebranch, master)
Author: vijetasn <vijetanarasanagi@gmail.com>
Date:   Sat Nov 16 10:57:24 2024 +0530

    c2

commit 6a56d3856e4aeda3d9f5ce8b88a0646149aa8b18
Author: vijetasn <vijetanarasanagi@gmail.com>
Date:   Sat Nov 16 10:57:07 2024 +0530

    c1

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/v (featurebranch)
$ nano b.txt

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/v (featurebranch)
$ git add .
warning: in the working copy of 'b.txt', LF will be replaced by CRLF the next time Git touches it

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/v (featurebranch)
$ git commit -m "c1"
[featurebranch 3eda2e1] c1
 1 file changed, 1 insertion(+)
 create mode 100644 b.txt

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/v (featurebranch)
$ nano e.txt

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/v (featurebranch)
$ git add .
warning: in the working copy of 'e.txt', LF will be replaced by CRLF the next time Git touches it

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/v (featurebranch)
$ git commit -m "c1"
[featurebranch 044f0e6] c1
 1 file changed, 1 insertion(+)
 create mode 100644 e.txt

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/v (featurebranch)
$ git log
commit 044f0e673b6d785065cae790dba253b09c8ecea1 (HEAD -> featurebranch)
Author: vijetasn <vijetanarasanagi@gmail.com>
Date:   Sat Nov 16 10:58:45 2024 +0530

    c1

commit 3eda2e14cb51ef8b2801172410d701c8860f57e6
Author: vijetasn <vijetanarasanagi@gmail.com>
Date:   Sat Nov 16 10:58:20 2024 +0530

    c1

commit eb20e9e333d59727526ae099cd357200cc1a2778 (master)
Author: vijetasn <vijetanarasanagi@gmail.com>
Date:   Sat Nov 16 10:57:24 2024 +0530

    c2

commit 6a56d3856e4aeda3d9f5ce8b88a0646149aa8b18
Author: vijetasn <vijetanarasanagi@gmail.com>
Date:   Sat Nov 16 10:57:07 2024 +0530

    c1

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/v (featurebranch)
$ git checkout master
Switched to branch 'master'

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/v (master)
$ git log
commit eb20e9e333d59727526ae099cd357200cc1a2778 (HEAD -> master)
Author: vijetasn <vijetanarasanagi@gmail.com>
Date:   Sat Nov 16 10:57:24 2024 +0530

    c2

commit 6a56d3856e4aeda3d9f5ce8b88a0646149aa8b18
Author: vijetasn <vijetanarasanagi@gmail.com>
Date:   Sat Nov 16 10:57:07 2024 +0530

    c1

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/v (master)
$ git cherry-pick  3eda2e14cb51ef8b2801172410d701c8860f57e6
[master 68b95be] c1
 Date: Sat Nov 16 10:58:20 2024 +0530
 1 file changed, 1 insertion(+)
 create mode 100644 b.txt

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/v (master)
$ ls
a.txt  b.txt

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/v (master)
$ git log
commit 68b95bef2dcb54c0835f8ae7e16e5f84c2b948d3 (HEAD -> master)
Author: vijetasn <vijetanarasanagi@gmail.com>
Date:   Sat Nov 16 10:58:20 2024 +0530

    c1

commit eb20e9e333d59727526ae099cd357200cc1a2778
Author: vijetasn <vijetanarasanagi@gmail.com>
Date:   Sat Nov 16 10:57:24 2024 +0530

    c2

commit 6a56d3856e4aeda3d9f5ce8b88a0646149aa8b18
Author: vijetasn <vijetanarasanagi@gmail.com>
Date:   Sat Nov 16 10:57:07 2024 +0530

    c1

