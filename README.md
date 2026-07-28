
# Manual de Buenas Prácticas para Trabajos Universitarios

Fomentar el uso de Git y GitHub como herramienta de colaboración y control de versiones en la creación de documentos (sin programar), promoviendo buenas prácticas de trabajo en equipo. Elaborado por Alirio Chourio y Ricardo Teran

##  Estructura de repositorio
- `/documentos`: Contiene los archivos Markdown con el contenido del manual.
- `/imagenes`: Recursos gráficos utilizados en el manual.
- `/referencias`: Bibliografía y material de apoyo.

## Gestión de proyecto
El trabajo se administra mediante la metodología Kanban. Puedes ver nuestro progreso en el siguiente enlace:
[https://github.com/users/AlirioChourio/projects/2]

## Cómo contribuir 
Para añadir nuevas secciones al manual, sigue este flujo de trabajo estricto:
1. Clona el repositorio: `git clone <URL>`
2. Actualiza tu rama principal: `git pull origin main`
3. Crea una rama para tu sección (ej. `git checkout -b seccion-herramientas`).
4. Redacta tu contenido en **markdown** dentro de la carpeta `/documentos`.
5. Sube tus cambios (`git add .`, `git commit -m "..."`, `git push origin nombre-rama`).
6. Abre un **Pull Request (PR)** en GitHub mencionando el Issue que resuelve (ejemplo: `Closes #4`).
7. Espera la revisión y aprobación de un compañero antes de fusionar.

## Historial de versiones
Revisa el archivo [CHANGELOG.md] para ver las actualizaciones y versiones etiquetadas (Tags) de este manual.