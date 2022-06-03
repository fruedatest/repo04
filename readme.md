# Ejercicio 4: NO FAST FORWARD
## Crea un repositorio llamado repo04 y basando en el ejemplo anterior realiza un commit no fast-forward. En este caso antes de hacer el merge sube ambas ramas por si te equivocas poder volver a clonar el repositorio

```
    $ git init repo04
    $ cd repo04
    $ nano readme.md
    $ git add readme.md
    $ git commit -m "commit001"
    $ git remote -v
    $ git remote add origin https://github.com/fruedatest/repo04.git
    $ git branch -M main
    $ git push -u origin main
    $ git checkout -b noFastForward
    


```