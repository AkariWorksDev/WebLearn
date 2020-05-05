# LearnWeb

La idea de este repositorio es que aprendaís a usar GitHub y a la vez aprendaís a programar páginas web. Vamos a hacerlo por medio de misiones que vaís a completar creando vuestras ramas para trabajar y luego posteriormente haciendo una PullRequest en la que corregiremos cada misión. 

Si teneís dudas al realizar una mision, preguntar en el [canal de discord de Akari del taller](https://discord.gg/KAexdz3 "canal de discord de Akari del taller").

## Misiones

### Mision 1

En esta mision vaís a aprender a utilizar git y vaís a crear vuestra primera PullRequest.

<details>
  <summary> Instrucciones</summary>

#### Simplificado en comandos

1. Instalar git desde [aquí](https://git-scm.com/ "aquí").
1. `git clone https://github.com/AkariWorksDev/WebLearn.git`
1. En la raíz, es decir, en la carpeta principal, crea una carpeta con el nombre de tu usuario de git. Dentro crea un archivo txt don algo escrito.
1. `git add .`
1. `git commit -m "Descripción corta de qué has hecho"`. 
1. `git push`

#### Explicación extensa

1. Instalar git desde [aquí](https://git-scm.com/ "aquí").
1. En [esta](https://git-scm.com/docs/git-clone "esta") página tienes información sobre el comando git clone.
1. Ahora deberías saber clonar este repositorio en tu pc. Adelante, clonalo. 
Usa `git clone https://github.com/AkariWorksDev/WebLearn.git´
1. Abrir con Visual Studio la carpeta en la que has clonado el repositorio. Si no tienes Visual Studio instálalo desde [aquí](https://code.visualstudio.com "aqui"). Es un editor de código.
1. En [esta](https://git-scm.com/docs/git-branch "esta") página tienes información sobre cómo crear una rama.
1. Ahora deberías saber crearte una rama. Es importante que crees una. Ponle como nombre **tu nombre** seguido de un **-** seguido de **mision1**. 
El nombre de la rama debería ser algo así: `Pedro-mision1` si tu nombre de gitHub es Pedro. 
El comando final debería ser algo como `git branch Pedro-mision1`
1. En la raíz, es decir, en la carpeta principal, crea una carpeta con el nombre de tu usuario de git.
1. Dentro de esa carpeta crea un archivo **.txt** con un mensaje.
1. En [esta](https://git-scm.com/docs/git-add "esta") página tienes información sobre cómo staggear archivos para commitearlos.
1. Ahora deberías saber **staggear** los archivos que crees, borres o modifiques en el repositiorio dentro de tu rama. Cuando haces cambios, si escribes el comando `git status` en la consola, te sale una lista en rojo de los archivos que NO has staggeado y has creado, alterado o borrado. Si introduces el comando `git add` **staggeas** todos los archivos que pongas a continuación, hazlo. 
Si pones `git add .` incluyendo el `.` al final, equivale a **staggear** todos los archivos modificados, hazlo.
1. En [esta](https://git-scm.com/docs/git-commit "esta") página tienes información sobre cómo **commitear** los archivos que has **staggeado**.
1. Ahora deberías saber crear un commit con tus cambios. 
Introduce el comando: `git commit -m "Descripción corta de qué has hecho"`. 
Con eso habrás hecho un commit. Este se queda guardado en tu local con el estado actual de tu rama. Si más tarde la liases podríamos volver a ese punto, genial. GitHub sirve para esto, para guardar versiones y evitar perder información.
1. En [esta](https://git-scm.com/docs/git-push "esta") página tienes información sobre cómo pushear.
1. Ahora sabes **pushear**. Tienes que pushear los cambios que has hecho en tu rama a **GitHub**. 
Introduce el comando `git push`.
1. Si has hecho todo bien hasta este punto, ahora tus cambios estarán en github. Solo queda crear una PullRequest desde la página web de GitHub. Lee [aquí](https://github.com/omegaup/omegaup/wiki/C%C3%B3mo-Hacer-un-Pull-Request#subir-tus-cambios-y-hacer-pull-request "aquí") si no sabes cómo.
1. Has completado la mision 1. Ahora pídele a alguien del equipo [Master](https://github.com/orgs/AkariWorksDev/teams/master "Master") de Akari que te lo corrija.
</details>