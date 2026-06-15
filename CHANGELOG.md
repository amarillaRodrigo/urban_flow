## Día 1 - Sprint 3 - Ejercicio 1
- Creación de la rama Sprint_3 a partir de la rama Sprint_2.
- Configuración inicial del entorno de trabajo para el Sprint 3.
- Verificación de acceso a los datasets generados en los sprints anteriores.
- Validación de la estructura de directorios y archivos necesarios para continuar el desarrollo.
- Preparación del repositorio para la incorporación de persistencia y versionado de datos.
## Día 1 - Sprint 3 - Ejercicio 02
- Creación del directorio /content/remote_dvc para simular un repositorio remoto DVC.
- Inicialización de DVC en el proyecto.
- Migración de archivos binarios desde Git hacia DVC.
- Generación de archivos .dvc para el versionado de datasets.
- Configuración del almacenamiento remoto para DVC.
## Día 1 - Sprint 3 - Ejercicio 02
- Creación del directorio /content/remote_dvc para simular un repositorio remoto DVC.
- Inicialización de DVC en el proyecto.
- Migración de archivos binarios desde Git hacia DVC.
- Generación de archivos .dvc para el versionado de datasets.
- Configuración del almacenamiento remoto para DVC.
## Día 1 - Sprint 3 - Ejercicio 03
- Diseño del modelo lógico basado en speeding_fines_image.csv.
- Definición de las entidades Vehículo, Multa, Radar y Evidencia.
- Identificación de atributos principales para cada entidad.
- Modelado de relaciones entre las entidades según las reglas del dominio.
- Se creo un campo de texto y tambien un archivo MD (Markdown), donde se muestra el modelo lógico.
## Día 1 - Sprint 3 - Ejercicio 03
- Diseño del modelo lógico basado en speeding_fines_image.csv.
- Definición de las entidades Vehículo, Multa, Radar y Evidencia.
- Identificación de atributos principales para cada entidad.
- Modelado de relaciones entre las entidades según las reglas del dominio.
- Se creo un campo de texto dentro del colab y tambien un archivo MD (Markdown), donde se muestra el modelo lógico.
## Día 1 - Sprint 3 - Ejercicio 02
- Creación del directorio /content/remote_dvc para simular un repositorio remoto DVC.
- Inicialización de DVC en el proyecto.
- Migración de archivos binarios desde Git hacia DVC.
- Generación de archivos .dvc para el versionado de datasets.
- Configuración del almacenamiento remoto para DVC.
## Día 1 - Sprint 3 - Ejercicio 03
- Diseño del modelo lógico basado en speeding_fines_image.csv.
- Definición de las entidades Vehículo, Multa, Radar y Evidencia.
- Identificación de atributos principales para cada entidad.
- Modelado de relaciones entre las entidades según las reglas del dominio.
- Se creo un campo de texto dentro del colab y tambien un archivo MD (Markdown), donde se muestra el modelo lógico.
## Día 2 - Sprint 3 - Ejercicio 04
- Diseño de las clases con respecto al ejercicio 3
- Creación de los objetos instanciando la clase Multa
- Prueba de la función utilizando la primera línea del csv speeding_fines_imag.csv
## Día 2 - Sprint 3 - Ejercicio 05
- Diseño de la base relacional usando el ORM de SQLAlchemy
## Día 2 - Sprint 3 - Ejercicio 05
- Diseño de la base relacional usando el ORM de SQLAlchemy

## Día 3 - Sprint 3 - Ejercicio 08

* Creación de la base de datos vectorial `patente_vectorial` utilizando ChromaDB.
* Generación de embeddings de imágenes mediante el modelo OpenCLIP.
* Almacenamiento de vectores asociados al identificador de cada vehículo.
* Población de la colección vectorial con las imágenes disponibles del dataset.

## Día 3 - Sprint 3 - Ejercicio 09

* Implementación de la función `buscar_patente_imagen`.
* Generación de embeddings para imágenes de consulta utilizando OpenCLIP.
* Búsqueda por similitud en la base vectorial.
* Integración entre ChromaDB y SQLite para recuperar la información completa del vehículo y la multa asociada.

## Día 3 - Sprint 3 - Ejercicio 10

* Elaboración de conclusiones sobre la integración de bases de datos relacionales y vectoriales.
* Evaluación del uso de embeddings para recuperación de información visual.
* Validación de resultados mediante búsqueda de imágenes de patentes.
