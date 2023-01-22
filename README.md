# Pyspark

## Que es Spark?

Spark es un framework de computación en clúster que permite a los usuarios ejecutar aplicaciones en clúster de manera más rápida y eficiente.
Spark ha sido la evolucion a hadoop, ya que spark es mucho mas rapido que hadoop, y permite realizar operaciones en memoria, mientras que hadoop realiza operaciones en disco.

Algunas de las características de Spark son:

- **Rápido**: Spark es 100 veces más rápido que Hadoop MapReduce para operaciones en memoria y 10 veces más rápido para operaciones en disco.
- **Fácil de usar**: Spark proporciona una API de alto nivel para los lenguajes de programación Scala, Java, Python y R, y un motor de ejecución optimizado para realizar operaciones en memoria.
- **General**: Spark puede ejecutar aplicaciones de procesamiento de datos, análisis de datos, aprendizaje automático y mucho más.
- **Escalable**: Spark puede ejecutar aplicaciones en clúster con miles de nodos.
- **Robusto**: Spark es tolerante a fallos y puede ejecutar aplicaciones con miles de tareas fallidas.
- **Programación funcional**: Spark proporciona una API funcional para programar aplicaciones de forma declarativa y concisa.

## Que es Pyspark?

PySpark es una interfaz de Python para Spark. Es una API de Python para Spark que permite a los usuarios utilizar Spark con Python. PySpark es una capa de abstracción sobre Spark Core que permite a los usuarios trabajar con Spark usando el lenguaje de programación Python.

## Como se procesa un programa en Spark?

Tenemos 3 componentes principales en Spark:

- **Driver**: Es el proceso que ejecuta el programa principal y crea las tareas.
- **Resourcemanager**: Es el proceso que administra los recursos del clúster.
- **Worker**: Es el proceso que ejecuta las tareas.

## Estructura de Spark

- **Spark Core API**: Es la API principal de Spark. Proporciona la funcionalidad de programación de Spark y permite a los usuarios crear RDDs, acumuladores y variables de transmisión.
- API's lenguajes de programacion
  - Python
  - Java
  - SQL
  - R
  - Scala
- **Streaming**: Es una API de Spark que permite a los usuarios procesar datos en tiempo real.
- **MLlib**: Es una API de Spark que proporciona algoritmos de aprendizaje automático y herramientas de aprendizaje automático comunes.
- **GraphX**: Es una API de Spark que proporciona una API de gráficos para trabajar con datos de gráficos.
- **Spark SQL**: Es una API de Spark que proporciona soporte para SQL y datos estructurados.

Documentación oficial: https://spark.apache.org/docs/latest/

## Ecosistema amplio

Spark es un proyecto de código abierto que se ejecuta en una comunidad de desarrolladores y usuarios. Spark tiene una amplia gama de bibliotecas y herramientas que se pueden utilizar para crear aplicaciones de Spark.
Ademas de poder integrar herramientas de python como pandas, numpy, matplotlib, etc.

## Tipos de administradores de clúster

- **Standalone**: Es un administrador de clúster simple que se ejecuta en un clúster de Spark. El administrador de clúster se ejecuta en el nodo maestro y se comunica con los nodos de trabajo para administrar los recursos.
- **YARN**: Es un administrador de clúster que se ejecuta en un clúster Hadoop. YARN es el administrador de clúster predeterminado de Spark.
- **Mesos**: Es un administrador de clúster que se ejecuta en un clúster de Apache Mesos. Mesos es un administrador de clúster de código abierto que se puede utilizar para administrar recursos en un clúster.
- **Kubernetes**: Es un administrador de clúster que se ejecuta en un clúster de Kubernetes. Kubernetes es un sistema de orquestación de contenedores de código abierto que se puede utilizar para administrar recursos en un clúster.

## Instalación
[tutorial](Instalacion.md)

## DataFrames en Pyspark

Los DataFrames son estructuras de datos distribuidas en filas y columnas. Los DataFrames son similares a las tablas de bases de datos relacionales o las hojas de cálculo de Excel. Los DataFrames son inmutables, lo que significa que no se pueden cambiar una vez creados. Los DataFrames se pueden crear a partir de archivos de datos existentes o a partir de fuentes de datos existentes.
