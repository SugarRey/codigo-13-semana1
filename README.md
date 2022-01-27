# Codigo - 13
## Comandos git

```
git init
```
- Este comando solo se hace una vez por proyecto, sirve para inicializar nuestro proyecto con git
- :eye: crear una :file_folder: carpeta oculta llamada .git


```
git status
```
- Poder listar y ver si los archivos estan listo para subir
- :eye: en caso los archivos no esten listos se veran de color rojo y cuando lo esten seran de color verde


```
git add .
git add nombre_de_archivo
```
- Se encarga de agregar los archivos a la memoria de GIT, es decir los guada en un stash git commit -m "comentario"
- Crear un punto en la linea de tiempo :alarm_clock: de nuestros cambios y a estos se le es posible adjuntar un comentario
- :eye: Los comentarios deben estar relacionados a los cambios que hice, esto es una recomendación

```
git push origin main
```
- Sirve para poder subir los cambios a nuestro repositorio en la nube, en este caso github

```

git pull origin main
```
- Sirve para poder descargar los cambios de nuestro repositorio en la ube, en este caso github.

```
git clone url_de_github.com
```
este comando me crear por default una carpeta con el nombre del repositorio.

```
git branch
```
-Sirve para poder listar los branch que tengo localmente y me dice en cual me encuentro actualmente.

```
git chekout -b nombre_de_branch
```
- Sirve para crear un branch nuevo y poder trabajar en el

```
git chekout nombre_de_branch
```
- Sirve para poder moverse entre ramas
- si el ckeckout no tiene el -b solo es para moverse