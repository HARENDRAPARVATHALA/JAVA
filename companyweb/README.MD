
HARENDRA@LAPTOP-PEUDFGI8 MINGW64 /
$ ls
LICENSE.txt        cmd/  git-bash.exe*  proc/         unins000.exe*
ReleaseNotes.html  dev/  git-cmd.exe*   tmp/          unins000.msg
bin/               etc/  mingw64/       unins000.dat  usr/

HARENDRA@LAPTOP-PEUDFGI8 MINGW64 /
$ cd C:\Program Files\Git\git repo
bash: cd: too many arguments

HARENDRA@LAPTOP-PEUDFGI8 MINGW64 /
$ cd "C:\Program Files\Git\git repo"

HARENDRA@LAPTOP-PEUDFGI8 MINGW64 /git repo
$ ls

HARENDRA@LAPTOP-PEUDFGI8 MINGW64 /git repo
$ mkdir /company_web
mkdir: cannot create directory ‘/company_web’: Permission denied

HARENDRA@LAPTOP-PEUDFGI8 MINGW64 /git repo
$ git init
C:/Program Files/Git/git repo/.git: Permission denied

HARENDRA@LAPTOP-PEUDFGI8 MINGW64 /git repo
$ cd "D:\git"

HARENDRA@LAPTOP-PEUDFGI8 MINGW64 /d/git
$ mkdir /company_web
mkdir: cannot create directory ‘/company_web’: Permission denied

HARENDRA@LAPTOP-PEUDFGI8 MINGW64 /d/git
$ mkdir companyweb

HARENDRA@LAPTOP-PEUDFGI8 MINGW64 /d/git
$ ls
companyweb/

HARENDRA@LAPTOP-PEUDFGI8 MINGW64 /d/git
$ git init
Initialized empty Git repository in D:/git/.git/

HARENDRA@LAPTOP-PEUDFGI8 MINGW64 /d/git (master)
$ ls
companyweb/

HARENDRA@LAPTOP-PEUDFGI8 MINGW64 /d/git (master)
$ cd .git

HARENDRA@LAPTOP-PEUDFGI8 MINGW64 /d/git/.git (GIT_DIR!)
$ ls
HEAD  config  description  hooks/  info/  objects/  refs/

HARENDRA@LAPTOP-PEUDFGI8 MINGW64 /d/git/.git (GIT_DIR!)
$ cd ..

HARENDRA@LAPTOP-PEUDFGI8 MINGW64 /d/git (master)
$ cd companyweb/

HARENDRA@LAPTOP-PEUDFGI8 MINGW64 /d/git/companyweb (master)
$ ls

HARENDRA@LAPTOP-PEUDFGI8 MINGW64 /d/git/companyweb (master)
$ ls
sample.txt

HARENDRA@LAPTOP-PEUDFGI8 MINGW64 /d/git/companyweb (master)
$ LS
README.MD  info.txt

HARENDRA@LAPTOP-PEUDFGI8 MINGW64 /d/git/companyweb (master)
$ GIT STATUS
git: 'STATUS' is not a git command. See 'git --help'.

HARENDRA@LAPTOP-PEUDFGI8 MINGW64 /d/git/companyweb (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ./

nothing added to commit but untracked files present (use "git add" to track)

HARENDRA@LAPTOP-PEUDFGI8 MINGW64 /d/git/companyweb (master)
$ git  add .

HARENDRA@LAPTOP-PEUDFGI8 MINGW64 /d/git/companyweb (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.MD
        new file:   info.txt


HARENDRA@LAPTOP-PEUDFGI8 MINGW64 /d/git/companyweb (master)
$ ;git commit -m  "this is my first commmit"
bash: syntax error near unexpected token `;'

HARENDRA@LAPTOP-PEUDFGI8 MINGW64 /d/git/companyweb (master)
$ git commit -m "this is my first commit"
[master (root-commit) b1c81f6] this is my first commit
 2 files changed, 1 insertion(+)
 create mode 100644 companyweb/README.MD
 create mode 100644 companyweb/info.txt

HARENDRA@LAPTOP-PEUDFGI8 MINGW64 /d/git/companyweb (master)
$ git status
On branch master
nothing to commit, working tree clean

HARENDRA@LAPTOP-PEUDFGI8 MINGW64 /d/git/companyweb (master)
$
