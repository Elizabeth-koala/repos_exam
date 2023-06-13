
LAB10-PC28@LAB10-PC28 MINGW64 ~
$ git config --global user.name "Elizabeth-koala"

LAB10-PC28@LAB10-PC28 MINGW64 ~
$ git config --global user.email "tic-280107@utnay.edu.mx"

LAB10-PC28@LAB10-PC28 MINGW64 ~
$ cd c:

LAB10-PC28@LAB10-PC28 MINGW64 /c
$ git clone https://github.com/Elizabeth-koala/repos_exam.git
Cloning into 'repos_exam'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

LAB10-PC28@LAB10-PC28 MINGW64 /c
$ cd repos_exam

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git branch produccion

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git branch
* main
  produccion

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git branch ventas

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git branch recurso_humano

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git branch
* main
  produccion
  recurso_humano
  ventas

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git checkout produccion
Switched to branch 'produccion'

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (produccion)
$ touch "materia prima.txt"

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (produccion)
$ touch "producto final.txt"

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (produccion)
$ git . add
git: '.' is not a git command. See 'git --help'.

The most similar commands are
        am
        gc
        mv
        p4
        rm

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (produccion)
$ git add .

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (produccion)
$ git status
On branch produccion
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   fotos/imagenproducto.png
        new file:   materia prima.txt
        new file:   producto final.txt


LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (produccion)
$ git checkout main
Switched to branch 'main'
A       fotos/imagenproducto.png
A       materia prima.txt
A       producto final.txt
Your branch is up to date with 'origin/main'.

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git config --global user.name "Elizabeth-koala"

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git config --global user.email "tic-280107@utnay.edu.mx"

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git log
commit d62f574ccfe837a42e07776012c5906e60ce2c85 (HEAD -> main, origin/main, origin/HEAD, ventas, recurso_humano, produccion)
Author: Elizabeth-koala <134746521+Elizabeth-koala@users.noreply.github.com>
Date:   Mon Jun 12 16:37:04 2023 -0700

    Initial commit

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git add .

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   fotos/imagenproducto.png
        new file:   materia prima.txt
        new file:   producto final.txt


LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git push origin main
remote: Permission to Elizabeth-koala/repos_exam.git denied to MarcusXxtream.
fatal: unable to access 'https://github.com/Elizabeth-koala/repos_exam.git/': The requested URL returned error: 403

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git push -u origin produccion
remote: Permission to Elizabeth-koala/repos_exam.git denied to MarcusXxtream.
fatal: unable to access 'https://github.com/Elizabeth-koala/repos_exam.git/': The requested URL returned error: 403

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git push -u origin produccion
remote: Permission to Elizabeth-koala/repos_exam.git denied to MarcusXxtream.
fatal: unable to access 'https://github.com/Elizabeth-koala/repos_exam.git/': The requested URL returned error: 403

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git clone https://github.com/Elizabeth-koala/repos_exam.git
fatal: could not create work tree dir 'repos_exam': No such file or directory

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam
$ cd c:

LAB10-PC28@LAB10-PC28 MINGW64 /c
$ git clone https://github.com/Elizabeth-koala/repos_exam.git
Cloning into 'repos_exam'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

LAB10-PC28@LAB10-PC28 MINGW64 /c
$ cd repos_exam

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git branch produccion

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git branch ventas

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git branch recurso_humano

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git branch
* main
  produccion
  recurso_humano
  ventas

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git checkout produccion
Switched to branch 'produccion'

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (produccion)
$  touch "materia prima.txt"

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (produccion)
$  touch "productofinal.txt"

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (produccion)
$  touch "imagenproducto.txt"

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (produccion)
$ git checkout ventas
Switched to branch 'ventas'

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (ventas)
$  touch "tiendas.txt"

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (ventas)
$ git checkout recurso_humano
Switched to branch 'recurso_humano'

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (recurso_humano)
$  touch "empleados.txt"

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (recurso_humano)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git add .

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git push
remote: Permission to Elizabeth-koala/repos_exam.git denied to MarcusXxtream.
fatal: unable to access 'https://github.com/Elizabeth-koala/repos_exam.git/': The requested URL returned error: 403

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git log
commit d62f574ccfe837a42e07776012c5906e60ce2c85 (HEAD -> main, origin/main, origin/HEAD, ventas, recurso_humano, produccion)
Author: Elizabeth-koala <134746521+Elizabeth-koala@users.noreply.github.com>
Date:   Mon Jun 12 16:37:04 2023 -0700

    Initial commit

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git config --global user.name "Elizabeth-koala"

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git config --global user.email "tic-280107@utnay.edu.mx"

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git log
commit d62f574ccfe837a42e07776012c5906e60ce2c85 (HEAD -> main, origin/main, origin/HEAD, ventas, recurso_humano, produccion)
Author: Elizabeth-koala <134746521+Elizabeth-koala@users.noreply.github.com>
Date:   Mon Jun 12 16:37:04 2023 -0700

    Initial commit

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ ^C

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git config --global user.name "Elizabeth-koala"

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git config --global user.email "tic-280107@utnay.edu.mx"

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git log
commit d62f574ccfe837a42e07776012c5906e60ce2c85 (HEAD -> main, origin/main, origin/HEAD, ventas, recurso_humano, produccion)
Author: Elizabeth-koala <134746521+Elizabeth-koala@users.noreply.github.com>
Date:   Mon Jun 12 16:37:04 2023 -0700

    Initial commit

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   empleados.txt
        new file:   imagenproducto.txt
        new file:   materia prima.txt
        new file:   productofinal.txt
        new file:   tiendas.txt


LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git commit -m "subiendo a plataforma"
[main d4b9d3b] subiendo a plataforma
 5 files changed, 8 insertions(+)
 create mode 100644 empleados.txt
 create mode 100644 imagenproducto.txt
 create mode 100644 materia prima.txt
 create mode 100644 productofinal.txt
 create mode 100644 tiendas.txt

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git push
info: please complete authentication in your browser...
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (5/5), 465 bytes | 465.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Elizabeth-koala/repos_exam.git
   d62f574..d4b9d3b  main -> main

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git push
Everything up-to-date

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git tag

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git merge recurso_humano
Already up to date.

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git add .

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git push
Everything up-to-date

LAB10-PC28@LAB10-PC28 MINGW64 /c/repos_exam (main)
$ git log
