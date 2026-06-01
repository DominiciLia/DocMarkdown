# Guía de Instalación de Git en Windows

![Foto logo git](https://img.icons8.com/ios_filled/1200/git.jpg)

## PORTADA 
+ **Institución:** CAFAM
+ **Asignatura:** Administración de Base de Datos
+ **Tema:** Guía de Instalación y Uso Básico de Git en Windows
+ **Estudiante:** Lia K. Torres Dominici
+ **Profesor:** Victor Recio
+ **Fecha:** 1/6/2026

## Índice

1. **Introducción**
2. **¿Qué es Git?**
3. **Instalación**
4. **Comandos básicos**
5. **Conclusiones**

### --- ★꩜ Introducción ꩜★ ---
Git es un sistema de control de versiones utilizado para gestionar cambios en proyectos de software. Permite registrar modificaciones en archivos, trabajar de forma colaborativa y mantener un historial completo de los cambios realizados. Actualmente es una de las herramientas más importantes en el desarrollo de software y es utilizada por millones de desarrolladores en todo el mundo.

### --- ★꩜ ¿Qué es Git? ꩜★ ---
Git es un software de control de versiones distribuido creado por Linus Torvalds en 2005. Su objetivo principal es facilitar el seguimiento de cambios en proyectos, permitiendo que varias personas trabajen simultáneamente sin perder información.

#### ★ Características principales ★
+ Gratuito y de código abierto.
+ Permite trabajar en equipo.
+ Mantiene un historial de cambios.
+ Facilita la recuperación de versiones anteriores.
+ Se integra con plataformas como GitHub.

---

## ★꩜ Instalación ꩜★ 

**Para instalar Git en Windows se deben seguir los siguientes pasos:**

1. Acceder al sitio oficial de Git.
2. Descargar el instalador correspondiente al sistema operativo.
3. Ejecutar el archivo descargado.
4. Seguir las instrucciones del asistente de instalación.
5. Verificar que Git se haya instalado correctamente.

#### Verificación de la instalación

```
 git --version
```

#### Enlace oficial para instalar

+ [Página Oficial para instalar](https://git-scm.com/install/)

## Comandos básicos

**Algunos de los comandos más utilizados en Git son:**

|  COMANDO |  Descripción |
| ---------- | ---------- |
| git init | Crea un repositorio local |
| git status  | Muestra el estado del proyecto |
| git add | Agrega archivos al área de preparación|
| git commit -m ""  | Guarda cambios realizados  |
| git pull | Descarga cambios del repositorio remoto  |
| git push | Envía cambios al repositorio remoto |

---
> **Nota:** Estos son unos pocos de los mas utilizados, es recomendable investigar más a fondo para encontrar otros comando utiles. 

---

## Ejemplo sencillo

```bash
`   # Inicializar un repositorio
    git init

    # Ver el estado actual
    git status

    # Agregar archivos
    git add .

    # Crear un commit
    git commit -m "Primer commit"

    # Conectar con GitHub
    git remote add origin https://github.com/usuario/repositorio.git

    # Subir cambios
    git push -u origin main
```
---

## --- ★꩜ Conclusiones ꩜★ ---

Git es una herramienta fundamental para el desarrollo de software moderno debido a su capacidad para gestionar versiones y facilitar el trabajo colaborativo. Su instalación es sencilla y sus comandos básicos permiten organizar proyectos de manera eficiente. Aprender a utilizar Git proporciona una base sólida para trabajar con repositorios y plataformas como GitHub, convirtiéndose en una habilidad esencial para cualquier estudiante o profesional del área tecnológica.