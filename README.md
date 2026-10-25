# Análisis de la salud adolescente a nivel mundial (2000-2021)

**Para ver el informe completo, entrar en este enlace (no se visualiza desde los archivos del repositorio):**
[https://nicoleortegaojeda15.github.io/analisis-salud-adolescente-2000-2021/](https://nicoleortegaojeda15.github.io/analisis-salud-adolescente-2000-2021/)

---

## Descripción

Análisis exploratorio y visualización de datos en **R** sobre la salud de la población adolescente por países y continentes, con gráficos interactivos y un modelo de predicción de series temporales hasta 2040.

Proyecto académico individual de la asignatura **Análisis Exploratorio y Visualización de Datos** (Grado en Ciencia e Ingeniería de Datos, ULPGC, 2024).

## Objetivos

- Evaluar las desigualdades regionales en indicadores clave de salud adolescente.
- Analizar correlaciones entre los indicadores de salud.
- Relacionar el análisis con los Objetivos de Desarrollo Sostenible (ODS 3, 5 y 10).
- Proyectar la evolución de la mortalidad adolescente hasta 2040.

## Datos

- **Indicadores de salud adolescente por país:** UNICEF, *State of the World's Children 2023* (Tabla 5).
- **Serie temporal de muertes adolescentes por continente (2000-2022):** dataset construido para este estudio a partir de datos de UNICEF.

## Contenido del análisis

- Países con mayor tasa de mortalidad adolescente y comparación por continentes.
- Consumo de alcohol y tabaco por continente y sexo.
- Maternidad adolescente y salud sexual.
- Correlaciones entre indicadores (matriz de correlación y diagramas de dispersión).
- Evolución de las muertes adolescentes desde el año 2000 y predicción hasta 2040 con modelos ETS.

## Cuadro de mandos

El proyecto incluye además un cuadro de mandos interactivo (Shiny y flexdashboard) con mapa por indicador, comparador de variables, matriz de correlación, análisis de componentes principales (PCA) y predicciones. Su código está en la carpeta `trabajo` (`dashboard.Rmd`), pero **no se puede ejecutar fuera de la universidad**, ya que requiere conexión a la VPN de la universidad.

## Tecnologías

R, RMarkdown, tidyverse, ggplot2, plotly, highcharter, GGally, fpp3 (tsibble y fable), Shiny, flexdashboard.

## Cómo reproducirlo

1. Abre `Proyecto_Personal.Rmd` en RStudio.
2. Instala los paquetes necesarios.
3. Deja los archivos `.xlsx` en la misma carpeta que el `.Rmd` y pulsa **Knit** para generar el informe HTML.
