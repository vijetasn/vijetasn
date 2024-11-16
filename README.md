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


BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 ~ (b1)
$ cd ..

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /c/Users
$ cd ..

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /c
$ cd ..

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /
$ cd d:

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d (master)
$ mkdir vv

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d (master)
$ cd vv

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/vv (master)
$ git init
Initialized empty Git repository in D:/vv/.git/

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/vv (master)
$ nanoa
bash: nanoa: command not found

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/vv (master)
$ nano a.txt

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/vv (master)
$ git add .
warning: in the working copy of 'a.txt', LF will be replaced by CRLF the next time Git touches it

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/vv (master)
$ git commit -m "c 1"
[master (root-commit) 5f8a6d9] c 1
 1 file changed, 1 insertion(+)
 create mode 100644 a.txt

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/vv (master)
$ nano a.txt

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/vv (master)
$ git add .
warning: in the working copy of 'a.txt', LF will be replaced by CRLF the next time Git touches it

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/vv (master)
$ git commit -m "c 2"
[master ed58111] c 2
 1 file changed, 3 insertions(+), 1 deletion(-)

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/vv (master)
$ nano a.txt

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/vv (master)
$ git add .
warning: in the working copy of 'a.txt', LF will be replaced by CRLF the next time Git touches it

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/vv (master)
$ git commit -m "c 3"
[master 510784c] c 3
 1 file changed, 1 insertion(+)

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/vv (master)
$ git branch
* master

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/vv (master)
$ git branch featurebranch

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/vv (master)
$ git checkout featurebranch
Switched to branch 'featurebranch'

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/vv (featurebranch)
$ git log
commit 510784ca664cf4858fab1d24b68bcd8d6b2f7e58 (HEAD -> featurebranch, master)
Author: Prashantelagi <prashant.elagi123@gmail.com>
Date:   Sat Nov 16 10:37:01 2024 +0530

    c 3

commit ed58111d0f4dc9948be698625e86bbec013e5ae4
Author: Prashantelagi <prashant.elagi123@gmail.com>
Date:   Sat Nov 16 10:36:44 2024 +0530

    c 2

commit 5f8a6d95d3678b0350dd633194dad259bb54d48c
Author: Prashantelagi <prashant.elagi123@gmail.com>
Date:   Sat Nov 16 10:36:15 2024 +0530

    c 1

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/vv (featurebranch)
$ nano b.txt

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/vv (featurebranch)
$ git add .
warning: in the working copy of 'b.txt', LF will be replaced by CRLF the next time Git touches it

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/vv (featurebranch)
$ git commit -m "c-1"
[featurebranch 4b5e96a] c-1
 1 file changed, 2 insertions(+)
 create mode 100644 b.txt

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/vv (featurebranch)
$ nano c.txt

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/vv (featurebranch)
$ git add .
warning: in the working copy of 'c.txt', LF will be replaced by CRLF the next time Git touches it

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/vv (featurebranch)
$ git commit -m "c-c1"
[featurebranch a6bbb17] c-c1
 1 file changed, 1 insertion(+)
 create mode 100644 c.txt

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/vv (featurebranch)
$ git log
commit a6bbb1716c5e8121f9fe43703000bc60fbc1ebd7 (HEAD -> featurebranch)
Author: Prashantelagi <prashant.elagi123@gmail.com>
Date:   Sat Nov 16 10:41:13 2024 +0530

    c-c1

commit 4b5e96a4b29a43b882dabcd9be01a998f4fc9b54
Author: Prashantelagi <prashant.elagi123@gmail.com>
Date:   Sat Nov 16 10:40:43 2024 +0530

    c-1

commit 510784ca664cf4858fab1d24b68bcd8d6b2f7e58 (master)
Author: Prashantelagi <prashant.elagi123@gmail.com>
Date:   Sat Nov 16 10:37:01 2024 +0530

    c 3

commit ed58111d0f4dc9948be698625e86bbec013e5ae4
Author: Prashantelagi <prashant.elagi123@gmail.com>
Date:   Sat Nov 16 10:36:44 2024 +0530

    c 2

commit 5f8a6d95d3678b0350dd633194dad259bb54d48c
Author: Prashantelagi <prashant.elagi123@gmail.com>
Date:   Sat Nov 16 10:36:15 2024 +0530

    c 1

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/vv (featurebranch)
$ git checkout master
Switched to branch 'master'

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/vv (master)
$ git log
commit 510784ca664cf4858fab1d24b68bcd8d6b2f7e58 (HEAD -> master)
Author: Prashantelagi <prashant.elagi123@gmail.com>
Date:   Sat Nov 16 10:37:01 2024 +0530

    c 3

commit ed58111d0f4dc9948be698625e86bbec013e5ae4
Author: Prashantelagi <prashant.elagi123@gmail.com>
Date:   Sat Nov 16 10:36:44 2024 +0530

    c 2

commit 5f8a6d95d3678b0350dd633194dad259bb54d48c
Author: Prashantelagi <prashant.elagi123@gmail.com>
Date:   Sat Nov 16 10:36:15 2024 +0530

    c 1

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/vv (master)
$ git cherry-pick  4b5e96a4b29a43b882dabcd9be01a998f4fc9b54
[master 7233cf4] c-1
 Date: Sat Nov 16 10:40:43 2024 +0530
 1 file changed, 2 insertions(+)
 create mode 100644 b.txt

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/vv (master)
$ ls
a.txt  b.txt

BLDEA-CSE@DESKTOP-T8C9NH4 MINGW64 /d/vv (master)
$ git log
commit 7233cf4d8b74bcb34b32846b989b88ad5c0baf84 (HEAD -> master)
Author: Prashantelagi <prashant.elagi123@gmail.com>
Date:   Sat Nov 16 10:40:43 2024 +0530

    c-1

commit 510784ca664cf4858fab1d24b68bcd8d6b2f7e58
Author: Prashantelagi <prashant.elagi123@gmail.com>
Date:   Sat Nov 16 10:37:01 2024 +0530

    c 3

commit ed58111d0f4dc9948be698625e86bbec013e5ae4
Author: Prashantelagi <prashant.elagi123@gmail.com>
Date:   Sat Nov 16 10:36:44 2024 +0530

    c 2

commit 5f8a6d95d3678b0350dd633194dad259bb54d48c
Author: Prashantelagi <prashant.elagi123@gmail.com>
Date:   Sat Nov 16 10:36:15 2024 +0530

    c 1

