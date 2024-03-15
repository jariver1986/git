# git

- Descargar git
- Crear carpeta
- Clic derecho dentro de la carpeta
- Abrir git bash

# Ver secuencia de lineas de comando


![image](https://github.com/jariver1986/git/assets/62295761/1e422d59-7ee9-4a74-8902-33906d83bc7e)

![image](https://github.com/jariver1986/git/assets/62295761/3a68edbd-dfbf-419f-8f6f-97bb70119c89)


- Lineas de comando

$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   suma.py

$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   suma.py

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   suma.py


$ git add .

$ git commit "version2"
error: pathspec 'version2' did not match any file(s) known to git

$ git commit -m "version2"
[master (root-commit) adefa17] version2
 1 file changed, 3 insertions(+)
 create mode 100644 suma.py

$ git config -global user.email "jariver1986@gmail.com"
error: did you mean `--global` (with two dashes)?

$ git config --global user.email "jariver1986@gmail.com"

$ git config --global user.name "jariver1986"

$ git commit -m "version2"
On branch master
nothing to commit, working tree clean

$ git remote add origin "https://github.com/jariver1986/Zephyr"
error: remote origin already exists.

$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 225 bytes | 225.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/jariver1986/Zephyr/pull/new/master
remote:
To https://github.com/jariver1986/Zephyr
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   suma.py

no changes added to commit (use "git add" and/or "git commit -a")

$ git add .

$ git commit -m "version3"
[master 10be488] version3
 1 file changed, 1 insertion(+), 1 deletion(-)

$ git push -u origin master
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Writing objects: 100% (3/3), 248 bytes | 248.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/jariver1986/Zephyr
   adefa17..10be488  master -> master
branch 'master' set up to track 'origin/master'.

$ git status
