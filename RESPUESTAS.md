1. ¿Qué es git?
Es un sistema que controla o administra las distintas versiones de un programa.
2. ¿Por qué queremos utilizar git?
Porque nos permite controlar los cambios en el codigo,poder constribuir con multiples desarrolladores,nos permite trabajar con un repositorio de codigo 
y multiples desarrolladores podran alterar ese codigo, podemos revertir los cambios,puede trabajar con repositores locales y remotos, tambien nos permite
tomar una foto alcodigo,etc.
3. ¿Qué es el bash que instala git?
Es un terminal que en realidad es como una consola pero con mejores funcionalidades.
4. Describa los estados (working directory, staging area, repository)
Working directory:Es donde estamos trabajando con nuestros archivos.
Staging area:Es donde vamos agregar todos los archivos que vamos a preparar para el guardado en GIT.
Repository:Es donde se guardan todos los archivos.
5. Describa el flujo para crear un nuevo repositorio git.
Se hace con git commit -m "descripcion".
6. Describa el flujo para agregar un archivo simple al repositorio.
Se hace con el comando git push con el cual es para subirlo a un repositorio remoto
7. Describa el flujo para cambiar el archivo agregado y guardar los cambios en el repositorio.
Cuando modificamos o agregamos un archivo al proyecto ponemos git status y te aparece un archivo en rojo por lo que no esta agregado entonces ponemos git add 
y el nombre del archivo para agregarlo al proyecto y despues ponemos git commit que hace una copia que se guarda y se agrega al repositorio.
8. ¿Cómo hago para ignorar un archivo o carpeta?
Se hace con el .gitignore
9. Explique qué es un branch. Dé un pequeño ejemplo de cómo haría un branch.
 Branch:Nos muestra los proyectos que tenemos creados.
 Ejemplo:
 Creamos un branch llamado nuevo «nuevo-branch» y con el checkout nos movemos a el (el working directory queda apuntando a este branch para poder trabajar con el).
 El nuevo branch se crea a partir del branch en el que nos encontramos, por lo que ahora mismo el master y el nuevo-branch tendrían los mismos cambios.
 A partir de este momento podemos trabajar en cada branch de forma independiente.
10. ¿Qué hago con `git add .`?
Se utiliza para pasar los archivos del working directory hasta el staging area.
11. ¿Cómo cambiamos de un branch a otro?
Se hace con un comando llamado checkout con el "nombre del branch al que se quiere pasar"
12. Investigue qué es Markdown y responda todas las preguntas anteriores en este lenguaje (con el nombre de archivo RESPUESTAS.md). Súbalo al repositorio.
Markdownes un lenguaje de marcado ligero desarrollado por John Gruber en 2004 que trata de conseguir la máxima legibilidad y facilidad de publicación tanto en su 
forma de entrada como de salida y que a la vez están listos para ser formados en otras plataformas.
