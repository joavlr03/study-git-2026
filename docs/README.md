# Documentação 
Pasta de documentação do projeto
## Capitulo 1 

### Sub Título

* item 1
* item 2
* item 3


### Instruções para commit no github

labsfiap@L1710MICRO34 MINGW64 /d/projetos/study-git-2026
$ pwd
/d/projetos/study-git-2026

labsfiap@L1710MICRO34 MINGW64 /d/projetos/study-git-2026
$ ls -la
total 0
drwxr-xr-x 1 labsfiap 1049089 0 Feb 23 20:01 ./
drwxr-xr-x 1 labsfiap 1049089 0 Feb 23 19:58 ../
drwxr-xr-x 1 labsfiap 1049089 0 Feb 23 20:01 dados/
drwxr-xr-x 1 labsfiap 1049089 0 Feb 23 20:02 docs/

labsfiap@L1710MICRO34 MINGW64 /d/projetos/study-git-2026
$ git init
Initialized empty Git repository in D:/projetos/study-git-2026/.git/

labsfiap@L1710MICRO34 MINGW64 /d/projetos/study-git-2026 (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        docs/

nothing added to commit but untracked files present (use "git add" to track)

labsfiap@L1710MICRO34 MINGW64 /d/projetos/study-git-2026 (master)
$ git branch

labsfiap@L1710MICRO34 MINGW64 /d/projetos/study-git-2026 (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        dados/
        docs/

nothing added to commit but untracked files present (use "git add" to track)

labsfiap@L1710MICRO34 MINGW64 /d/projetos/study-git-2026 (master)
$ git add .

labsfiap@L1710MICRO34 MINGW64 /d/projetos/study-git-2026 (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   dados/.gitkeep
        new file:   docs/README.md


labsfiap@L1710MICRO34 MINGW64 /d/projetos/study-git-2026 (master)
$ git commit -m "docs: Primeiro commit"
[master (root-commit) 6015e70] docs: Primeiro commit
 
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly:

    git config --global user.name "Your Name"
    git config --global user.email you@example.com

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 2 files changed, 9 insertions(+)
 create mode 100644 dados/.gitkeep
 create mode 100644 docs/README.md

labsfiap@L1710MICRO34 MINGW64 /d/projetos/study-git-2026 (master)
$ ^C

labsfiap@L1710MICRO34 MINGW64 /d/projetos/study-git-2026 (master)
$ git config --global user.name "joavlr03"

labsfiap@L1710MICRO34 MINGW64 /d/projetos/study-git-2026 (master)
$ git config --global user.email "seuemailexemplo@gmail.com"

labsfiap@L1710MICRO34 MINGW64 /d/projetos/study-git-2026 (master)
$ git commit -m "docs: Primeiro commit"
On branch master
nothing to commit, working tree clean

labsfiap@L1710MICRO34 MINGW64 /d/projetos/study-git-2026 (master)
$ git status
On branch master
nothing to commit, working tree clean

labsfiap@L1710MICRO34 MINGW64 /d/projetos/study-git-2026 (master)
$ git branch -M main

labsfiap@L1710MICRO34 MINGW64 /d/projetos/study-git-2026 (main)
$
