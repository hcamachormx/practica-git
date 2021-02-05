# **Docuementando comandos de GIT con Markdown**


## Esto es lo que vamos haciendo en la práctica de GIT
<br>

### Ejecutar el comando 
```
git init
```

Esto crea el directorio y los archivos de gestión de GIT.
<br><br>
### Ejecutar el comando 
```
git status
```

Este muestra el estado de los recursos con los que estoy trabajando.
<br><br>
### Git tiene 3 áreas de archivos:

- Área de trabajo: es mi directorio local.
- Área de stagging: es donde voy agregando mis recursos de manera temporal
- Área de repositorio.


<br><br>
### Ejecutar el comando 
```
git add
```
Agrega archivos al área de stagging.
<br><br>
### Ejecutar el comando 
```
git commit
```

Agrega los recursos al área de repositorio.
<br><br>
### Me identifico en el repositorio
```
git config --global user.email "micorreo@gmail.com"
git config --global user.name "miusuario"
```

<br><br>
### Este comando me permite ver los logs de los cambios aplicados.
```
git log"
```

### Deshago los cambios en mi área de trabajo, uso los comandos restore o checkout, por alguna razón los tutoriales usan checkout, pero mi ayuda de comando usa restore.

```
git restore mi_archivo

```
Toma el archivo de stage y lo reemplaza en el área de trabajo.
**Ojo: SE PIERDEN LOS ÚLTIMOS CAMBIOS QUE SE HAYAN AGREGADO**


```
git restore --staged mi_archivo

```
Este comando reemplaza el recurso que se agregó al área de stage tomando como base le archivo del repositorio. 
**Ojo: SE PIERDEN LOS CAMBIOS QUE SE TENÍAN EN STAGE Y POR LO TANTO EN EL ÁREA DE TRABAJO.**




