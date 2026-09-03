# Proyecto-ENHIGUR
Análisis estadístico descriptivo del ingreso y gasto de consumo de los hogares de la región Sierra - Ecuador, usando datos de la ENIGHUR2025 (INEC). Proyecto académico en R.
# Análisis del Ingreso y Gasto de Consumo en la Región Sierra - Ecuador

Proyecto de la materia Introducción a la Estadística, basado en datos de la 
ENIGHUR [2024/2025] (Encuesta Nacional de Ingresos y Gastos de los Hogares 
Urbanos y Rurales, INEC).

## Autores
- Jonathan Paute
- Carlos Morales

## Pregunta de investigación
¿Cómo cambia la distribución del gasto de consumo de los hogares de la región 
Sierra a medida que aumenta su nivel de ingreso corriente per cápita?

## Fuente de datos
Base de datos descargada del portal oficial del INEC (ENIGHUR [2024/2025]).

## Metodología
- Análisis estadístico descriptivo en R: medidas de tendencia central, 
  dispersión, análisis por deciles de ingreso y análisis bivariado 
  (sexo del jefe de hogar / percepción de ingresos).
- Para el cálculo y visualización de deciles se utilizó un **script auxiliar 
  proporcionado por técnicos del INEC**, replicando la metodología oficial 
  con la que la institución construye sus propios deciles.

## Hallazgos principales
- El ingreso corriente per cápita en la Sierra es 14,5% mayor al promedio nacional.
- El gasto de consumo aumenta casi 5 veces del Decil 1 al Decil 10.
- Se observa un patrón consistente con la Ley de Engel: el gasto en necesidades 
  básicas pierde peso relativo a medida que sube el ingreso.
- Existe una brecha de ingreso y de participación laboral por sexo del 
  jefe/perceptor de hogar.

## Contenido del repositorio
- `script.Rmd` — Código completo del análisis en R Markdown
- `script_deciles_inec.R` — Script auxiliar del INEC usado para el cálculo de deciles
- `presentacion.pptx` — Presentación final del proyecto
- `graficos/` — Gráficos generados
