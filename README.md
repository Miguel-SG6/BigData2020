# BigData2020UTM

## Big data class

### syllabus contents
* The importance of data
Your data without important because if someone gets your data. You can impersonate your identity or even get your bank account and grab the money. Now that your data is already becoming digital, they have become much more important.

* Big Data
It is the storage or data set whose volume, speed, processing are much larger than a database

* Difference between private and open data
Virtually open data is easily found while private data is not.

* Difference between structured and unstructured data
Structured data is data that is easy to search while unstructured data is difficult to search as well as multimedia files.

* Difference between stored and moving data
The stored data are structured and generate information and the moving data are the ones that are circulating in the network

* Data analysis
It is responsible for examining the data in order to draw a conclusion about the information

* Impact of data analytics
The impact it has is that companies can now earn income through data analysis

* Different types of data analytics
-Descriptive: In a business it allows you to see the main metrics within the business. For example, gains and losses in the month, sales made, etc.
-Diagnostic: You must have the necessary tools so that the analyst can deepen the data and isolate the root cause of a problem.
-Predictive: Predictive analysis has to do with prediction. Either the probability of an event occurring in the future, the forecast of a quantifiable amount or the estimation of a point in time at which something could happen - all of them are done through predictive models.
-Prescriptive: The prescriptive model uses an understanding of what has happened, why it has happened and a variety of "what could happen" analysis to help the user determine the best course of action to take. The prescriptive analysis is usually not only with an individual action, but in fact it is a series of other actions.

### other topics

* MapReduce is a framework that provides a parallel and distributed data processing system and is aimed at solving problems with large datasets, so it uses the HDFS distributed file system.

* Hoodoop: Simply put, Hadoop is a set of open source programs and procedures that anyone can use as the “backbone” of their Big Data operations
-Ability to store and process large quantities
-Fault tolerant
-It is very flexible
-Low cost
-Scalable

* Apache Spark: The idea is that we have n machines, for example ten machines, and each of those instances will have a version of Apache Spark installed. In this way, when we have to process a large amount of data, for example a very large file, we can divide it into ten parts, and each machine will handle a tenth of the file, and in the end we will join it.

* Lamba and Kappa
Its objective was to have a robust fault-tolerant system, both human and hardware, that was linearly scalable and that allowed writing and reading with low latency, while kappa points to "weak" Lambda Architecture and how to solve them through an evolution . Your proposal is to eliminate the batch layer leaving only the streaming layer.

* Docker: The idea behind Docker is to create lightweight and portable containers for software applications that can run on any machine with Docker installed, thus also facilitating the deployment or execution of the software.

### Github commands

_this is cursive_


```
git config --global user.email miguelsalvgomez@gmail.com

git init index.html

git add temp.txt

git clone alex@93.188.160.58:/path/to/repository

git commit –m “Cambie un boton”

git log

```
-----------------------------------------------------------------------------------------------------------------
### Identificar el ciclo de vida del análisis de datos.

* *Fase 1 "Planificar":* Se crea la propuesta de investigación, se identifica, describe que datos seran analizados y como se 
manejaran.
* *Fase 2 "Recolectar":* Los datos son recogidos de forma manual o usando instrumentos.
* *Fase 3 "Controlar la calidad":* Los datos pasan a traves de verificaciones e inspecciones para asegurar que los datos sean de 
calidad.
* *Fase 4 "Describir":* Los datos se escriben de forma precisa y completa para generar información para su comprensión
* *Fase 5 "Preservar":* Los datos son enviados a centros de datos para almacenarlos y preservarlos a largo plazo
* *Fase 6 "Descubrir":* Se identifican y obtienen nuevos datos que son utiles a la investigación
* *Fase 7 "Integrar":* Los datos obtenidos desde distintas fuentes son combinadas que pueden ser usados en la investigación
* *Fase 8 "Analizar":* Aqui se usan diversas herramientas que permiten explorar analizar  y visualizar datos.

### Identificar los diferentes tipos de estadística en el análisis de datos.

* *Descriptiva:* Recolectar datos característicos para presentarlos en tablas y gráficas. 
* *Inferencial:* Predecir para estimar para tomar decisiones. También comprende las pruebas de hipótesis.

### Definir Exploratory Data Analysis (EDA) y Extraction Transfer Load (ETL).

* *EDA:* Es un enfoque para analizar conjuntos de datos para resumir sus características principales con métodos visuales. Se 
puede usar un modelo estadístico, pero principalmente EDA es para ver lo que los datos nos pueden decir más allá de la tarea de 
modelado formal o prueba de hipótesis. Se aplica utilizando cualquiera de las siguientes maneras:
  - *Medición y dispersión:* Aplica la estadistica descriptiva, usa las medidas de tendencia central que son media, mediana y moda. 
Utiliza graficas.
  - *Comparación:* Aplica la estadistica inferencial, usa comparaciones visuales a través de gráficas como la campana de Gauss o 
nubes de dispersión.

* *ETL:* Es el proceso que permite a las organizaciones mover datos desde múltiples fuentes, reformatearlos y limpiarlos, y 
cargarlos en otra base de datos. Sus tres principales fases son:
  - *Extraer:* La primera parte del proceso ETL consiste en extraer los datos desde los sistemas de origen.
  - *Transformar:* La fase de transformación aplica una serie de reglas o funciones sobre los datos extraídos para convertirlos 
  en datos que serán cargados. 
  - *Cargar:* Es el momento en el cual los datos de la fase anterior (transformación) son cargados en el sistema de destino. 

### Definir diagrama de flujo de datos.

Es una representación gráfica del flujo de datos a través de un sistema de información y se puede utilizar para la visualización 
de procesamiento de datos (diseño estructurado). Emplea símbolos definidos, como rectángulos, círculos y flechas, además de 
etiquetas de texto breves, para mostrar las entradas y salidas de datos, los puntos de almacenamiento y las rutas entre cada 
destino.

#### Created by:
- Giovanny Dzul
- Miguel Salvador
- Fernando Carvajal

###Getting & knowing your data

]
  },
  {
   "cell_type": "code",
   "execution_count": 1,
   "metadata": {
    "collapsed": false
   },
   "outputs": [],
   "source": [
    "import pandas as pd\n",
    "import numpy as np"
   
  }
  ]
