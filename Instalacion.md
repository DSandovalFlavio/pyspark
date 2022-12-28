# Instalacion de Pyspark sobre Anaconda en Mac

Para instalar Anaconda en Mac os puedes seguir este [tutorial]('').

Una vez instalado Anaconda creamos un entorno virtual con Python e instalamos Pyspark.

```bash
conda create -n pyspark_env python pyspark
```

Activamos el entorno virtual.

```bash
conda activate pyspark_env
```

Tambien debemos instalar Java para poder ejecutar Pyspark.

```bash
conda install openjdk
```

Por ultimo debemos de instalar findspark que nos permitira ejecutar Pyspark desde Python.

```bash
conda install -c conda-forge findspark
```

Ahora ya podemos ejecutar Pyspark desde Python.
