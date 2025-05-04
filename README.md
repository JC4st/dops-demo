

# DOPS Demo: Evaluación Formativa y Sumativa en Procedimientos Clínicos

Este repositorio contiene una versión demostrativa de una aplicación **Shiny** desarrollada para recolectar, visualizar y analizar observaciones estructuradas directas (DOPS, por sus siglas en inglés) en un entorno clínico de posgrado.

## 🔍 Objetivo

Facilitar el uso educativo de DOPS mediante una herramienta digital que:

- Permita el registro estructurado de evaluaciones formativas y sumativas.
- Genere reportes automáticos por ítem, procedimiento, evaluador y estudiante.
- Calcule indicadores de confiabilidad (como el ICC).
- Ofrezca retroalimentación visual para apoyar el aprendizaje.

## 📁 Estructura del repositorio

```
dops-demo/
  ├── README.md            # Este archivo
  ├── app/                 # Código de la aplicación Shiny
  ├── data/                # Datos simulados (e.g. dops_simulada.csv)
  ├── scripts/             # Análisis estadístico y visualizaciones
  ├── docs/                # Sitio web generado con Quarto
  ├── learn/               # Guías y recursos educativos
  └── .gitignore           # Archivos a excluir del control de versiones
```

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

# DOPS Demo – Evaluación clínica digital para procedimientos

Este proyecto ofrece una herramienta interactiva para evaluar habilidades procedimentales usando el método DOPS (Direct Observation of Procedural Skills).

🩺 **¿Qué es?**  
Una plataforma digital desarrollada en R y Shiny, con almacenamiento en Supabase, para registrar observaciones clínicas de procedimientos en tiempo real.

🎯 **Objetivos del proyecto**
1. Mostrar una demostración funcional para otros docentes clínicos.
2. Compartir el código y documentación para que pueda replicarse.
3. Enseñar cómo analizar los datos recolectados para monitorear desempeño y confiabilidad.

🔍 **Tecnologías utilizadas**
- R + Shiny para la aplicación
- Supabase como base de datos
- Quarto para documentar y publicar el proyecto
- GitHub Pages para mostrarlo públicamente

📂 **Explora el proyecto**
- [`/docs`](./docs): Sitio web generado (para GitHub Pages)
- [`/R`](./R): Código de análisis en R
- [`/sql`](./sql): Consultas y estructura de la base de datos Supabase
- [`/tutorials`](./tutorials): Guías paso a paso para docentes

🌐 **Acceso rápido**
- App Shiny: [necardio.shinyapps.io/dops](https://necardio.shinyapps.io/dops/)
- Repositorio: [github.com/JC4st/dops-demo](https://github.com/JC4st/dops-demo)

👨‍🏫 **¿Eres docente clínico?**
- Revisa la [Guía Docente](docs/guia-docente.html)
- Mira ejemplos de [análisis de desempeño](docs/analisis.html)

🔧 ¿Quieres usar esto en tu especialidad?  
Contáctame o explora cómo adaptarlo.

Este proyecto hace parte de un desarrollo educativo llevado a cabo en el contexto del máster en Clinical Education de la Universidad de Edimburgo.