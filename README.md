# Aplicación de Git y GitHub en Proyectos de Desarrollo de Software

##  ¿Qué es Git?

Git es un **sistema de control de versiones distribuido**, es deci un software que permite:

- Registrar todo el historial de cambios de un proyecto.
- Trabajar en diferentes versiones de un proyecto simultáneamente.
- Colaborar con otros desarrolladores sin conflictos.
- Recuperar versiones anteriores del código.
- Mantener un historial completo de modificaciones.

*Ventajas principales de su uso:*
- Es gratuito y de código abierto.
- Funciona sin conexión a internet.
- Es bastante rápido y eficiente.
- Utilizado por millones de desarrolladores en todo el mundo.

## ¿Qué es GitHub?
GitHub es una plataforma basada en la nube donde cada desarrollador puede almacenar, compartir y trabajar junto con otros usuarios para escribir código. Almacenar el código en un *"repositorio"* en GitHub nos permite:

- Presentar o compartir el trabajo realizado.
- Dejar que otros usuarios revisen el código y realicen sugerencias para mejorarlo.
- Mantener un seguimiento detallado del progreso.
- Herramientas de colaboración (pull requests, issues).
- Tener un hosting gratuito para proyectos públicos y privados.

# Principales Comandos de Git
## 1. Configuración Inicial
![configuracion inicial](configuracion.png)

_Establece la identidad para todos los commits que uno vaya a realizar y se configura el salto de línea dependiendo del Sistema Operativo en que se encuentre, en este caso es Windows por lo que tiene que tener su valor tru y los caracteres cr (para subir código) y lf (si se quiere descargar código del repositorio). Es importante usar el mismo email que tiene en GitHub_

## 2. `git init`

Inicializa un nuevo repositorio Git en el directorio actual. Crea una carpeta oculta `.git` que contiene toda la información del control de versiones.
**Cuándo usarlo:** Al comenzar un nuevo proyecto desde cero.

## 3. `git clone`

Descarga una copia completa de un repositorio remoto a tu máquina local, incluyendo todo el historial de cambios.

**Cuándo usarlo:** Para trabajar en un proyecto existente.

## 4. `git status`

Muestra el estado actual del repositorio:
- Archivos modificados
- Archivos nuevos sin seguimiento
- Archivos preparados para commit
- Rama actual en la que te encuentras

**Cuándo usarlo:** Constantemente, para verificar el estado de tus cambios.

## 5. `git add`

Prepara los archivos para el próximo commit, moviéndolos al "staging area" (área de preparación).
## 6. `git commit`

Guarda los cambios preparados en el historial del repositorio con un mensaje descriptivo.

**Buenas prácticas para mensajes:**
- Usa verbos en imperativo: "Agrega", "Corrige", "Actualiza"
- Sé específico y conciso
- Explica el QUÉ y el POR QUÉ, no el CÓMO

## 7. `git log`

Muestra el historial de commits del repositorio, incluyendo autor, fecha y mensaje.

## 8. `git branch`

Las ramas permiten trabajar en diferentes funcionalidades sin afectar el código principal.

## 9. `git checkout` / `git switch`

Permite moverse entre diferentes ramas del proyecto.

## 10. `git merge`

Integra los cambios de una rama en la rama actual. Se usa típicamente para incorporar funcionalidades completadas a la rama principal.

## 11. `git pull`

Descarga los cambios del repositorio remoto y los fusiona automáticamente con tu rama local. Es equivalente a hacer `git fetch` + `git merge`.

**Cuándo usarlo:** Antes de comenzar a trabajar, para tener la última versión del código.

## 12. `git push`

Envía tus commits locales al repositorio remoto en GitHub.

**Importante:** Debes hacer `git commit` antes de hacer `git push`.

## 13. `git remote`

Conecta tu repositorio local con uno remoto en GitHub.

