 
## Dia 1 - Sprint 1 - Ejercicio 01
- Inicialización del repositorio.
- Creación de la rama `Sprint_1`.
- Creación de la estructura de directorios `urban_flow/data/raw`, `urban_flow/data/interim`, `urban_flow/data/interim/plots` y `urban_flow/data/processed`.
- Adicion del dataset a la carpeta data/raw

## Día 1 - Sprint 1 - Ejercicio 02
#### Análisis del DataSet
- Se analizaron los tipos de datos y la cantidad de valores nulos existentes en el DataSet.

## Día 1 - Sprint 1 - Ejercicio 03 (Continuación)
- Normalización de fechas (relleno con 1932-01-01).
- Normalización de horas (formato 24hs, relleno con 00:00).
- Limpieza de ubicaciones (mayúsculas y remoción de caracteres especiales).
- Normalización de patentes (mayúsculas, remoción de caracteres y gestión de nulos con pd.NA).
- Eliminación de registros con valores nulos en columnas relevantes.
- Detección y eliminación de outliers en velocidad registrada.
- Creación de columnas de exceso de velocidad real y ajustado (5%).
- Filtrado de registros sin infracciones.

- Guardado del dataset limpio en `urban_flow/data/interim/speeding_fines.csv`.

## Día 2 - Sprint 1 - Ejercicio 04
- Creación de la clase `FineAnalyzer` para el análisis estadístico de 
  infracciones de tránsito.
- Implementación de encapsulamiento (`self.__df`) para proteger el 
  DataFrame de datos limpios.
- Desarrollo del método `top_patentes` para obtener el ranking top 5 
  de las patentes más multadas.
- Desarrollo del método `top_horarios` para obtener el ranking top 5 
  de los horarios con más multas.
- Creación de métodos para calcular el exceso de velocidad promedio y 
  el exceso real promedio.
- Implementación de `multas_por_ubicacion` para infracciones agrupadas 
  y ordenadas alfabéticamente.
## Día 3 - Sprint 1 - Ejercicio 06
- Cálculo del porcentaje de infracciones con fecha desconocida (1932-01-01).
- Cálculo del porcentaje de infracciones con hora desconocida (00:00).
## Día 4 - Sprint 1 - Ejercicio 07
- Redacción de la conclusión del dataset en el archivo Readme.md.

## Día 3 - Sprint 1 - Ejercicio 06

### Objetivo

Analizar datos de infracciones y representarlos con gráficos, exportando cada resultado en la carpeta correspondiente.

### Introducción y contexto

Se trabajó con datos de infracciones usando pandas y matplotlib. 
Se generaron distintos gráficos: ranking de patentes reincidentes (fines.jpg), porcentaje por hora (hours.jpg), 
infracciones por mes (months.jpg), y exceso de velocidad promedio por hora (hour.jpg) y por fecha (date.jpg).

### Conclusión

Se logró transformar los datos en visualizaciones claras que permiten entender mejor el comportamiento de las infracciones. 
A partir de los gráficos, se pueden identificar patrones como los horarios con mayor actividad, los meses con más infracciones y tendencias en el exceso de velocidad. 
Esto facilita el análisis y sirve como base para futuras mejoras o decisiones dentro del proyecto.

## Día 4 - Sprint 1 - Ejercicio 06

### Objetivo

Analizar datos de infracciones y representarlos con gráficos, exportando cada resultado en la carpeta correspondiente.

### Introducción y contexto

Se trabajó con datos de infracciones usando pandas y matplotlib. 
Se generaron distintos gráficos: ranking de patentes reincidentes (fines.jpg), porcentaje por hora (hours.jpg), 
infracciones por mes (months.jpg), y exceso de velocidad promedio por hora (hour.jpg) y por fecha (date.jpg).

### Conclusión

Se logró transformar los datos en visualizaciones claras que permiten entender mejor el comportamiento de las infracciones. 
A partir de los gráficos, se pueden identificar patrones como los horarios con mayor actividad, los meses con más infracciones y tendencias en el exceso de velocidad. 
Esto facilita el análisis y sirve como base para futuras mejoras o decisiones dentro del proyecto.

## Día 4 - Sprint 1 - Ejercicio 06

### Objetivo

Analizar datos de infracciones y representarlos con gráficos, exportando cada resultado en la carpeta correspondiente.

### Introducción y contexto

Se trabajó con datos de infracciones usando pandas y matplotlib.
Se generaron distintos gráficos: ranking de patentes reincidentes (fines.jpg), porcentaje por hora (hours.jpg),
infracciones por mes (months.jpg), y exceso de velocidad promedio por hora (hour.jpg) y por fecha (date.jpg).

### Conclusión

Se logró transformar los datos en visualizaciones claras que permiten entender mejor el comportamiento de las infracciones.
A partir de los gráficos, se pueden identificar patrones como los horarios con mayor actividad, los meses con más infracciones y tendencias en el exceso de velocidad.
Esto facilita el análisis y sirve como base para futuras mejoras o decisiones dentro del proyecto.
