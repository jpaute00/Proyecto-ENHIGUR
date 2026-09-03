# Análisis del Ingreso y Gasto de Consumo en la Región Sierra - Ecuador

Proyecto de la materia Introducción a la Estadística, basado en datos de la 
ENIGHUR (Encuesta Nacional de Ingresos y Gastos de los Hogares Urbanos y 
Rurales, INEC), descargados desde el portal oficial del INEC.

## Autores
- Jonathan Paute
- Carlos Morales

## Pregunta de investigación
¿Cómo cambia la distribución del gasto de consumo de los hogares de la región 
Sierra a medida que aumenta su nivel de ingreso corriente per cápita?

## Fuente de datos
Base de datos oficial de la ENIGHUR, descargada del portal del INEC 
(Instituto Nacional de Estadística y Censos, Ecuador).

## Metodología
- Análisis estadístico descriptivo en R: medidas de tendencia central, 
  dispersión, análisis por deciles de ingreso y análisis bivariado 
  (sexo del jefe de hogar / percepción de ingresos).
- Para el cálculo de deciles se utilizó un **script auxiliar proporcionado 
  por técnicos del INEC**, replicando la metodología oficial con la que la 
  institución construye sus propios deciles.
- Se aplicó el marco teórico de la **Ley de Engel** para analizar cómo 
  cambian las prioridades de gasto de los hogares según su nivel de ingreso.

## Hallazgos principales
- El ingreso corriente per cápita en la Sierra es 14,5% mayor al promedio nacional.
- El gasto de consumo aumenta casi 5 veces del Decil 1 al Decil 10.
- Se observa un patrón consistente con la Ley de Engel: el gasto en alimentos 
  y vivienda pierde peso relativo a medida que sube el ingreso, mientras 
  educación y transporte ganan participación.
- Existe una brecha de ingreso y de participación laboral por sexo del 
  jefe/perceptor de hogar.

## Contenido del repositorio
- `Pro_Est/proyecto_introduccion_a_la_estadistica.Rmd` — Código completo del 
  análisis en R Markdown
- `Pro_Est/proyecto_introduccion_a_la_estadistica.pdf` — Reporte final generado
- `Scripts auxiliares/Deciles.R` — Script auxiliar del INEC para el cálculo 
  de deciles
- `Datos/Bases_trabajo.RData` — Base de datos utilizada para el análisis
- `Pro_Est/bivariado1_sierra.xlsx` — Tabla de análisis bivariado (Sierra)
- `Pro_Est/tabla_resumen_sierra_divisiones_consumo.xlsx` — Resumen de gasto 
  por divisiones de consumo (Sierra)
- `Pro_Est/tabla_resumen_amazonia_divisiones_consumo.xlsx` — Resumen de gasto 
  por divisiones de consumo (Amazonía)
- `Pro_Est/tabla_resumen_amazonia_gasto.xlsx` — Resumen de gasto (Amazonía)
- `Pro_Est/tabla_resumen_deciles_alimentacion.xlsx` — Resumen de gasto en 
  alimentación por deciles
- `Proyecto de Introducción a la Estadística final (2).pptx` — Presentación 
  final del proyecto

## Herramientas
R, RStudio, ggplot2 (u otras librerías que hayas usado)
