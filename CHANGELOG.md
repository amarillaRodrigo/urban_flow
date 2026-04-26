
## Día 1 - Sprint 1 - Ejercicio 01
- Inicialización del repositorio.
- Creación de la rama `Sprint_1`.
- Creación de la estructura de directorios `urban_flow/data/raw`, 
  `urban_flow/data/interim`, `urban_flow/data/interim/plots` y 
  `urban_flow/data/processed`.
- Adicion del dataset a la carpeta data/raw

## Día 1 - Sprint 1 - Ejercicio 02
#### Análisis del DataSet
- Se analizaron los tipos de datos y la cantidad de valores nulos existentes 
  en el DataSet.

## Día 1 - Sprint 1 - Ejercicio 03 (Continuación)
- Normalización de fechas (relleno con 1932-01-01).
- Normalización de horas (formato 24hs, relleno con 00:00).
- Limpieza de ubicaciones (mayúsculas y remoción de caracteres especiales).
- Normalización de patentes (mayúsculas, remoción de caracteres y gestión 
  de nulos con pd.NA).
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

## Día 4 - Sprint 1 - Ejercicio 05
- Creación del directorio `urban_flow/data/interim/plots`.
- Generación de gráfico de barras de top 10 patentes reincidentes (fines.jpg).
- Generación de gráfico de torta del porcentaje de infracciones por hora 
  (hours.jpg).
- Generación de gráfico de barras horizontales de infracciones por mes 
  (months.jpg).
- Generación de gráfico de líneas de exceso de velocidad promedio por hora 
  (hour.jpg).
- Generación de gráfico de líneas de exceso de velocidad promedio por fecha 
  (date.jpg).
- Reorganización y corrección del historial del CHANGELOG para reflejar el 
  orden cronológico real de los ejercicios y eliminar redundancias.
