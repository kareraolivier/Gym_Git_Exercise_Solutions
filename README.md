# Gym_Git_Exercise_Solutions

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
