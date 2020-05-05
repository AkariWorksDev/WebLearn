# LearnWeb

La idea de este repositorio es que aprendaís a usar GitHub y a la vez aprendaís a programar páginas web. Vamos a hacerlo por medio de misiones que vaís a completar creando vuestras ramas para trabajar y luego posteriormente haciendo una PullRequest en la que corregiremos cada misión. 

Si teneís dudas al realizar una mision, preguntar en el [canal de discord de Akari del taller](https://discord.gg/KAexdz3 "canal de discord de Akari del taller").

## Misiones

### Mision 1

En esta mision vaís a aprender a utilizar git y vaís a crear vuestra primera PullRequest.

<details>
  <summary> Instrucciones</summary>

#### Pasos simples

1. Instalar git desde [aquí](https://git-scm.com/ "aquí").
1. `git clone https://github.com/AkariWorksDev/WebLearn.git`
1. `git pull`
1. `git status`
Debería decirte **On branch master**
1. `git branch TUNOMBRE-mision1`
Este comando no devuelve nada, crealo con tu nombre, por ejemplo **Borja-mision1**.
1. `git checkout TUNOMBRE-mision1`
1. `git status`
Debería decirte **On branch TUNOMBRE-mision1**
1. En la raíz, es decir, en la carpeta principal, crea una carpeta con el nombre de tu usuario de git. Dentro crea un archivo txt con algo escrito.
1. `git add .`
1. `git commit -m "Descripción corta de qué has hecho"`. 
1. `git push`
1. Ahora crea la pull request y pide que te lo corrijan.

#### Más información

- En [esta](https://git-scm.com/docs/git-clone "esta") página tienes información sobre el comando git clone.
- En [esta](https://git-scm.com/docs/git-pull "esta") página tienes información sobre el comando git pull.
- En [esta](https://git-scm.com/docs/git-branch "esta") página tienes información sobre cómo crear una rama.
- En [esta](https://git-scm.com/docs/git-checkout "esta") página tienes información sobre el comando git clone.
- En [esta](https://git-scm.com/docs/git-add "esta") página tienes información sobre cómo staggear archivos para commitearlos.
- En [esta](https://git-scm.com/docs/git-commit "esta") página tienes información sobre cómo **commitear** los archivos que has **staggeado**.
- En [esta](https://git-scm.com/docs/git-push "esta") página tienes información sobre cómo pushear.
- Has completado la mision 1. Ahora pídele a alguien del equipo [Master](https://github.com/orgs/AkariWorksDev/teams/master "Master") de Akari que te lo corrija creando la pull request desde la web de GitHub.
<img src="https://i.imgur.com/QYhCBWt.jpg"/>

</details>

### Mision 2

En esta mision vaís a aprender html básico

<details>
  <summary> Instrucciones</summary>

#### Pasos simples

1. `git pull`
2. `git status`
Debería decirte **On branch master**
3. `git branch TUNOMBRE-mision2`
4. `git checkout TUNOMBRE-mision2`
5. `git status`
Debería decirte **On branch TUNOMBRE-mision2**
6. Dentro de la carpeta con tu nombre crea 2 carpetas. Una con nombre **mision1** y otra con nombre **mision2**
7. Mete el archivo .txt de la anterior misión en la carpeta **mision1**
8. Dentro de la carpeta mision2 crea un archivo con nombre **index.html**
9. Vamos a editar el archivo **index.html**. Primero creamos las dos secciones básicas en un html: 
```html
<!DOCTYPE html>
<html>
  <head></head>
  <body></body>
</html>
```
- `<!DOCTYPE html>` Define el archivo como un documento html. A veces no se les pone .html al final a los archivos. Sin esta extensión esta etiqueta le diría al navegador que es un html.
- `<html>` Define el inicio y final de un código html
- `<head>` Define la información del documento
- `<body>` Define el contenido del documento
- Las etiquetas en html pueden ponerse cómo apertura de la etiqueta con sus parámetros, valores de parámetros, contenido + cierre de etiqueta:
```html
<etiqueta param1 = "valorparam1" > Contenido etiqueta </etiqueta>
```
- También pueden ponerse cómo etiqueta sin cierre con sus parámetros:
```html
<etiqueta param1 = "valorparam1" >
```
- Esta última se suele usar por ejemplo para añadir imágenes a una web:
```html
<img src="imagen.gif" height="42" width="42">
```
- Existen muchas etiquetas. Investiga las que añado a continuación y añádelas dentro de nuestro código en **head** o **body** según  corresponda. Más información abajo.
  - a
  - img
  - br
  - p
  - h1
  - input
  - button 
  - div
  - title
  - !--

10. Cuando creas que tu página web está bien formada y contiene todos los tags anteriores ejecuta el comando `git add .`
11. `git commit -m "Descripción corta de qué has hecho"`. 

Dentro 
12. `git add .`
13. `git commit -m "Descripción corta de qué has hecho"`. 
14. `git push`
15. Ahora crea la pull request y pide que te lo corrijan.
16. `git push`

#### Más información
- En [esta](https://www.w3schools.com/tags/tag_a.asp "esta")        página tienes información sobre la etiqueta **a**.
- En [esta](https://www.w3schools.com/tags/tag_img.asp "esta")      página tienes información sobre la etiqueta **img**.
- En [esta](https://www.w3schools.com/tags/tag_br.asp "esta")       página tienes información sobre la etiqueta **br**.
- En [esta](https://www.w3schools.com/tags/tag_p.asp "esta")        página tienes información sobre la etiqueta **p**.
- En [esta](https://www.w3schools.com/tags/tag_hn.asp "esta")       página tienes información sobre la etiqueta **h1**.
- En [esta](https://www.w3schools.com/tags/tag_input.asp "esta")    página tienes información sobre la etiqueta **input**.
- En [esta](https://www.w3schools.com/tags/tag_button.asp "esta")   página tienes información sobre la etiqueta **button**.
- En [esta](https://www.w3schools.com/tags/tag_div.asp "esta")      página tienes información sobre la etiqueta **div**.
- En [esta](https://www.w3schools.com/tags/tag_title.asp "esta")    página tienes información sobre la etiqueta **title**.
- En [esta](https://www.w3schools.com/tags/tag_comment.asp "esta")  página tienes información sobre la etiqueta comentario **!--**.
- Ejemplo de web bien formada:
```html
<!DOCTYPE html>
  <html>

    <head>
      <!--> Esto es un comentario en el código html <-->
      <title> Aprendiendo HTML </title>
    </head>

    <body>

      <div>
        <h1> Esto es un título Enorme </h1>
        <h2> Esto es un título grande </h2>
        <h3> Esto es un título </h3>
        <p> Esto es un párrafo. </p>
        <a href="https://akariworks.es/"> Esto es un enlace a AkariWorks </a>
        <br>
        <input> Esto es un campo para escribir </input>
        <button> Esto es un botón </button>
      </div>

    </body>

  </html>
```

</details>