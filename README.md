# VER ESTUTUS DE LOS ARCHIVOS
```bash
git status # ver el estatus de los archivos (CRUD)
```

# AGREGAR MODIFICACIONES DE LOS ARCHIVOS

```bash
git add . # agregar todos los cambien en los archivos (CRUD).
```
# CREAR COMMIT

```bash

#TYPE COMMIT
#   FIX: aplica cuando se implementa una solucion a un bug
#   FEAT: aplica cuando hay nuava funcionalida.
#SCOPE: Es el identificador del modulo principal al cual se le esta realizando el cambio o mejora. ejemplo: modulo, vista, funcions, etc.
#DESCRIPTION: descripcion general del commit

#EJEMPLO:

#Estructura

git commit -m "<TYPE COMMIT>(<SCOPE>): <DESCRIPTION>"

#Practico

git commit -m "feat(note): add commans git"

#NOTA: es importante tomar en cuanta conventional commit

```

# SUBIR CAMBIOS A LA NUBE
```bash

git push origin <rama>  #  subir los cambios a github, de acuerdo a la rama seleccionada.
```

# DESCARGAR CAMBIOS DE LA NUBE

```bash
git pull origin <rama> # descargar los cambios de github, de acurdo a la rama seleccionada.
```

