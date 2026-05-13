## 1️⃣ ¿Qué es Git?
[cite_start]Git es una plataforma que nos permite tener un **control exhaustivo de versiones** en un repositorio en la nube[cite: 6]. [cite_start]Es una herramienta fundamental para trabajar de forma segura y organizada en proyectos de desarrollo, permitiendo guardar diferentes estados del trabajo[cite: 11].

## ¿Cuál es el flujo de trabajo de Git?
El funcionamiento de Git se basa en la sincronización de tres espacios distintos:
* [cite_start]**Directorio local:** Es la carpeta física en nuestro ordenador donde realizamos los cambios y trabajamos habitualmente[cite: 8].
* [cite_start]**Repositorio local:** Contiene los cambios que realizamos en el directorio local y que decidimos subir a Git; es un paso de seguridad antes de enviarlos al servidor[cite: 13, 14].
* [cite_start]**Repositorio remoto:** Es el servidor en la nube (GitHub) que contiene todos los cambios subidos por todos los usuarios del proyecto[cite: 16, 17].



## Comandos realizados durante la práctica
Durante el laboratorio de SMR, hemos utilizado los siguientes comandos fundamentales:

* **Git add:** Sirve para preparar los archivos del directorio local antes de realizar un commit.
* [cite_start]**Git commit:** Sube los cambios del directorio local al repositorio local[cite: 18].
* [cite_start]**Git push:** Sube los cambios del repositorio local al repositorio remoto en la nube[cite: 19].
* [cite_start]**Git pull:** Descarga y actualiza todos los cambios del repositorio remoto directamente en nuestro directorio local[cite: 20].
* **Git fetch:** Permite consultar si hay cambios en el repositorio remoto sin descargarlos todavía al directorio de trabajo.
* **Git merge:** Se utiliza para unir los cambios de diferentes versiones o ramas de un proyecto.


##  Gestión de Conflictos
### ¿Qué es un conflicto y qué lo causa?
[cite_start]Un **conflicto** ocurre cuando intentamos hacer un `push` o un `merge` y el archivo que hemos editado también ha sido modificado por otra persona en la misma línea[cite: 27]. [cite_start]En ese momento, Git no sabe qué versión es la correcta y se produce un error[cite: 28].

### ¿Cómo podemos solucionarlo?
Ante un conflicto, debemos decidir manualmente qué información conservar:
* [cite_start]**Quedarnos con nuestros cambios (HEAD):** Mantenemos nuestra versión local[cite: 29].
* [cite_start]**Quedarnos con los cambios del repositorio (MASTER):** Aceptamos la versión que viene del servidor[cite: 30].
* [cite_start]**Combinar ambos:** Revisamos el archivo y guardamos partes de las dos versiones[cite: 31].
