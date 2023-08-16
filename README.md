# Gym_Git_Exercise_Solutions

## Bundle I

### Excercise one

```bash
    1  e:
    2  cd ..
    3  cd ..
    4  cd ..
    5  cd e
    6  /c
    7  cd thegym/
    8  cd week2
    9  cd pro
   10  cd project/
   11  nanp service.html
   12  nano service.html
   13  git add .
   14  git commit -m "service redesign"
   15  git push
   16  git push --set-upstream origin ft/service-redesign
   17  git status
   18  history
   19  clear
   20  git rebase main
   21  nano README.md
   22  git rebase --continue
   23  git add .
   24  git commit --amend --no-edit
   25  git push
   26  git push -f
   27  ls
   28  e:
   29  cd e
   30  cd ..
   31  e:
   32  cd ..
   33  cd ..
   34  cd e
   35  cd thegym/
   36  cd ojembaIntern/
   37  cd Gym_Git_Exercise_Solutions/
   38  cd project/
   39  ls
   40  dir
   41  touch index.html
   42  ls
   43  touch index.css
   44  rm index.css index.js
   45  mv -r index.css index.js
   46  mv index.css index.js
   47  ren index.css indexone.js
   48  ls
   49  touch index.css
   50  ren index.css indexone.js
   51  mv index.css index.js
   52  ls
   53  git add .
   54  git commit-m "initial commit"
   55  git commit -m "initial commit"
   56  git push
   57  git history
   58  type history
   59  rm index.css index.js


```

```bash
   61  ls
   62  cd ..
   63  nano README.md
   64  git add .
   65  git status
   66  git commit -m "first commit"
   67  git push
   68  git checkout -b dev
   69  git checkout -b test
   70  git checkout dev
   71  git branch -d test
   72  history
```

## Excercise II

```bash
karer@DESKTOP-ALDB193 MINGW64 /e/thegym/ojembaIntern/Gym_Git_Exercise_Solutions (main)
$ git stash
Saved working directory and index state WIP on main: 51f0c3e first commit

karer@DESKTOP-ALDB193 MINGW64 /e/thegym/ojembaIntern/Gym_Git_Exercise_Solutions (main)
$ touch project/abouttwo.html

karer@DESKTOP-ALDB193 MINGW64 /e/thegym/ojembaIntern/Gym_Git_Exercise_Solutions (main)
$ git stash
No local changes to save

karer@DESKTOP-ALDB193 MINGW64 /e/thegym/ojembaIntern/Gym_Git_Exercise_Solutions (main)
$ touch project/yeam.html

karer@DESKTOP-ALDB193 MINGW64 /e/thegym/ojembaIntern/Gym_Git_Exercise_Solutions (main)
$ ls
LICENSE  README.md  index.html  project/

karer@DESKTOP-ALDB193 MINGW64 /e/thegym/ojembaIntern/Gym_Git_Exercise_Solutions (main)
$ rm index.html

karer@DESKTOP-ALDB193 MINGW64 /e/thegym/ojembaIntern/Gym_Git_Exercise_Solutions (main)
$ ls
LICENSE  README.md  project/

karer@DESKTOP-ALDB193 MINGW64 /e/thegym/ojembaIntern/Gym_Git_Exercise_Solutions (main)
$ cd project/

karer@DESKTOP-ALDB193 MINGW64 /e/thegym/ojembaIntern/Gym_Git_Exercise_Solutions/project (main)
$ ls
abouttwo.html  home.html  index.html  yeam.html

karer@DESKTOP-ALDB193 MINGW64 /e/thegym/ojembaIntern/Gym_Git_Exercise_Solutions/project (main)
$ rm abouttwo.html index.html yeam.html

karer@DESKTOP-ALDB193 MINGW64 /e/thegym/ojembaIntern/Gym_Git_Exercise_Solutions/project (main)
$ ls
home.html

karer@DESKTOP-ALDB193 MINGW64 /e/thegym/ojembaIntern/Gym_Git_Exercise_Solutions/project (main)
$ cd ..

karer@DESKTOP-ALDB193 MINGW64 /e/thegym/ojembaIntern/Gym_Git_Exercise_Solutions (main)
$ git add .

karer@DESKTOP-ALDB193 MINGW64 /e/thegym/ojembaIntern/Gym_Git_Exercise_Solutions (main)
$ git commit -m "add home"
[main 233cf6a] add home
 2 files changed, 0 insertions(+), 0 deletions(-)
 rename index.html => project/home.html (100%)
 delete mode 100644 project/index.html

karer@DESKTOP-ALDB193 MINGW64 /e/thegym/ojembaIntern/Gym_Git_Exercise_Solutions (main)
$ git stash save "stashing home"
No local changes to save

karer@DESKTOP-ALDB193 MINGW64 /e/thegym/ojembaIntern/Gym_Git_Exercise_Solutions (main)
$ touch project/about.html

karer@DESKTOP-ALDB193 MINGW64 /e/thegym/ojembaIntern/Gym_Git_Exercise_Solutions (main)
$ git add .

karer@DESKTOP-ALDB193 MINGW64 /e/thegym/ojembaIntern/Gym_Git_Exercise_Solutions (main)
$ git stash save "stashing about"
Saved working directory and index state On main: stashing about

karer@DESKTOP-ALDB193 MINGW64 /e/thegym/ojembaIntern/Gym_Git_Exercise_Solutions (main)
$ touch project/team.html

karer@DESKTOP-ALDB193 MINGW64 /e/thegym/ojembaIntern/Gym_Git_Exercise_Solutions (main)
$ git add .

karer@DESKTOP-ALDB193 MINGW64 /e/thegym/ojembaIntern/Gym_Git_Exercise_Solutions (main)
$ git stash save "stashing team"
Saved working directory and index state On main: stashing team

karer@DESKTOP-ALDB193 MINGW64 /e/thegym/ojembaIntern/Gym_Git_Exercise_Solutions (main)
$ git stash pop stash@{1}
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   project/about.html

Dropped stash@{1} (ff4bcc27f31da824f385dd061904cc673a1313e3)

karer@DESKTOP-ALDB193 MINGW64 /e/thegym/ojembaIntern/Gym_Git_Exercise_Solutions (main)
$ git stash pop stash@{0}
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   project/about.html
        new file:   project/team.html

Dropped stash@{0} (66b5e3ec1362eaf0452fe090070599c4ca8caf90)

karer@DESKTOP-ALDB193 MINGW64 /e/thegym/ojembaIntern/Gym_Git_Exercise_Solutions (main)
$ git add .

karer@DESKTOP-ALDB193 MINGW64 /e/thegym/ojembaIntern/Gym_Git_Exercise_Solutions (main)
$ git commit -m "add home and about"
[main 7b95f7b] add home and about
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 project/about.html
 create mode 100644 project/team.html

karer@DESKTOP-ALDB193 MINGW64 /e/thegym/ojembaIntern/Gym_Git_Exercise_Solutions (main)
$ git push
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (6/6), 558 bytes | 558.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/kareraolivier/Gym_Git_Exercise_Solutions.git
   51f0c3e..7b95f7b  main -> main

karer@DESKTOP-ALDB193 MINGW64 /e/thegym/ojembaIntern/Gym_Git_Exercise_Solutions (main)
$ git stash pop stash@{1}
fatal: log for 'stash' only has 1 entries

karer@DESKTOP-ALDB193 MINGW64 /e/thegym/ojembaIntern/Gym_Git_Exercise_Solutions (main)
$ git reset HEAD

karer@DESKTOP-ALDB193 MINGW64 /e/thegym/ojembaIntern/Gym_Git_Exercise_Solutions (main)
$ git checkout .
Updated 0 paths from the index

karer@DESKTOP-ALDB193 MINGW64 /e/thegym/ojembaIntern/Gym_Git_Exercise_Solutions (main)
$

..............................................................................


C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>git branch
* main

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>git checkout dev
Switched to a new branch 'dev'
A       about.html
branch 'dev' set up to track 'origin/dev'.

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>git stash
Saved working directory and index state WIP on dev: a716e0b Merge branch 'main' into dev

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>git add .

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>git checkout dev
Already on 'dev'
Your branch is up to date with 'origin/dev'.

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>git branch
* dev
  main

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>touch home.html

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>git add .

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>git stash
Saved working directory and index state WIP on dev: a716e0b Merge branch 'main' into dev

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>touch about.html

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>git add .

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>git stash
Saved working directory and index state WIP on dev: a716e0b Merge branch 'main' into dev

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>touch about.html

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>git add .

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>rm about.html

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>ls
LICENSE  README.md  project

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>touch team.html

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>git add .

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>git stash
Saved working directory and index state WIP on dev: a716e0b Merge branch 'main' into dev

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>git stash list
stash@{0}: WIP on dev: a716e0b Merge branch 'main' into dev
stash@{1}: WIP on dev: a716e0b Merge branch 'main' into dev
stash@{2}: WIP on dev: a716e0b Merge branch 'main' into dev
stash@{3}: WIP on dev: a716e0b Merge branch 'main' into dev
stash@{4}: WIP on main: 8767b5d git excercise

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>ls
LICENSE  README.md  project

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>git stash pop stash@{1}
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html

Dropped stash@{1} (9763c94b38f9469c156fd37749da67fc076a1ec7)

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>git stash pop stash@{1}
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html

Dropped stash@{1} (0459235bc15cde828fb6361031589a5364b580a0)

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>git add .

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>git status
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html


C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions> git commit -m "home & about pages"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'The Gym@DESKTOP-PN6DN2V.(none)')

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>git config --global user.email "kareraolivie
r@gmail.com"

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>git config --global user.name "kareraolivier
"

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions> git commit -m "home & about pages"
[dev 5e64794] home & about pages
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 about.html
 create mode 100644 home.html

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>git push
info: please complete authentication in your browser...
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 387 bytes | 387.00 KiB/s, done.
Total 3 (delta 0), reused 1 (delta 0), pack-reused 0
To https://github.com/kareraolivier/Gym_Git_Exercise_Solutions.git
   a716e0b..5e64794  dev -> dev

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>git status
On branch dev
Your branch is up to date with 'origin/dev'.

nothing to commit, working tree clean

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>nano README.md

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>nano README.md

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>git stash pop
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Dropped refs/stash@{0} (fd72266075329314f745c4eaa78ca774220230d6)

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>git git status
git: 'git' is not a git command. See 'git --help'.

The most similar command is
        init

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>git status
On branch dev
Your branch is up to date with 'origin/dev'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html


C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>git reset --hard
HEAD is now at 5e64794 home & about pages

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>git status
On branch dev
Your branch is up to date with 'origin/dev'.

nothing to commit, working tree clean

C:\Users\The Gym\Desktop\TheGym\Gym_Git_Exercise_Solutions>



```

## Bundle II

### Excercise one

```bash

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (main)
$ git checkout ft/bundle-2
Switched to a new branch 'ft/bundle-2'
branch 'ft/bundle-2' set up to track 'origin/ft/bundle-2'.

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/bundle-2)
$ nano readme


Use "fg" to return to nano.

[1]+  Stopped                 nano readme

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/bundle-2)
$ nano README.md

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/bundle-2)
$ git merge main
Merge made by the 'ort' strategy.
 README.md | 202 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 home.html |   0
 2 files changed, 202 insertions(+)
 create mode 100644 home.html

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/bundle-2)
The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/bundle-2)
$ nano README.md

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/bundle-2)
$ torch service.html
bash: torch: command not found

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/bundle-2)
$ tourch service.html
bash: tourch: command not found

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/bundle-2)
$ touch service.html

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/bundle-2)
$ ls
LICENSE  README.md  about.html  home.html  project/  service.html  services.html

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/bundle-2)
$ git add .

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/bundle-2)
$ git commit -m "service"
[ft/bundle-2 35b0426] service
 2 files changed, 46 insertions(+)
 create mode 100644 service.html

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/bundle-2)
$ git push
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 932 bytes | 932.00 KiB/s, done.
Total 5 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 2 local objects.
To https://github.com/kareraolivier/Gym_Git_Exercise_Solutions.git
   7bd1c72..35b0426  ft/bundle-2 -> ft/bundle-2

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/bundle-2)
$ nano README.md



```

### Excercise two

```bash

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/bundle-2)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (main)
$ git pull
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (1/1), 621 bytes | 51.00 KiB/s, done.
From https://github.com/kareraolivier/Gym_Git_Exercise_Solutions
   f14595e..30b2070  main       -> origin/main
Updating f14595e..30b2070
Fast-forward
 README.md                          | 87 ++++++++++++++++++++++++++++++++++++++
 project/{ => stash}/home.html      |  0
 project/team.html                  |  0
 project/about.html => service.html |  0
 services.html                      |  3 ++
 5 files changed, 90 insertions(+)
 rename project/{ => stash}/home.html (100%)
 delete mode 100644 project/team.html
 rename project/about.html => service.html (100%)
 create mode 100644 services.html

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (main)
$ git checkout -b ft/service-redesign
Switched to a new branch 'ft/service-redesign'

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/service-redesign)
$ nano service.html

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/service-redesign)
$ git add .
warning: in the working copy of 'service.html', LF will be replaced by CRLF the next time Git touches i
t

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/service-redesign)
$ git commit -m "services change"
[ft/service-redesign f7b6b8a] services change
 1 file changed, 1 insertion(+)

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/service-redesign)
$ git push
fatal: The current branch ft/service-redesign has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/service-redesign

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/service-redesign)
$   git push --set-upstream origin ft/service-redesign
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 269 bytes | 269.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/kareraolivier/Gym_Git_Exercise_Solutions/pull/new/ft/service-redesign
remote:
To https://github.com/kareraolivier/Gym_Git_Exercise_Solutions.git
 * [new branch]      ft/service-redesign -> ft/service-redesign
branch 'ft/service-redesign' set up to track 'origin/ft/service-redesign'.

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (main)
$ nano service.html

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (main)
$ git add .
warning: in the working copy of 'service.html', LF will be replaced by CRLF the next time Git touches i
t

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (main)
$ git commit -m "service"
[main 21a26ae] service
 1 file changed, 1 insertion(+)

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 267 bytes | 267.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: Bypassed rule violations for refs/heads/main:
remote:
remote: - Changes must be made through a pull request.
remote:
To https://github.com/kareraolivier/Gym_Git_Exercise_Solutions.git
   30b2070..21a26ae  main -> main

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (main)
$ git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'
Your branch is up to date with 'origin/ft/service-redesign'.

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/service-redesign)
$ git diff

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/service-redesign)
$ git merge main
Auto-merging service.html
CONFLICT (content): Merge conflict in service.html
Automatic merge failed; fix conflicts and then commit the result.

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/service-redesign|MERGING)
$ git diff ft/service-redesign..main
diff --git a/service.html b/service.html
index 4a7db5e..9fc2ab3 100644
--- a/service.html
+++ b/service.html
@@ -1 +1 @@
-my services
+sadfsetrrewtw

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/service-redesign|MERGING)
$ git diff main...ft/service-redesign
diff --git a/service.html b/service.html
index e69de29..4a7db5e 100644
--- a/service.html
+++ b/service.html
@@ -0,0 +1 @@
+my services

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/service-redesign|MERGING)
$ git merge main
error: Merging is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: Exiting because of an unresolved conflict.

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/service-redesign|MERGING)
$ git status
On branch ft/service-redesign
Your branch is up to date with 'origin/ft/service-redesign'.

You have unmerged paths.
  (fix conflicts and run "git commit")
  (use "git merge --abort" to abort the merge)

Unmerged paths:
  (use "git add <file>..." to mark resolution)
        both modified:   service.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        mintty.2023-07-28_17-54-22.png

no changes added to commit (use "git add" and/or "git commit -a")

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/service-redesign|MERGING)
$ git pull origin main
error: Pulling is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: Exiting because of an unresolved conflict.

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/service-redesign|MERGING)
$ git merge --abort

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/service-redesign)
$ git pull origin main
From https://github.com/kareraolivier/Gym_Git_Exercise_Solutions
 * branch            main       -> FETCH_HEAD
Auto-merging service.html
CONFLICT (content): Merge conflict in service.html
Automatic merge failed; fix conflicts and then commit the result.

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/service-redesign|MERGING)
$ git merge main
error: Merging is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: Exiting because of an unresolved conflict.

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/service-redesign|MERGING)
$ git diff main...ft/service-redesign
diff --git a/service.html b/service.html
index e69de29..4a7db5e 100644
--- a/service.html
+++ b/service.html
@@ -0,0 +1 @@
+my services

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/service-redesign|MERGING)
$ git add .

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/service-redesign|MERGING)
$ git commit -m "changes"
[ft/service-redesign d5ae694] changes

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/service-redesign)
$ git merge main
Already up to date.

The Gym@DESKTOP-PN6DN2V

```

## Bundle vI

### Excercise one

```bash

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (main)
$ git branch
  dev
  ft/bundle-2
  ft/contact-page
  ft/faq-page
  ft/home-page-redesign
  ft/service-redesign
  ft/team-page
* main

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (main)
$ git remote add git-copy https://github.com/kareraolivier/git-copy.git

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (main)
$ git add .

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (main)
$ git commit -m "addidng repo"
On branch main
Your branch is behind 'origin/main' by 6 commits, and can be fast-forwarded.
  (use "git pull" to update your local branch)

nothing to commit, working tree clean

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (main)
$ git pull
Updating 21a26ae..665e0bf
Fast-forward
 README.md     | 209 ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 readme.save   |   1 +
 service.html  |   1 +
 services.html |   3 -
 team.html     |   1 +
 5 files changed, 212 insertions(+), 3 deletions(-)
 create mode 100644 readme.save
 delete mode 100644 services.html
 create mode 100644 team.html

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (main)
$ git commit -m "addidng repo"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (main)
$ git push
Everything up-to-date

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (main)
$ cd ..

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym
$ git remote add git-copy https://github.com/kareraolivier/git-copy.git
fatal: not a git repository (or any of the parent directories): .git

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym
$ git remote add git-copy https://github.com/kareraolivier/git-copy
fatal: not a git repository (or any of the parent directories): .git

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym
$ cd Gym_Git_Exercise_Solutions/

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (main)
$ git remote add git-copy https://github.com/kareraolivier/Gym_Git_Exercise_Solutions.git
error: remote git-copy already exists.

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (main)
$ code .

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (main)

```

### Excercise two

```bash

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (main)
$ git checkout -b ft/footer
Switched to a new branch 'ft/footer'

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/footer)
$ ls
LICENSE  README.md  about.html  home.html  project/  readme.save  service.html  team.html

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/footer)
$ nano home.html

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/footer)
$ nano about.html

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/footer)
$ git add .
warning: in the working copy of 'about.html', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'home.html', LF will be replaced by CRLF the next time Git touches it

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/footer)
$ git commit -m "changes"
[ft/footer 2fe0a24] changes
 2 files changed, 2 insertions(+)

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/footer)
$ nano home.html

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/footer)
$ nano about.html

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/footer)
$ git add .
warning: in the working copy of 'about.html', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'home.html', LF will be replaced by CRLF the next time Git touches it

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/footer)
$ git commit -m "changes 2"
[ft/footer c2dbf19] changes 2
 2 files changed, 4 insertions(+)

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/footer)
$ git push
fatal: The current branch ft/footer has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/footer

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/footer)
$ git push --set-upstream origin ft/footer
Enumerating objects: 11, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (8/8), 630 bytes | 315.00 KiB/s, done.
Total 8 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/footer' on GitHub by visiting:
remote:      https://github.com/kareraolivier/Gym_Git_Exercise_Solutions/pull/new/ft/footer
remote:
To https://github.com/kareraolivier/Gym_Git_Exercise_Solutions.git
 * [new branch]      ft/footer -> ft/footer
branch 'ft/footer' set up to track 'origin/ft/footer'.

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/footer)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.


The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (main)
$ git checkout -b ft/squashing
Switched to a new branch 'ft/squashing'

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/squashing)
$ git merge --squash ft/footer
Updating 665e0bf..c2dbf19
Fast-forward
Squash commit -- not updating HEAD
 about.html | 3 +++
 home.html  | 3 +++
 2 files changed, 6 insertions(+)

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/squashing)
$ git commit -m "changes"
[ft/squashing 547cd25] changes
 2 files changed, 6 insertions(+)

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/squashing)
$ git push --set-upstream origin ft/squashing
Enumerating objects: 7, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 336 bytes | 168.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/squashing' on GitHub by visiting:
remote:      https://github.com/kareraolivier/Gym_Git_Exercise_Solutions/pull/new/ft/squashing
remote:
To https://github.com/kareraolivier/Gym_Git_Exercise_Solutions.git
 * [new branch]      ft/squashing -> ft/squashing
branch 'ft/squashing' set up to track 'origin/ft/squashing'.

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/squashing)

```

## Bundle V

### Excercise one

```bash
The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/squashing)
$ cd ..

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym
$ git clone https://github.com/kareraolivier/git-cafe-exercise.git
Cloning into 'git-cafe-exercise'...
remote: Enumerating objects: 107, done.
remote: Counting objects: 100% (14/14), done.
remote: Compressing objects: 100% (10/10), done.
remote: Total 107 (delta 5), reused 4 (delta 4), pack-reused 93Receiving objects:  97% (104/107), 1.75
Receiving objects: 100% (107/107), 1.95 MiB | 787.00 KiB/s, done.

Resolving deltas: 100% (5/5), done.

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym
$ cd git-cafe-exercise/

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/git-cafe-exercise (main)
$ code .

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/git-cafe-exercise (main)
$ git add .

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/git-cafe-exercise (main)
$ git commit -m "Updated"
[main 918a201] Updated
 1 file changed, 283 insertions(+), 226 deletions(-)

```

### Excercise two

```bash
The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/squashing)
$ cd ..

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym
$ git clone https://github.com/kareraolivier/git-cafe-exercise.git
Cloning into 'git-cafe-exercise'...
remote: Enumerating objects: 107, done.
remote: Counting objects: 100% (14/14), done.
remote: Compressing objects: 100% (10/10), done.
remote: Total 107 (delta 5), reused 4 (delta 4), pack-reused 93Receiving objects:  97% (104/107), 1.75
Receiving objects: 100% (107/107), 1.95 MiB | 787.00 KiB/s, done.

Resolving deltas: 100% (5/5), done.

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym
$ cd git-cafe-exercise/

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/git-cafe-exercise (main)
$ code .

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/git-cafe-exercise (main)
$ git add .

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/git-cafe-exercise (main)
$ git commit -m "Updated"
[main 918a201] Updated
 1 file changed, 283 insertions(+), 226 deletions(-)

```

## Bundle VI

### Excercise one

```bash

Switched to branch 'main'
Your branch is up to date with 'origin/main'.

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/git-cafe-exercise (main)
$ git checkout -b new/feature
Switched to a new branch 'new/feature'

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/git-cafe-exercise (new/feature)
$ git add .

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/git-cafe-exercise (new/feature)
$ git commit -m "feature"
[new/feature 50084ef] feature
 1 file changed, 206 insertions(+), 149 deletions(-)

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/git-cafe-exercise (new/feature)
$ git push
fatal: The current branch new/feature has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin new/feature

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/git-cafe-exercise (new/feature)
$ git push --set-upstream origin new/feature
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.08 KiB | 1.08 MiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'new/feature' on GitHub by visiting:
remote:      https://github.com/kareraolivier/git-cafe-exercise/pull/new/new/feature
remote:
To https://github.com/kareraolivier/git-cafe-exercise.git
 * [new branch]      new/feature -> new/feature
branch 'new/feature' set up to track 'origin/new/feature'.

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/git-cafe-exercise (new/feature)

```

### Excercise two

```bash

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/git-cafe-exercise (new/feature)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/git-cafe-exercise (main)
$ git checkout -b bug/fix
Switched to a new branch 'bug/fix'

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/git-cafe-exercise (bug/fix)
$ git add .

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/git-cafe-exercise (bug/fix)
$ git commit -m "bug-fix"
[bug/fix 434e94c] bug-fix
 1 file changed, 172 insertions(+), 157 deletions(-)

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/git-cafe-exercise (bug/fix)
$ git push --set-upstream origin bug/fix
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.16 KiB | 1.16 MiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'bug/fix' on GitHub by visiting:
remote:      https://github.com/kareraolivier/git-cafe-exercise/pull/new/bug/fix
remote:
To https://github.com/kareraolivier/git-cafe-exercise.git
 * [new branch]      bug/fix -> bug/fix
branch 'bug/fix' set up to track 'origin/bug/fix'.

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/git-cafe-exercise (bug/fix)


```

### Excercise three

```bash

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/git-cafe-exercise (bug/fix)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.


The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/git-cafe-exercise (main)
$ git checkout -b contact/fix
Switched to a new branch 'contact/fix'

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/git-cafe-exercise (contact/fix)
$ git add .

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/git-cafe-exercise (contact/fix)
$ git commit -m "contact-fix"
[contact/fix 4fb3d7d] contact-fix
 1 file changed, 171 insertions(+), 156 deletions(-)

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/git-cafe-exercise (contact/fix)
$ git push --set-upstream origin contact/fix
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.18 KiB | 1.18 MiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'contact/fix' on GitHub by visiting:
remote:      https://github.com/kareraolivier/git-cafe-exercise/pull/new/contact/fix
remote:
To https://github.com/kareraolivier/git-cafe-exercise.git
 * [new branch]      contact/fix -> contact/fix
branch 'contact/fix' set up to track 'origin/contact/fix'.

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/git-cafe-exercise (contact/fix)


```


## Bundle III

```bash

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym
$ ls
Airbnb/        ES6/                         Pinterest_clone/
Airbnb_clone/  Gym_Git_Exercise_Solutions/  TheGym_GoldSmiths_Clone/
Amazon_clone/  HBO_CLONE/                   TheGym_clone_materna_website/

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym
$ cd Gym_Git_Exercise_Solutions/

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/service-redesign)
$ ls
LICENSE  README.md  about.html  home.html  project/  readme.save  service.html

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/service-redesign)
$ ls
LICENSE  README.md  about.html  home.html  project/  readme.save  service.html

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (main)
$ git checkout -b ft/team-page
Switched to a new branch 'ft/team-page'

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/team-page)
$ touch team.html

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/team-page)
$ nano team.html

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/team-page)
$ add .
bash: add: command not found

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/team-page)
$ git add .
warning: in the working copy of 'readme.save', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'team.html', LF will be replaced by CRLF the next time Git touches it

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/team-page)
$ git commit -m "team"
[ft/team-page 2b8b787] team
 2 files changed, 2 insertions(+)
 create mode 100644 readme.save
 create mode 100644 team.html

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/team-page)
$ git push
fatal: The current branch ft/team-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/team-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/team-page)
$ git push --set-upstream origin ft/team-page
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 312 bytes | 312.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/team-page' on GitHub by visiting:
remote:      https://github.com/kareraolivier/Gym_Git_Exercise_Solutions/pull/new/ft/team-page
remote:
To https://github.com/kareraolivier/Gym_Git_Exercise_Solutions.git
 * [new branch]      ft/team-page -> ft/team-page
branch 'ft/team-page' set up to track 'origin/ft/team-page'.

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/team-page)
$ git status
On branch ft/team-page
Your branch is up to date with 'origin/ft/team-page'.

nothing to commit, working tree clean

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/team-page)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (main)
$ git checkout -b ft/contact-page
Switched to a new branch 'ft/contact-page'

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/contact-page)
$ git log
commit 21a26ae26da6f3bc11ac38fd0c3f3ffd152c5b7e (HEAD -> ft/contact-page, origin/main, origin/HEAD, mai
n)
Author: kareraolivier <kareraolivier@gmail.com>
Date:   Fri Jul 28 17:54:39 2023 +0200

    service

commit 30b20708cdbb22c1655a536af0b9edf88df862e2
Merge: f14595e 0812b92
Author: kareraolivier <77101006+kareraolivier@users.noreply.github.com>
Date:   Fri Jul 28 08:44:59 2023 -0700

    Merge pull request #4 from kareraolivier/ft/bundle-2

    Ft/bundle 2

commit 0812b9290abac697ba4c65391562ac2a3ae0f111 (origin/ft/bundle-2, ft/bundle-2)
Author: kareraolivier <kareraolivier@gmail.com>
Date:   Fri Jul 28 17:37:09 2023 +0200

    service

commit 35b0426c2e7b91ce02e828852ae19015a0cb2131
Author: kareraolivier <kareraolivier@gmail.com>
Date:   Fri Jul 28 17:35:38 2023 +0200

    service

commit c4b4b495eb15e9ea87910800a31bb5a599f33bf2
Merge: 7bd1c72 f14595e
Author: kareraolivier <kareraolivier@gmail.com>
Date:   Fri Jul 28 17:26:17 2023 +0200

    Merge branch 'main' into ft/bundle-2

commit f14595ea4156d0e2967b5c50d1baf14eeb542a31
Merge: 5e64794 434f7b1
Author: kareraolivier <kareraolivier@gmail.com>
cherry-pick command

[ft/contact-page ca26937] cherry-pick command
 Author: kareraolivier <77101006+kareraolivier@users.noreply.github.com>
 Date: Wed Jul 26 03:01:10 2023 -0700
 1 file changed, 2 insertions(+), 5 deletions(-)

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/contact-page)
$ ls
LICENSE  README.md  about.html  home.html  project/  service.html  services.html

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/contact-page)
$ git cherry-pick "c04f53c6accb4f990b2012a116fcae11b997fd30"
Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
error: could not apply c04f53c... Update README.md
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git cherry-pick --continue".
hint: You can instead skip this commit with "git cherry-pick --skip".
hint: To abort and get back to the state before "git cherry-pick",
hint: run "git cherry-pick --abort".

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/contact-page|CHERRY-PICKING)
$ git cherry-pick --continue
error: Committing is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
Update README.md

[ft/contact-page 2ae098d] Update README.md
 Author: kareraolivier <77101006+kareraolivier@users.noreply.github.com>
 Date: Wed Jul 26 03:01:10 2023 -0700

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/contact-page)
$ touch contact.html

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/contact-page)
$ nano contact.html

The Gym@DESKTOP-PN6DN2V MINGW64 ~/Desktop/TheGym/Gym_Git_Exercise_Solutions (ft/contact-page)


```
