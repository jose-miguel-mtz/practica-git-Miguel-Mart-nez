
José Miguel Martínez Blanco 
Matricula: 2630043
Prática de vinculación de Git con GitHub
Objetivo: el objetivo es que el estudiante aprenda el como crear un repositorio y un comit con git en una carpeta y subirlo a la nube y vincularla con GitHub. 
Comandos utilizados:
cd  ~
cd
git config --global user.name 
git config --global user.email 
mkdir 
New-Item archivo.txt
New-Item archivo.md
git init
git branch -M main
git status
git add -A
git status
git commit -m
git remote origin "URL"
git reomte -v
git push -u origin main
git pull origin main

¿Cómo se creo el repositorio local? el repositorio local se creo en la power shell, entrando en la ruta del usuario principal (cd ~), ahi configure la laptop con (git config --global user.name) y (git config --global user.email), despues cambiando a desktop (cd desktop) y ahi creandola carpeta del proyecto (mkdir practica-git-Miguel-Mat-nez)y ahi inicializando el repositorio (git init) y despues, dentro de esa carpeta (cd practica-git-Miguel-Mat-nez) crear los documentos .txt y .md (New-Item archivo.txt) y (New-Item archivo.md).

¿Cómo se vinculo el repositorio local con GitHub? Primerose creoun repositorio publico en GitHub con el nombre de "practica-git-Miguel-Mart-nez" , se copiola URL del repositorio y en la powershell se ingreso el comando  git remote add origin "URL del repositorio", se verifico que se halla agragado correctamente con el comando git remote -v, una vez comprobado, ahora se suben los documentos que estan en la zona de Dit D.B con el comando git push -u origin main y checar que se hallan enviado. Si,  si se enviaron,entonces ya estara vinculado. Se podra modificar desde un repositorio de Git el repositorio de GitHub y de GitHub a Git.

Explicacion de la sincroizacion local con GitHub: Primero se debe de configurar la laptop o pc con los datos del usuario (user name y user email), despues, crear una carpeta con el nombre indicado y ahi inicializar el repositorio de git y creando los documentos .txt y .md y pasarlos de la zona de untrack files a la zona de staying y dela zona de staying a la nube.

Explicacion de la sincronizacion de GitHub con local: Ahoara se debe de crear un repositorio publico en GitHub con el nombre "practica-git-Miguel-Mart-nez" y copiar la URL y en la powershell con el comando git remote add origin "URL copiada" y despues subirlos doccumentos que estan en la zona de Git D.B con el comando git push -u origin main. 

Descripcion delos arhivos contenidos en el repositorio: En el archivo.txt se registraron las modificaciones realizadas para comprobar si Git y GitHub se respondian 
reciprocamente o en otras palabras, si estaban sincronizadas.

Conclusion personal: En conclusion esta practica funciono para aprender como respaldar documentos por medio de la nube con los servicios que nos ofrece Git y GitHub con su vinculacion facil y rapida.