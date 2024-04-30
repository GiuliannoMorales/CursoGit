# Clases de git
Estas clases se llevarán acabo durante dos semanas a horas 9pm
## Primeros comandos de git
Para iniciar un nuevo repositorio en git utilizamos:

```
          git init
```
Este comando se utiliza para agregar cambios en un archivo específico al área de preparación (staging area) en Git:
```
         git add nombreArchivo
```

 Este comando se utiliza para guardar los cambios confirmados en el repositorio:
```
         git commit -m "titulo del archivo"
```
Este comando muestra el estado actual del repositorio Git:
```
         git status
```
**Head significa que estas aqui, puntero para saber donde estamos**

Para volver a un commit anterior usamos:
```
        git checkout <hash_del_commit_anterior>
        git reset --hard <hash_del_commit_anterior>
```
           