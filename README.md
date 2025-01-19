En esta evaluación se han explorado, limpiado y transformado dos archivos de datos (.csv) que contienen información sobre los clientes canadienses adscritos al programa de fidelización de una compañía aérea.

Se ha automatizado la primera fase del proceso de transformación y limpieza de datos para crear un archivo .csv combinado llamado 'datos_limpios_unidos'.

Se han utilizado diferentes herramientas de visualización para responder a algunas cuestiones relacionadas con el comportamiento de los clientes y su distribución por sexo, estado civil o lugar de procedencia, entre otros.

Y se ha realizado una prueba de hipótesis para comprobar si existe o no una relación entre el número de vuelos reservados y el nivel de estudios de los clientes.

## Contenido

1. [Preparación de Datos](#preparación-de-datos)
2. [Análisis Descriptivo](#análisis-descriptivo)
3. [Visualización de Datos](#visualización-de-datos)
4. [Prueba Estadística](#prueba-estadística)

### Exploración y Limpieza de Datos

- **Carga de datos**: Los datos se cargan desde dos archivo CSV.
- **Analisis y Limpieza de datos**: Se eliminan duplicados y se conviertes tipos en los datos (por ejemplo, fechas).

  ### Filtrado de Datos

- **Filtrado temporal**: Se filtran los clientes activos durante el periodo de enero 2017 a diciembre 2018.
- **Cálculo de fechas**: Se crean nuevas columnas para fechas combinando año, mes y día.
## Análisis Descriptivo

### Estadísticas Descriptivas

- **Cálculo de estadísticas**: Se agrupan los datos por nivel educativo y se calculan estadísticas descriptivas (media, mediana, desviación estándar, percentiles) del número de vuelos reservados.

### Comparación de Grupos

- **Agrupación**: Se dividen los niveles educativos en grupos de alto, medio y bajo, y se calcula la media y desviación estándar del número de vuelos reservados para cada grupo.

## Prueba Estadística

### Evaluación de Normalidad

- **Prueba de Shapiro-Wilk**: Se evalúa si los datos se ajustan a una distribución normal.

### Alternativa para Datos No Normales

- **Prueba de Mann-Whitney U**: Se utiliza si los datos no siguen una distribución normal para comparar las medianas entre los grupos de alto y bajo nivel educativo.

  ## Visualización de Datos

### Gráficos Generales

- **Distribución por Provincia**: Gráfico de barras mostrando la distribución de clientes por provincia.
- **Salario por Nivel Educativo**: Gráfico de barras que muestra el salario promedio por nivel educativo.
- **Número de Vuelos Reservados**: Gráfico de líneas que muestra la evolución mensual de los vuelos reservados.
- **Relación entre Distancia y Puntos Acumulados**: Gráfico de dispersión con una línea de regresión para evaluar la relación entre distancia y puntos acumulados.

  
