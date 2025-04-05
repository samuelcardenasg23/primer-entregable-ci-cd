# Primer Entregable CI/CD - GitHub Actions

Este repositorio contiene el primer entregable para el curso de CI/CD de la Especialización en Desarrollo de Software en EAFIT.

## Descripción

El proyecto implementa un flujo de trabajo básico utilizando GitHub Actions que realiza las siguientes tareas:

- Imprime un mensaje personalizado
- Muestra la fecha y hora actual del sistema
- Ejecuta un script de Python que muestra información del sistema operativo

## Estructura del Proyecto

- `.github/workflows/my_workflow.yml`: Configuración del workflow de GitHub Actions
- `my_script.py`: Script de Python que muestra información del sistema

## Configuración del Workflow

El workflow está configurado para ejecutarse en los siguientes eventos:
- Push a la rama main
- Pull requests a la rama main
- Manualmente mediante workflow_dispatch

## Ejecución

El workflow se ejecuta automáticamente cuando ocurren los eventos configurados, o puede ser iniciado manualmente desde la pestaña "Actions" en GitHub.

## Tecnologías Utilizadas

- GitHub Actions
- Python 3.13
- Shell scripting básico