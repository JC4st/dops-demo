---
title: "README"
editor_options:
  markdown:
    mode: gfm
---

# DOPS Demo: Evaluación Formativa y Sumativa en Procedimientos Clínicos

Este repositorio contiene una versión demostrativa de una aplicación **Shiny** desarrollada para recolectar, visualizar y analizar observaciones estructuradas directas (DOPS, por sus siglas en inglés) en un entorno clínico de posgrado.

## 🔍 Objetivo

Facilitar el uso educativo de DOPS mediante una herramienta digital que:

- Permita el registro estructurado de evaluaciones formativas y sumativas.
- Genere reportes automáticos por ítem, procedimiento, evaluador y estudiante.
- Calcule indicadores de confiabilidad (como el ICC).
- Ofrezca retroalimentación visual para apoyar el aprendizaje.

## 📁 Estructura del repositorio
  
dops-demo/
  ├── README.md            # Este archivo
  ├── app/                 # Código de la aplicación Shiny
  ├── data/                # Datos simulados (e.g. dops_simulada.csv)
  ├── scripts/             # Análisis estadístico y visualizaciones
  ├── docs/                # Sitio web generado con Quarto
  ├── learn/               # Guías y recursos educativos
  └── .gitignore           # Archivos a excluir del control de versiones
  

## 🧪 Datos simulados

Se incluyen datos de ejemplo (`data/dops_simulada.csv`) con:

- 10 estudiantes ficticios
- 3 procedimientos (CVC, Biopsia, POCUS)
- 3 evaluadores
- Evaluaciones sumativas con 12 ítems (puntajes del 1 al 5)

Estos datos pueden ser usados para explorar la app sin riesgo y realizar análisis de fiabilidad, progresión y consistencia.

## 🌐 Documentación

La documentación completa del proyecto está disponible en el sitio web generado con Quarto (en construcción).

## 👨‍🏫 Público objetivo

- Docentes clínicos interesados en métodos de evaluación basados en el lugar de trabajo.
- Programas de residencia o fellowships en medicina.
- Educadores que deseen implementar herramientas digitales para retroalimentación estructurada.

## 🛠️ Tecnologías usadas

- R + Shiny
- Supabase (opcional para base de datos real)
- Quarto + GitHub Pages (documentación)
- GitHub Education tools

## 📄 Licencia

MIT License

---

Este proyecto hace parte de un desarrollo educativo llevado a cabo en el contexto del máster en Clinical Education de la Universidad de Edimburgo.