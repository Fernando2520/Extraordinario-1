# Extraordinario-1

Big Data : El concepto básico responde a datos lo suficientemente variados, grandes y generados muy rápidamente y a partir de diferentes fuentes, pero que no pueden ser procesados o gestionados por métodos convencionales fácilmente,se desarrollan continuamente y en tiempo real.


Datos estructurados: Es información que normalmente se encuentra en la mayoría de las bases de datos. Pueden ser fácilmente ordenados y procesados por todas las herramientas de minería de datos.

Datos no estructurados : En su definición más básica, simplemente significa cualquier forma de datos que no encajen fácilmente en un modelo relacional o conjunto de tablas de base de datos no estructuradas.

Datos almacenados : Son los datos que se almacenan en una base de datos donde se puede verificar su registro y se puede analizar.

Movimiento de datos : Son datos que se transmiten en una red. Además, se almacenan en diferentes fuentes.

Análisis de datos : El análisis de datos es un proceso que implica inspeccionar, limpiar y transformar datos para resaltar información útil, sugerir conclusiones y apoyo en la toma de decisiones.

Ingeniería de datos y Cientificos de datos : Los ingenieros de datos requieren habilidades en una serie de disciplinas técnicas. Estos incluyen lenguajes de scripting (como LINUX y Python), habilidades de programación orientadas a objetos (particularmente Java y Scala), y por supuesto SQL y cómo varía la sintaxis entre diferentes aplicaciones. Científico de datos, a diferencia del ingeniero, no participa activamente en el proceso de adquisición y administración de los datos ya han pasado por un proceso de limpieza, que garantiza su validez (se han eliminado, los fallos y que han sido detectados por el ingeniero) y, por lo tanto, el científico se dedicará a desarrollar  programas analíticos y sistemas de aprendizaje automático (Machine Learning y Deep Learning), así como métodos estadísticos para preparar datos para su uso en modelos predictivos y prescriptivos. 

Git es un software de control de versiones diseñado por Linus Torvalds, pensando en la eficiencia y la confiabilidad del mantenimiento de versiones de aplicaciones cuando estas tienen un gran número de archivos de código fuente.
Creamos un nuevo repositorio vacío.
Creamos un nuevo fichero fichero-1.txt dentro del repositorio. Nuestro VCS guardará que acabamos de crear un fichero.
Editamos el fichero-1.txt y le añadimos texto. Nuestro VCS guardará la nueva versión del fichero.
Añadimos un segundo fichero fichero-2.txt y un directorio llamado carpeta. De nuevo, el VCS guardará estos cambios.
Borramos el fichero-1.txt. ¿Y ahora? El VCS se apunta que hemos borrado ese fichero y lo elimina.

A diferencia de GitHub trabaja en línea con los repositorios que usa Git. Para ello necesitamos lo siguientes requisitos antes de poder integrar GitHub con nuestro repositorio local:

1.- Tendremos que instalar Git.
2.- Tenemos que crear una cuenta en [GitHub].
3.- Crearemos un nuevo repositorio en GitHub.
4.- Configuraremos nuestro git para usar el repositorio de GitHub que hemos creado.

Arquitectura Lambda: en una arquitectura lambda, la idea es implementar sistemas de información que combinen las modalidades de procesamiento de datos: por lotes y flujo. Esto nos da lo mejor de dos mundos, ya que el modo por lotes nos da un alcance completo y fiable, mientras que el modo nos da datos en línea para tomar decisiones instantáneas.

Arquitectura Kappa: Es un patrón de arquitectura de software. En lugar de utilizar una base de datos relacional como SQL o un almacén de clave-valor como Cassandra, el almacén de datos canónico en un sistema de arquitectura Kappa es un registro inmutable, simplemente anexar. Desde el registro, los datos se transmiten a través de un sistema informático y se introducen en almacenes auxiliares para servir.
La diferencia de Lambda: esta arquitectura se caracteriza por utilizar diferentes capas para el procesamiento por lotes y el streaming.
Kappa: A diferencia de lambda, su propuesta es eliminar la capa por lotes dejando solo la capa de streaming.

Docker Containers
Docker es una de las plataformas de contenedorización que se pueden usar para crear y ejecutar contenedores. Las máquinas virtuales son lentas y requieren mucho tiempo para arrancar, por lo que se utilizan contenedores que son rápidos y se inician rápidamente, ya que utiliza el sistema operativo host y comparte las bibliotecas relevantes.

Tipos de graficos para visualizar datos : La visualización de datos es la representación gráfica de información y datos. Al utilizar elementos visuales como cuadros, gráficos y mapas, las herramientas de visualización de datos proporcionan una manera accesible de ver y comprender tendencias, valores atípicos y patrones en los datos. Son los siguientes: 
Gráfico de barras
Diagrama de cajas y bigotes
Gráficos de densidad
Gráfico de anillos
Histograma

Datos Cloud y Fog : Datos Cloud este tipo de uso eficaz de los sistemas Cloud para Big Data permite a las empresas ofrecer sus servicios en la nube en tres modalidades en función de las necesidades de uso: infraestructura (IaaS), preconfigurado (PaaS) y software (SaaS). Podemos hacer el procesamiento y análisis de datos de una manera transparente con respecto a los detalles de la infraestructura.
Datos fog 
La computación de niebla se refiere así a la infraestructura informática cerca a las fuentes de datos, en las que se producen muchas conexiones con poco ancho de banda y mínima transmisión de datos. La computación de niebla en contraste permite un solo dispositivo, comúnmente llamado puerta de enlace, o procesar datos que provienen de múltiples fuentes.

Exploratory Data Analysis (EDA) EDA: Es un enfoque para analizar conjuntos de datos para las características principales con métodos visuales. Se puede usar un modelo estadístico, pero principalmente EDA es para ver que los datos nos decir más posible de la tarea de modelado formal o prueba de sistencia. Se aplica utilizando cualquierado de las maneras siguientes:

Medición y dispersión: Aplica la estadistica descriptiva, usa las medidas de tendencia central que son media, mediana y moda. Utiliza graficas.
Comparación: Aplica la estadistica inferencial, us comparaciones visuales a través de gráficas como la campana de Gauss o nubes de dispersión.

Mapreduce
Map Reduce es un entorno de programación que consiste en distribuir una gran cantidad de datos en muchos clústeres y procesarlos más rápido.

Apache Spark
Spark es un motor de procesamiento de datos distribuido que le permite manejar grandes volúmenes de información.

Los principios de los datos limpios: 

Cada columna es una variable.
Cada renglón es una observación .
Cada celda es un único valor.

Datos limpios son datos que facilitan las tareas del análisis de datos:

Visualización: Resúmenes de datos usando gráficas, análisis exploratorio, o presentación de resultados.

Manipulación: Manipulación de variables como agregar, filtrar, reordenar, transformar.

Modelación: Ajustar modelos es sencillo si los datos están en la forma correcta.

Codigo de bash shell 

1.- cat fich1 [...fichN]	Concatena y muestra un archivo	cat /etc/passwd

2.- cd [dir]	Cambia de directorio	cd /tmp

3.- chmod permisos fich	Cambia los permisos de un archivo	chmod +x miscript

4.- chown usuario:grupo fich	Cambia el dueño un archivo	chown nobody miscript

5.- cp fich1...fichN dir Copia archivos	cp foo foo.backup

6.- pwd	Muestra la ruta del directorio actual	pwd

7.- rm fich	Borra un fichero	rm foo.c

8.- rm -r dir	Borra todo un directorio	rm -rf prog_dir

9.- rmdir dir	Borra un directorio vacío	rmdir prog_dir

10.- ps [axiu]	Muestra información sobre los procesos que se están ejecutando en el sistema	ps -ux , ps -ef
