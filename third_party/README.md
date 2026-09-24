# Dependencia de sistema de archivos para Windows

`hadoop-bare-naked-local-fs-0.1.0.jar` proviene de
[GlobalMentor Hadoop Bare Naked Local FileSystem](https://github.com/globalmentor/hadoop-bare-naked-local-fs),
versión 0.1.0, distribuida en
[Maven Central](https://repo.maven.apache.org/maven2/com/globalmentor/hadoop-bare-naked-local-fs/0.1.0/).
Licencia Apache 2.0; se incluye una copia en `LICENSE-Apache-2.0.txt`.

La primera celda del notebook lo configura solo en Windows para que Spark pueda
guardar los Parquet y los pipelines sin requerir `winutils.exe`. En otros sistemas
Spark usa su configuración normal.
