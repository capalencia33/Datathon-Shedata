# Análisis de proporción de escuelas ubicadas en zonas rurales que atienden a estudiantes con discapacidad en comparación con aquellas ubicadas en zonas urbanas o mixtas.

Este proyecto corresponde a una propuesta de análisis de datos educativos en el contexto colombiano. Utiliza un enfoque de ciencia de datos para explorar si existen diferencias en la proporción de escuelas con atención a estudiantes con discapacidad según la ubicación geográfica de los establecimientos educativos (zonas rurales vs. urbanas).

## Problema de investigación

¿Las escuelas ubicadas en zonas rurales de la Región Caribe colombiana presentan una menor proporción de atención a estudiantes con discapacidad en comparación con aquellas ubicadas en zonas urbanas o mixtas?

## Hipótesis de investigación
**En la Región Caribe colombiana, se presentó una baja proporción de escuelas ubicadas en zonas rurales que atienden a estudiantes con discapacidad en comparación con aquellas ubicadas en zonas urbanas o mixtas.**

## Hipótesis del modelo

**Hipótesis nula (H₀):** La proporción de escuelas con atención a estudiantes con discapacidad es igual en zonas rurales y urbanas.  
**Hipótesis alternativa (H₁):** La proporción de escuelas con atención a estudiantes con discapacidad es menor en zonas rurales que en urbanas.

## Enfoque metodológico

1. **Carga y limpieza de datos:** Se utiliza un dataset de establecimientos educativos.
2. **Análisis exploratorio (EDA):** Distribución por departamentos, zonas y atención a la discapacidad.
3. **Creación de variables dummy y categorización por zona.**
4. **Visualizaciones:** Gráficos de barras y tablas de contingencia.
5. **Pruebas estadísticas:** Comparación de proporciones entre zonas.

## Estructura del proyecto

- `hackaton.ipynb`: Notebook principal con el análisis.
- `dashboard.pbix`: Informe interactivo en Power BI con visualización de los resultados clave.
- `README.md`: Este archivo, con la descripción del proyecto.

## Resultados esperados

Se espera encontrar evidencia de desigualdad territorial en el acceso a servicios educativos inclusivos, particularmente en zonas rurales.

## Requerimientos

- Python 3.9+
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook
- Power BI Desktop (para visualizar el `.pbix`)
