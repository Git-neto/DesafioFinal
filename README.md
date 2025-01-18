PROCESSO DE INSERÇÃO NO GITHUB

Administrador@XXXXXXX MINGW64 /c/ProjetoGithub/DesafioFinal
$ git init
Initialized empty Git repository in C:/ProjetoGithub/DesafioFinal/.git/

Administrador@XXXXX MINGW64 /c/ProjetoGithub/DesafioFinal (master)
$ git commit -m "verificando"
On branch master

Initial commit

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        arquivo.txt
        decrypter.md
        encrypter.md

nothing added to commit but untracked files present (use "git add" to track)

Administrador@XXXX MINGW64 /c/ProjetoGithub/DesafioFinal (master)
$ git add .

Administrador@XXXXX MINGW64 /c/ProjetoGithub/DesafioFinal (master)
$ git commit -m "verificando"
[master (root-commit) eb8a886] verificando
 3 files changed, 47 insertions(+)
 create mode 100644 arquivo.txt
 create mode 100644 decrypter.md
 create mode 100644 encrypter.md

Administrador@XXXXX MINGW64 /c/ProjetoGithub/DesafioFinal (master)
$ git branch -M main

Administrador@XXXXX MINGW64 /c/ProjetoGithub/DesafioFinal (main)
$ git remote add origin https://github.com/Git-neto/DesafioFinal.git

Administrador@XXXX MINGW64 /c/ProjetoGithub/DesafioFinal (main)
$ git push -u origin main
info: please complete authentication in your browser...
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 778 bytes | 778.00 KiB/s, done.
Total 5 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/Git-neto/DesafioFinal.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

Administrador@XXXXX MINGW64 /c/ProjetoGithub/DesafioFinal (main)
$
