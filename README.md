# Clases de git
Estas clases se llevarán acabo durante dos semanas a horas 9pm

## Clase 1
### Primeros comandos de git
*Para iniciar un nuevo repositorio en git utilizamos:

```bash
          git init
```
*Este comando se utiliza para agregar cambios en un archivo específico al área de preparación (staging area) en Git:

```bash
         git add nombreArchivo
```

 *Este comando se utiliza para guardar los cambios confirmados en el repositorio:
```bash
         git commit -m "titulo del archivo"
```

*Este comando muestra el estado actual del repositorio Git:
```bash
         git status
```

*Para volver a un commit anterior usamos:
```bash
        git checkout <hash_del_commit_anterior>
        git reset --hard <hash_del_commit_anterior>
```           

*Para revisar historial o identificar cambios utilizamos:
```bash
         git log
```
### Importante:

**Head significa que estas aqui, puntero para saber donde estamos**

## Clase 2
La rama es un snapshot de la división del estado del código, un nuevo apuntador(bifurcación)

### ¿Para que sirve?
permite realizar un desarrollo no lineal y colaborativo

*Para listar las ramas:
```bash
         git brach
```
*Para crear una rama(especificar lo que hará):
```bash
         git brach "nombre de la rama"
```
*Para cambiar entre ramas:
```bash
         git switch "nombre de la rama"
         
         git checkout "nombre de la rama" (no recomendado)
```

*Para cambiar y crear una rama:
```bash

         git checkout -b "nombre de la rama"

        git switch -c "nombre de la rama"
      
```
### Fusionar ramas

Integración de dos ramas, incorporar los cambios de una rama a la ram donde estoy.

*Para eliminar una rama(limpiar el espacio de trabajo):
```bash

         git brach -d "nombre de la rama"
 ```
*Ver todas las ramas:
```bash

         git brach -a
 ```

*Ver historial de otras maneras:
```bash

         git log --oneline

         git log --graph
 ```
 
### Conflictos
