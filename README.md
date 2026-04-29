# Guía básica de Git y GitHub

## Introducción

**Git** es un sistema de control de versiones que permite registrar y gestionar los cambios en proyectos de desarrollo.

**GitHub** es una plataforma online que permite almacenar repositorios Git y colaborar con otros desarrolladores.

## Comandos básicos de Git

- `git init` → inicializa un repositorio
- `git add .` → añade archivos al área de preparación
- `git commit -m "mensaje"` → guarda los cambios en el repositorio
- `git status` → muestra el estado del repositorio
- `git log` → muestra el historial de commits

## Flujo de trabajo

1. Crear repositorio
2. Añadir archivos
3. Hacer commit
4. Subir a GitHub

## Ejemplo práctico

```bash
mkdir mi-proyecto
cd mi-proyecto
git init
git add .
git commit -m "primer commit"

## Errores comunes

- Olvidar hacer commit
- No añadir archivos con git add
- No sincronizar con GitHub