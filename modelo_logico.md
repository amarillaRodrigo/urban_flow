
# Modelo Lógico - Sprint 3 - Ejercicio 03

## Entidad Vehiculo

Atributos:
- id_vehiculo (PK)
- patente

## Entidad Radar

Atributos:
- id_radar (PK)
- ubicacion

## Entidad Evidencia

Atributos:
- id_evidencia (PK)
- imagen

## Entidad Multa

Atributos:
- id_multa (PK)
- fecha
- velocidad_detectada
- velocidad_maxima
- exceso_velocidad
- id_vehiculo (FK)
- id_radar (FK)
- id_evidencia (FK, opcional)

## Relaciones

- Un Vehiculo puede tener muchas Multas.
- Una Multa pertenece a un único Vehiculo.
- Un Radar puede generar muchas Multas.
- Una Multa es generada por un único Radar.
- Una Multa puede tener una Evidencia (opcional).
