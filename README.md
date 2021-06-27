# PRÁCTICA DEL CURSO git, gitHub y Sourcetree

**1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?**  
    + *git reset --hard HEAD~1*  
    - Porque deshacia el ultimo commit junto con el cambio realizado en él

2. **¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**  
~~~
*<span style="color:green">git reflog</span>*  
Para buscar el commit  
<span style="color:green">git show "#Commit"</span>  
Para verificar el cambio de ese commit  
<span style="color:green">git reset --hard "#Commit"</span>  
Para rehacer el commit y el cambio
~~~

**- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**  
    No causo ningún conflicto

**- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**  
Si, porque el htmlify tenia más contenido que styled en cada una de las lineas del archivo

**- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**  
No causo ningún conflicto

**- ¿Qué comando o comandos utilizaste en el paso 25?**  
<span style="color:green">git log --graph --pretty=oneline</span>

**- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**  
Si se podría por lo que en ese caso master tambien absorbería a la rama title pero no generaría un commit adicional para documentar el cambio

**- ¿Qué comando o comandos utilizaste en el paso 27?**  
<span style="color:green">git reset HEAD~1</span>

**- ¿Qué comando o comandos utilizaste en el paso 28?**  
<span style="color:green">git restore git-nuestro.md</span>

**- ¿Qué comando o comandos utilizaste en el paso 29?**  
<span style="color:green">git branch -D title</span>

**- ¿Qué comando o comandos utilizaste en el paso 30?**  
<span style="color:green">git reflog</span>  
<span style="color:green">git reset --hard "#Commit"</span>

**- ¿Qué comando o comandos usaste en el paso 32?**  
<span style="color:green">git checkout "#CommitInicial"</span></span>

**- ¿Qué comando o comandos usaste en el punto 33?**  
<span style="color:green">git checkout "#CommitTitulo"</span></span>
