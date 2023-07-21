
# GIT  🌿 

Git es un sistema de control de versiones distribuido que permite a los desarrolladores realizar un seguimiento de los cambios realizados en su código fuente y colaborar de manera efectiva en proyectos de desarrollo de software.

## Utilidades

- **Registro de cambios**: Git realiza un seguimiento detallado de cada cambio realizado en el código, lo que permite a los desarrolladores ver y entender exactamente qué cambios se han realizado en cualquier momento.

- **Control de versiones**: Los cambios se registran en forma de "commits", que son instantáneas de los archivos del proyecto en un momento dado. Esto permite a los desarrolladores retroceder en el tiempo y ver cómo era el código en versiones anteriores.

- **Colaboración**: Varios desarrolladores pueden trabajar en el mismo proyecto al mismo tiempo. Git facilita la combinación de cambios de diferentes personas y la resolución de conflictos.

- **Ramas**: Git permite a los desarrolladores trabajar en ramas separadas del proyecto para desarrollar características nuevas o arreglar problemas sin afectar la rama principal. Luego, estos cambios se pueden fusionar con la rama principal cuando estén listos.

- **Seguridad**: Al ser distribuido, cada desarrollador tiene una copia completa del historial del repositorio. Esto proporciona seguridad y protección contra pérdidas.

## Stagging Area y Repositorio Local
En Git, la Staging Area y el Repositorio Local son dos conceptos fundamentales relacionados con el control de versiones y la forma en que se gestionan los cambios en el código.

- **Staging Area**: Hace referencia a el área de ensayo, donde preparas los cambios que deseas incluir en el siguiente commit.

- **Repositorio Local**: Es donde se almacenan todos los cambios y versiones de tu proyecto. Es básicamente una base de datos que guarda el historial de commits y la información necesaria para reconstruir cualquier versión anterior del proyecto.

Cuando realizas un commit en Git, los cambios en la Staging Area se guardan permanentemente en el repositorio local. Cada commit tiene un identificador único (hash) y contiene una instantánea del estado de tu proyecto en ese momento.
## Lista de comandos más utilizados

```bash

git init                        # Inicializar un directorio existente como uno de Git.
git clone [url]                 # Clonar un repositorio remoto.
git add [archivo]               # Agrega cambios al área de preparación.
git commit -m "descripcion"     # Crea un nuevo commit con los cambios del staging area.
git status                      # Muestra el estado actual del repositorio. 
git log                         # Muestra el historial de commits en el repositorio.
git push                        # Envía los commits locales al repositorio remoto. 
git pull                        # Obtiene y fusiona los cambios del repositorio remoto en local (equivalente a ejecutar git fetch seguido de git merge). 
git fetch                       # Descarga los cambios del repositorio remoto sin fusionarlos con tu rama local actual. 
git branch [nombre]             # Crea una rama con el nombre especificado.
git branch                      # Muestra una lista de ramas en el repositorio.
git checkout [rama]             # Cambia a la rama especificada. Te permite trabajar en una rama diferente.
git merge [rama]                # Fusiona la rama especificada con la rama actual.
git remote add [nombre] [url]   # Agrega un nuevo repositorio remoto con un nombre dado. 
git reset hard [idcommit]       # Restaura a la copia seleccionada.

```
