# PRÁCTICA DEL CURSO git, gitHub y Sourcetree

- **¿Qué comando utilizaste en el paso 11? ¿Por qué?**
    - `git reset --hard HEAD~1`
    - Porque deshacia el ultimo commit junto con el cambio realizado en él

- **¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**
    - `git reflog`
    - Para buscar el commit
    - `git show "#Commit"`
    - Para verificar el cambio de ese commit
    - `git reset --hard "#Commit"`
    - Para rehacer el commit y el cambio

- **El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**
    - No causo ningún conflicto

- **El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**
    - Si, porque el htmlify tenia más contenido que styled en cada una de las lineas del archivo

- **El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**
    - No causo ningún conflicto

- **¿Qué comando o comandos utilizaste en el paso 25?**
    - `git log --graph --pretty=oneline`

- **El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**
    - Si se podría por lo que en ese caso master tambien absorbería a la rama title pero no generaría un commit adicional para documentar el cambio

- **¿Qué comando o comandos utilizaste en el paso 27?**
    - `git reset HEAD~1`

- **¿Qué comando o comandos utilizaste en el paso 28?**
    - `git restore git-nuestro.md`

- **¿Qué comando o comandos utilizaste en el paso 29?**
    - git branch -D title

- **¿Qué comando o comandos utilizaste en el paso 30?**
    - `git reflog`
    - `git reset --hard "#Commit"`

- **¿Qué comando o comandos usaste en el paso 32?**
    - `git checkout "#CommitInicial"`

- **¿Qué comando o comandos usaste en el punto 33?**
    - `git checkout "#CommitTitulo"`
