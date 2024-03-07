- Crear un proyecto vacio de git 

```shell
git init
```

- Ver el estado de nuestro proyecto o ver cambios en nuestro proyecto

```shell
git status
```

- Agregar archivos para hacer commit (guardado)

```shell
git add .
git add <file>
git add -A
git add *
```

- Guardamos los cambios en el repositorio local

```shell
git commit 
git commit -m "mensaje descriptivo"
```

- Ver el historio de cambios dentro del proyecto

```shell
git log
```

- Configurar datos de git (nombre, email)

```shell
git config --global user.name "John Doe"
```
```shell
git config --global user.email "john.doe@gmail.com"
```

- Configurar el repositorio remoto (git remote)

```shell
git remote
```
- Añadir el repositorio remoto

```shell
git remote add <nombre_remote> <url_repositorio>
```
- ejemplo:

```shell
git remote add origin https://...
```

- Eliminar el repositorio remoto

```shell
git remote rm <nombre_remote>
```

- Actualizar el repositorio remoto (cambiar la url a donde apunta nuestro proyecto)

```shell
git remote set-url <nombre_remote> <url_repositorio_nuevo>
```

- Ver la informacion de nuestro repositorio remoto

```shell
git remote show origin
```

- Enviar los cambios al repositorio remoto

```shell
git push <nombre_remoto> <rama_o_branch>
```
- Ejemplo:
```shell
git push origin main
```