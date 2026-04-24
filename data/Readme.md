
# Urban Flow

## Sprint 1

## Objetivo
Aplicar los conocimientos adquiridos para el versionado de código,
la organización, limpieza del código y la utilización de pandas.

## Introducción y Contexto
La localidad de Vaalserberg de Bélgica cuenta con un sistema de radares
urbanos para la detección de infracciones por exceso de velocidad.
Los registros históricos provienen de sistemas heredados que presentan
errores de formato y faltante de datos generando registros inconsistentes
en el nuevo sistema.

## Conclusión
El dataset contiene registros históricos de multas por exceso de velocidad.
Presentaba datos inconsistentes provenientes del sistema heredado, incluyendo
50 fechas inválidas, 1957 valores nulos en velocidad_maxima y 1002 en
estado_multa. El 26.43% tiene fecha desconocida y el 19.85% hora desconocida.
Se eliminaron outliers con IQR y registros sin infracción real. El dataset
quedó depurado y listo para incorporarse al nuevo sistema.
