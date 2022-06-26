# KeepCoding_Practicas_Git

**¿Qué comando utilizaste en el paso 11? ¿Por qué?**<br>

`$ git reset --hard HEAD~1`

Porque nos permite volver al estado del *commit* anterior y descartar los cambios del *working copy*.

**¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**<br>

`$ git reflog`<br>
`$ git reset --hard 3c29366`

He utilizado primero "*reflog*" para acceder a un registro de los commits que he hecho y buscar la posición a la que quiero volver.
Con "*git reset --hard*" me muevo a esa posición.

**El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**<br>
No, al ser *fast-forward* y no haber ningún *commit* en *main* no se producen conflictos.

**El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**<br>
Sí, ya cuando va a compararse el contenido de ambos *commits* detecta que en la mismas lienas hay contenido diferente.

**El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**<br>
No hay conflictos ya que es *fast-forward*.

**¿Qué comando o comandos utilizaste en el paso 25?**<br>

`git log --graph --pretty=oneline`

**El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**<br>
Sí, ya que git hace *merge fast-forward* si no se especifica lo contrario y en la rama "title" es en la única que hemos hecho nuevos *commits*.

**¿Qué comando o comandos utilizaste en el paso 27?**<br>

`$ git reset HEAD~1`

**¿Qué comando o comandos utilizaste en el paso 28?**<br>

`$ git restore git-nuestro.md`

**¿Qué comando o comandos utilizaste en el paso 29?**<br>

`$ git branch -D title`

**¿Qué comando o comandos utilizaste en el paso 30?**<br>

`$ git reflog`<br>
`$ git reset --hard 4838ce2`

**¿Qué comando o comandos usaste en el paso 32?**<br>

`$ git log`<br>
`$ git reset --hard 7c79a3e316512ced3f4f0039f1a39a9d2da05004`

**¿Qué comando o comandos usaste en el punto 33?**<br>

`$ git reflog`<br>
`$ git reset --hard 599234a81d2567b735118f9e018ab98e7d9c979a`
