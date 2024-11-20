# Comandos

## Crear ficheiros

    touch archivo.txt archivo2.txt

## Eitar ficheiros

    nano ficheirro1.txt

## Facer commit

    git commit -m "Commit inicial"

## Crear carpeta

    mkdir carpeta

## Añadir UN archivo

    git add

## Añadir todos los archivos
    
    git add .

## Añadir todos los archivos mostrando lo que está ignorado

    git add *

## Push

    git push

## Eliminar archivo

    rm archivo

## Renombrar archivo

    mv nombre_archivo nuevo_nombre_archivo

## Cambiar nombre ultimo commit

    git commit --amend

## Combrobar status repositorio

    git status

## Comprobar status de forma corta

    git status -s

## Crear rama

    git branch nombre 

## Moverse a la rama

    git checkout nombre

## Fusionar ramas 

    git merge nombre nombre2

## Eliminar rama a la fuerza

    git branck -D nombre

## Eliminar rama sin ser a la fuerza

    git branch -d

## Mostrar todo lo q hay e una ubicacion (ocultos)

    ls -a

## Iniciar repossitorio

    git init

## Saber donde estou ubicado

    pwd

## Ver si ten remotos

    git remote -v

## Ignorar todos los que empiecen por...
Metemos dentro de `.gitignore`:

    (lo que empiecen por ...)*

Para poner excepto un archivo:

    !_archivo.txt

Si queremos que ignore o que acaban por...:

    *(lo que queremos ignorar)

## Sincronizar repositorios

    git pull (desde el repositorio que queremos sincronizar)