# Entrega del Trabajo Práctico Integrador

## Datos del participante

- Nombre y apellido: Priscila Vega
- Curso: Introduccion a Git y GitHub para la gestion de proyectos digitales
- Fecha de entrega: 11/09/2026

## Enlaces

- Repositorio de GitHub: https://github.com/priscilavega14p-source/tp-integrador-vega-priscila
- Issue: https://github.com/priscilavega14p-source/tp-integrador-vega-priscila/issues/1
- Pull request: https://github.com/priscilavega14p-source/tp-integrador-vega-priscila/pull/2

## Comandos principales utilizados

Los comandos utilizados durante el trabajo fueron:

- `git init`
- `git status`
- `git add`
- `git commit`
- `git log --oneline`
- `git remote add origin`
- `git remote -v`
- `git push`
- `git branch`
- `git switch`
- `git merge`
- `git pull`

También se utilizó `git switch -c` para crear la rama de trabajo.

## Descripción del proceso

Primero se creó una carpeta local para el proyecto y se inicializó Git con `git init`.
Luego se consultó el estado del repositorio con `git status` y se creó la estructura inicial con los archivos de documentación y la carpeta del proyecto.
Los cambios se registraron mediante varios commits claros y específicos.
Después se creó un repositorio público en GitHub y se vinculó con el repositorio local mediante `git remote add origin`.
Se creó una issue relacionada con una mejora de la documentación y, para resolverla, se creó la rama `mejora-readme`.
En esa rama se modificó el README, se realizó un commit y se publicó la rama en GitHub.
Finalmente se creó una pull request hacia `main`, se integraron los cambios y se actualizó la rama principal local mediante `git pull`.

## Dificultades encontradas

Durante el proceso puede aparecer como dificultad que Git solicite configurar el nombre y el correo electrónico del usuario antes de realizar un commit. Se resuelve configurándolos con `git config --global user.name` y `git config --global user.email`.

También puede ser necesario comprobar que la rama principal se llame `main` antes de realizar el primer `push`. Si tiene otro nombre, se puede renombrar con `git branch -M main`.

## Reflexión final

La realización de este trabajo permitió comprender cómo Git ayuda a controlar las diferentes versiones de un proyecto y cómo GitHub permite publicar y colaborar sobre ese trabajo. Se aprendió a registrar cambios mediante commits, trabajar de manera independiente en una rama y luego integrar las modificaciones a la rama principal. También se comprendió la utilidad de las issues para organizar tareas y de las pull requests para revisar e incorporar cambios. En conjunto, Git y GitHub permiten mantener los proyectos digitales más ordenados, trazables y fáciles de compartir.
El uso de Git y GitHub permitio comprender la importancia del control de versiones y de mantener un registro ordenado de los cambios realizados. Tambien aprendi a trabajar con ramas, commits, issues y pull requests para organizar mejor un proyecto final 

