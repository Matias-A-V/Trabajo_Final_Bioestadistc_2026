# Trabajo Final: Diseño Experimental y Bioestadística MCBIO-010_2026
**Estudiante:** Matías A. Vergara  
**Fecha de entrega:** 24 de junio de 2026

Este repositorio contiene el código de R del análisis estadístico utilizado para el trabajo final del curso. El estudio evalúa el efecto de la presencia del muérdago (*Desmaria mutabilis*) sobre la diversidad de artrópodos epígeos y su relación de mediación sobre las comunidades de aves insectívoras.

## Estructura del Repositorio
* `TrabajoFinalR.Rmd`: Documento RMarkdown reproducible que contiene generación de datos, la exploración de datos, análisis multivariados (`mvabund`, NMDS) e inferencia.

## Instrucciones para la Reproducción del Análisis
Para ejecutar este código y reproducir la totalidad de las tablas y figuras del informe, siga estos pasos:
1. Clone este repositorio o descargue los archivos en una carpeta local.
2. Abra el archivo `TrabajoFinalR.Rmd` en RStudio (se recomienda trabajar dentro de un Proyecto de RStudio `.Rproj`).
3. Asegúrese de tener instalados los siguientes paquetes ejecutando en la consola:
   `install.packages(c("vegan", "mvabund", "MASS", "tidyverse", 
                   "ggsci", "DHARMa", "patchwork", "ggtext", "knitr"))`
4. Presione el botón **Knit** en RStudio para compilar el documento y generar el reporte HTML automatizado.
