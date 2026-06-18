# Repositorio de Análisis de Datos  
## Extracción del Conocimiento de Base de Datos

---

## Datos generales

**Nombre del alumno:** Roberto Herrera Zetina  
**Materia:** Extracción del Conocimiento de Base de Datos  
**Cuatrimestre:** 9 B 
**Periodo:** Primer parcial  
**Repositorio:** ECBD_HerreraZetinaRoberto_  
**Plataforma:** GitHub  

---

## Descripción general

Este repositorio fue desarrollado como evidencia académica del primer parcial de la materia **Extracción del Conocimiento de Base de Datos**.

El proyecto reúne diferentes prácticas realizadas en notebooks, donde se aplican procesos relacionados con el análisis de datos, limpieza de información, generación de datasets sintéticos, análisis descriptivo, visualización de datos e interpretación de resultados.

A lo largo de las prácticas se utilizan datasets reales y sintéticos para trabajar con problemas comunes en el tratamiento de datos, como valores nulos, duplicados, outliers, errores de formato, datos inválidos y registros inconsistentes.

El repositorio también permite evidenciar el uso de GitHub como herramienta para organizar archivos, documentar avances, mantener una estructura clara y presentar resultados de manera profesional.

La finalidad del repositorio no es únicamente almacenar código, sino mostrar un proceso completo de análisis de datos: desde la carga inicial de información hasta la generación de conclusiones basadas en evidencia. Por ello, cada práctica representa una etapa importante del aprendizaje en el manejo de datos.

---

## Objetivo general

El objetivo principal de este repositorio es integrar prácticas de análisis de datos mediante Python, aplicando técnicas de limpieza, transformación, visualización e interpretación de información para generar conocimiento a partir de diferentes fuentes de datos.

Además, el repositorio busca demostrar la importancia de la organización, documentación y buenas prácticas en proyectos académicos de análisis de datos.

---

## Objetivos específicos

- Organizar notebooks y datasets dentro de una estructura clara.
- Utilizar Python como lenguaje principal para el análisis de datos.
- Aplicar la librería pandas para cargar, limpiar y transformar datasets.
- Identificar valores nulos, duplicados, datos inválidos y outliers.
- Generar datasets sintéticos mediante herramientas como Faker, random y SDV.
- Crear visualizaciones para facilitar la interpretación de los datos.
- Aplicar el principio GIGO para comprender el impacto de la mala calidad de datos.
- Relacionar el trabajo realizado con el modelo DIKW: Datos, Información, Conocimiento y Sabiduría.
- Documentar correctamente el repositorio mediante un archivo README completo.
- Presentar evidencia del avance de las prácticas realizadas durante el parcial.

---

## Estructura del repositorio

~~~text
ECBD_HerreraZetinaRoberto_/
│
├── NoteBook/
│   ├── Practicas/
│   │   ├── Lab01.ipynb
│   │   ├── lab02.ipynb
│   │   ├── Lab03.ipynb
│   │   ├── Lab04.ipynb
│   │   ├── Lab05.ipynb
│   │   ├── Lab06.ipynb
│   │   ├── Lab07.ipynb
│   │   ├── Lab09.ipynb
│   │   └── Lab10.ipynb
│   │
│   └── Datasets/
│       ├── dataset_sucio_practica.csv
│       ├── netflix_titles.csv
│       ├── test.csv
│       └── ventas-por-factura.csv
│
└── README.md
~~~

---

# Descripción breve de las prácticas

En esta sección se describen las prácticas contenidas en el repositorio. Cada laboratorio aborda un tema relacionado con el análisis de datos, desde la creación de DataFrames hasta la limpieza, visualización, generación de datos sintéticos y aplicación del principio GIGO.

---

## Lab01.ipynb

### Descripción

En esta práctica se introduce el uso de la librería **pandas** para la creación y manipulación de DataFrames.

Primero se crea un conjunto de datos pequeño con información de usuarios. El dataset incluye campos como usuario, edad, ciudad, compras realizadas, estado activo y fecha de registro.

Posteriormente, se genera un DataFrame de gran tamaño con **1,000,000 registros**, simulando información de usuarios con variables como nombre, edad, salario, categoría, ciudad y año de registro.

### Propósito

El propósito de este laboratorio es comprender cómo se crean y manipulan estructuras de datos en Python usando pandas. También permite observar cómo se comporta un DataFrame cuando contiene una gran cantidad de registros.

### Contenido principal

- Importación de pandas.
- Creación manual de un diccionario de datos.
- Conversión del diccionario a DataFrame.
- Visualización inicial del DataFrame.
- Generación de datos aleatorios.
- Creación de un DataFrame con un millón de registros.

### Aprendizajes obtenidos

- Creación manual de DataFrames.
- Manejo básico de pandas.
- Uso de listas y diccionarios en Python.
- Generación de datos aleatorios.
- Manipulación de grandes volúmenes de información.
- Visualización inicial de registros.

---

## lab02.ipynb

### Descripción

Esta práctica se enfoca en la generación de datos sintéticos relacionados con redes sociales e influencers.

Se genera un DataFrame con **1,000,000 registros**, utilizando campos como influencer, likes, comentarios, fecha y tipo de publicación.

Los datos se generan de manera aleatoria utilizando listas de nombres y categorías de publicaciones, como playa, viaje, comida, hotel, selfie y atardecer.

### Propósito

El objetivo de esta práctica es reforzar la creación de datasets sintéticos y analizar el comportamiento de grandes volúmenes de datos dentro de un DataFrame.

### Contenido principal

- Importación de pandas.
- Uso de la librería random.
- Creación de listas de influencers.
- Creación de categorías de publicaciones.
- Generación de un DataFrame masivo.
- Revisión del uso de memoria del dataset.

### Aprendizajes obtenidos

- Generación de datos aleatorios.
- Creación de datasets sintéticos.
- Simulación de información de redes sociales.
- Revisión del uso de memoria de un DataFrame.
- Comprensión básica del costo computacional al trabajar con muchos registros.

---

## Lab03.ipynb

### Descripción

En este notebook se trabaja con un dataset externo de telecomunicaciones relacionado con el abandono de clientes, conocido como **Churn**.

El dataset se carga desde una URL pública y contiene información sobre clientes de una compañía telefónica. Incluye variables relacionadas con llamadas, cargos, planes contratados, duración de cuenta y abandono del servicio.

Algunas columnas utilizadas son:

- State
- Account length
- Area code
- International plan
- Voice mail plan
- Total day minutes
- Total day calls
- Total day charge
- Total eve minutes
- Total night minutes
- Customer service calls
- Churn

### Propósito

El propósito de este laboratorio es realizar una exploración inicial de datos reales, revisar su estructura y obtener estadísticas descriptivas para comprender el comportamiento de los clientes.

### Contenido principal

- Carga de un dataset desde una URL.
- Exploración de columnas.
- Visualización inicial de registros.
- Revisión de tipos de datos.
- Estadística descriptiva.
- Interpretación inicial de variables.

### Aprendizajes obtenidos

- Carga de datasets externos.
- Exploración de datasets reales.
- Uso de funciones como `head`, `info` y `describe`.
- Revisión de variables numéricas y categóricas.
- Análisis inicial de un dataset orientado a clientes.

---

## Lab04.ipynb

### Descripción

Esta práctica utiliza el archivo **test.csv**, correspondiente a un dataset tipo Titanic.

El dataset contiene información de pasajeros, incluyendo columnas como:

- PassengerId
- Pclass
- Name
- Sex
- Age
- SibSp
- Parch
- Ticket
- Fare
- Cabin
- Embarked

### Propósito

El objetivo de este laboratorio es realizar análisis exploratorio de datos y revisar la estructura de un dataset con información de pasajeros.

Este tipo de dataset es útil para practicar la revisión de columnas numéricas, columnas categóricas, valores faltantes y estadísticas generales.

### Contenido principal

- Carga de archivo CSV.
- Visualización de registros.
- Revisión de columnas.
- Análisis descriptivo.
- Identificación de posibles valores nulos.
- Preparación para visualización de datos.

### Aprendizajes obtenidos

- Carga de archivos CSV locales.
- Identificación de columnas numéricas y categóricas.
- Revisión de valores nulos.
- Uso de estadística descriptiva.
- Introducción a la visualización de datos con matplotlib y seaborn.

---

## Lab05.ipynb

### Descripción

En este laboratorio se utiliza el dataset **netflix_titles.csv**, que contiene información sobre películas y series disponibles en Netflix.

El dataset incluye columnas como:

- show_id
- type
- title
- director
- cast
- country
- date_added
- release_year
- rating
- duration
- listed_in
- description

Durante la práctica se identifican valores nulos en columnas como director, cast, country, date_added, rating y duration.

Posteriormente, se realiza una limpieza de datos reemplazando valores faltantes por etiquetas como:

- Desconocido
- Sin clasificación
- No especificado
- Fecha desconocida

### Propósito

El propósito principal es aplicar técnicas de limpieza de datos en un dataset real, evitando eliminar registros importantes y conservando la mayor cantidad posible de información.

### Contenido principal

- Carga del dataset de Netflix.
- Exploración inicial de registros.
- Identificación de valores nulos.
- Cálculo de valores faltantes.
- Limpieza de datos con `fillna`.
- Revisión de duplicados.
- Generación de gráficas.
- Interpretación de resultados.

### Aprendizajes obtenidos

- Identificación de valores nulos.
- Cálculo del porcentaje de datos faltantes.
- Limpieza de columnas con valores vacíos.
- Reemplazo de nulos por etiquetas descriptivas.
- Generación de visualizaciones para analizar contenido.
- Interpretación de información relacionada con películas y series.

### Interpretación de la práctica

Esta práctica demuestra que no siempre es recomendable eliminar registros con datos faltantes. En algunos casos, como ocurre con el dataset de Netflix, un registro puede seguir siendo útil aunque no tenga director, reparto o país. Por eso, se decidió conservar la información y reemplazar los valores nulos con etiquetas descriptivas.

---

## Lab06.ipynb

### Descripción

Esta práctica trabaja con el archivo **dataset_sucio_practica.csv**, el cual contiene errores intencionales para practicar limpieza de datos.

El dataset incluye columnas como:

- id
- nombre
- edad
- correo
- pais
- salario
- fecha_registro
- activo

Durante el análisis se identifican problemas como:

- Valores nulos.
- Edades imposibles, como valores negativos o edades demasiado altas.
- Correos inválidos.
- Países faltantes.
- Salarios nulos.
- Inconsistencias en la columna de estado activo.
- Posibles registros duplicados.

### Propósito

El objetivo de este laboratorio es aplicar técnicas de limpieza y validación de datos, demostrando que antes de analizar información es necesario revisar su calidad.

### Contenido principal

- Carga de un dataset sucio.
- Revisión de tamaño del dataset.
- Visualización de las primeras filas.
- Revisión de valores nulos.
- Análisis de tipos de datos.
- Identificación de datos inválidos.
- Visualización de valores faltantes mediante heatmap.
- Copia del dataset para limpieza.
- Interpretación de errores encontrados.

### Aprendizajes obtenidos

- Detección de datos sucios.
- Uso de `isnull`, `info` y `describe`.
- Identificación de outliers.
- Análisis de columnas con errores.
- Visualización de valores nulos mediante heatmaps.
- Comprensión de la importancia de preparar los datos antes de analizarlos.

### Interpretación de la práctica

El dataset utilizado en este laboratorio muestra claramente que un análisis puede verse afectado si los datos contienen errores. Por ejemplo, una edad negativa o una edad de 150 años puede modificar los resultados estadísticos. De igual forma, correos inválidos o datos faltantes pueden reducir la confiabilidad de cualquier proceso posterior.

---

## Lab07.ipynb

### Descripción

El laboratorio 07 se centra en la generación, limpieza y transformación de un dataset aplicando el principio **GIGO**.

Se utiliza el archivo **ventas-por-factura.csv**, el cual contiene información relacionada con facturas de ventas.

El dataset contiene columnas como:

- N° de factura
- Fecha de factura
- ID Cliente
- País
- Cantidad
- Monto

Durante la práctica se identifican distintos problemas de calidad de datos, entre ellos:

- Valores nulos.
- Facturas canceladas identificadas con la letra C.
- Cantidades negativas.
- Montos negativos.
- Problemas de formato en la columna Monto.
- Fechas con formato de texto.
- Posibles duplicados.
- Outliers en cantidades o montos.

También se solicitan gráficas para apoyar la interpretación, como:

- Ventas por país.
- Heatmap de valores nulos.
- Distribución del monto.

### Propósito

El propósito principal de este laboratorio es demostrar que los datos incorrectos afectan directamente los resultados del análisis. Esto se relaciona con el principio GIGO, el cual indica que si se ingresan datos incorrectos, se obtendrán resultados incorrectos.

### Contenido principal

- Carga del dataset de facturas.
- Revisión de los primeros registros.
- Identificación de facturas canceladas.
- Análisis de cantidades negativas.
- Transformación de montos.
- Conversión de formatos.
- Detección de valores nulos.
- Limpieza del dataset.
- Generación de gráficas solicitadas.
- Exportación del dataset limpio.

### Aprendizajes obtenidos

- Limpieza de datos financieros.
- Conversión de formatos de monto.
- Conversión de fechas.
- Identificación de facturas canceladas.
- Tratamiento de valores negativos.
- Visualización de anomalías.
- Comprensión práctica del principio GIGO.

### Interpretación de la práctica

Esta práctica es una de las más importantes del repositorio, ya que muestra cómo un dataset de ventas puede generar conclusiones incorrectas si no se limpia adecuadamente. Las facturas canceladas, cantidades negativas y montos con formato incorrecto pueden afectar totales, promedios y gráficas.

---

## Lab09.ipynb

### Descripción

En esta práctica se utiliza la librería **Faker** para generar datos sintéticos en español de México.

Se crea un dataset con **1,000 usuarios ficticios**, utilizando columnas como:

- id_usuario
- nombre
- correo
- edad
- seguidores
- plataforma

Las plataformas consideradas son:

- Instagram
- Facebook
- Twitter

### Propósito

El objetivo de este laboratorio es aprender a generar datos ficticios, pero con una estructura realista, para usarlos en pruebas, análisis o simulaciones.

### Contenido principal

- Instalación de Faker.
- Creación de una instancia de Faker con localización mexicana.
- Generación de nombres ficticios.
- Generación de correos electrónicos.
- Generación de edades.
- Generación de número de seguidores.
- Asignación aleatoria de plataforma.
- Conversión de la lista de datos en DataFrame.
- Estadística descriptiva.

### Aprendizajes obtenidos

- Instalación y uso de Faker.
- Generación de nombres y correos ficticios.
- Creación de datasets sintéticos.
- Uso de datos aleatorios para simular redes sociales.
- Análisis descriptivo de datos generados.

### Interpretación de la práctica

Los datos sintéticos son útiles cuando se necesita practicar análisis de datos sin utilizar información real o sensible. Faker permite generar registros que tienen apariencia realista, lo cual ayuda a simular escenarios de análisis.

---

## Lab10.ipynb

### Descripción

En este laboratorio se utilizan las librerías **SDV** y **SDMetrics** para la generación avanzada de datos sintéticos.

Primero se crea un dataset base de clientes con columnas como:

- cliente_id
- edad
- ingreso_mensual
- ciudad

Después se detecta la metadata del DataFrame y se entrena un modelo llamado `GaussianCopulaSynthesizer`. Con este modelo se generan nuevos registros sintéticos que conservan características similares a los datos originales.

Posteriormente, se contamina el dataset agregando errores, como edades imposibles y registros duplicados, con el fin de demostrar cómo se afecta la calidad de los datos.

### Propósito

El propósito principal es comprender cómo se pueden generar datos sintéticos más avanzados mediante modelos especializados, y analizar cómo la mala calidad de datos afecta el resultado final.

### Contenido principal

- Instalación de SDV y SDMetrics.
- Creación de un dataset base de clientes.
- Detección automática de metadata.
- Visualización de metadata.
- Entrenamiento de un sintetizador.
- Generación de datos sintéticos.
- Revisión de datos generados.
- Contaminación del dataset con errores.
- Análisis de duplicados y valores incorrectos.

### Aprendizajes obtenidos

- Instalación de SDV y SDMetrics.
- Uso de metadata en datasets.
- Entrenamiento de un sintetizador de datos.
- Generación de datos sintéticos.
- Evaluación inicial de datos generados.
- Contaminación controlada de datasets.
- Análisis del principio GIGO en datos sintéticos.

### Interpretación de la práctica

Esta práctica permite observar una diferencia importante entre datos generados aleatoriamente y datos sintéticos generados mediante modelos. SDV permite producir datos que conservan patrones similares a los datos originales, lo cual puede ser útil para pruebas, simulaciones y aprendizaje.

---

# Datasets utilizados

En el repositorio se utilizan diferentes tipos de datasets. Algunos son reales, otros son públicos y otros fueron generados de forma sintética durante las prácticas.

| Dataset | Tipo | Descripción | Prácticas relacionadas |
|---|---|---|---|
| `dataset_sucio_practica.csv` | CSV | Dataset con errores intencionales, valores nulos, correos inválidos, edades fuera de rango y datos inconsistentes. | Lab06 |
| `netflix_titles.csv` | CSV | Dataset de películas y series de Netflix, con información sobre título, tipo, director, reparto, país, clasificación y duración. | Lab05 |
| `test.csv` | CSV | Dataset tipo Titanic con información de pasajeros, edad, clase, tarifa, cabina y puerto de embarque. | Lab04 |
| `ventas-por-factura.csv` | CSV | Dataset de facturas de ventas con país, cliente, cantidad, fecha y monto. | Lab07 |
| Telecom Churn | Dataset externo | Dataset público de clientes de telecomunicaciones para analizar abandono de servicio. | Lab03 |
| Datos sintéticos de usuarios | Generado con Python | Dataset creado manualmente y con valores aleatorios para practicar DataFrames. | Lab01 |
| Datos sintéticos de influencers | Generado con Python | Dataset de publicaciones de influencers con likes, comentarios y tipo de post. | lab02 |
| Datos sintéticos con Faker | Generado con Faker | Dataset de usuarios ficticios con nombre, correo, edad, seguidores y plataforma. | Lab09 |
| Datos sintéticos con SDV | Generado con SDV | Dataset de clientes generado mediante un sintetizador de datos. | Lab10 |

---

## Descripción de los datasets principales

### dataset_sucio_practica.csv

Este dataset fue utilizado para practicar limpieza de datos. Contiene errores como valores nulos, edades fuera de rango, correos inválidos, países faltantes y datos inconsistentes.

Su utilidad principal es demostrar que un dataset puede contener problemas que deben corregirse antes de realizar análisis confiables.

---

### netflix_titles.csv

Este dataset contiene información sobre contenido de Netflix. Incluye películas y series, así como datos de director, reparto, país, año de lanzamiento, duración, clasificación y descripción.

Es útil para realizar análisis exploratorio, limpieza de valores nulos y visualizaciones relacionadas con el tipo de contenido.

---

### test.csv

Este archivo corresponde a un dataset tipo Titanic. Contiene información de pasajeros como edad, sexo, clase, tarifa y puerto de embarque.

Se utiliza para practicar análisis exploratorio y revisión de valores faltantes.

---

### ventas-por-factura.csv

Este dataset contiene información de facturas de ventas. Incluye número de factura, fecha, cliente, país, cantidad y monto.

Es utilizado principalmente para analizar problemas de calidad de datos, como facturas canceladas, montos negativos, cantidades negativas y formatos incorrectos.

---

### Dataset Telecom Churn

Este dataset se carga desde una fuente externa y contiene información de clientes de telecomunicaciones. Se utiliza para analizar variables relacionadas con el abandono del servicio.

Permite practicar análisis descriptivo con un dataset real.

---

# Herramientas utilizadas

## Lenguaje de programación

### Python

Python fue el lenguaje principal utilizado en todas las prácticas. Se eligió porque cuenta con librerías especializadas para análisis, limpieza, transformación y visualización de datos.

---

## Entornos de trabajo

### Jupyter Notebook

Jupyter Notebook permite trabajar con celdas de código y texto, facilitando la documentación del proceso de análisis.

### Google Colab

Google Colab permite ejecutar notebooks en la nube sin necesidad de instalar todo el entorno localmente. También facilita la instalación rápida de librerías.

### GitHub

GitHub se utilizó para almacenar, organizar, versionar y documentar el proyecto. Además, permite evidenciar el avance de las prácticas y mantener una estructura profesional.

---

## Librerías utilizadas

### pandas

Utilizada para:

- Crear DataFrames.
- Cargar archivos CSV.
- Explorar datasets.
- Limpiar valores nulos.
- Transformar columnas.
- Calcular estadísticas descriptivas.
- Detectar duplicados.

### numpy

Utilizada para:

- Operaciones numéricas.
- Manejo de valores especiales.
- Apoyo en transformaciones de datos.

### matplotlib

Utilizada para:

- Crear gráficas básicas.
- Visualizar distribuciones.
- Representar resultados de análisis.

### seaborn

Utilizada para:

- Crear visualizaciones estadísticas.
- Generar heatmaps.
- Crear gráficas de conteo.
- Mejorar la interpretación visual de los datos.

### random

Utilizada para:

- Generar datos aleatorios.
- Simular registros.
- Crear valores ficticios para datasets grandes.

### Faker

Utilizada para:

- Generar nombres ficticios.
- Generar correos electrónicos.
- Crear datos sintéticos con apariencia realista.
- Simular usuarios.

### SDV

Utilizada para:

- Generar datos sintéticos avanzados.
- Entrenar sintetizadores de datos.
- Crear registros nuevos basados en un dataset original.

### SDMetrics

Utilizada como complemento para trabajar con datos sintéticos y evaluar aspectos relacionados con su calidad.

---

# Instrucciones de ejecución general

Para ejecutar correctamente las prácticas del repositorio, se recomienda seguir los siguientes pasos.

---

## 1. Clonar el repositorio

~~~bash
git clone https://github.com/Roberto-H-Z/ECBD_HerreraZetinaRoberto_.git
~~~

---

## 2. Entrar a la carpeta del repositorio

~~~bash
cd ECBD_HerreraZetinaRoberto_
~~~

---

## 3. Abrir los notebooks

Los notebooks se encuentran en la siguiente ruta:

~~~text
NoteBook/Practicas/
~~~

Se pueden abrir con cualquiera de las siguientes herramientas:

- Jupyter Notebook
- JupyterLab
- Google Colab
- Visual Studio Code con extensión de Jupyter

---

## 4. Verificar los datasets

Los datasets se encuentran en la ruta:

~~~text
NoteBook/Datasets/
~~~

Antes de ejecutar los notebooks, se debe verificar que los archivos CSV estén disponibles en la ruta correcta.

---

## 5. Instalar librerías necesarias

En caso de ejecutar el proyecto en un entorno local, se pueden instalar las librerías principales con el siguiente comando:

~~~bash
pip install pandas numpy matplotlib seaborn faker sdv sdmetrics
~~~

---

## 6. Ejecutar las celdas

Cada notebook debe ejecutarse en orden, desde la primera celda hasta la última, para evitar errores por variables no definidas o archivos no cargados.

---

## 7. Revisar resultados

Después de ejecutar cada práctica, se deben revisar:

- Tablas generadas.
- Estadísticas descriptivas.
- Valores nulos.
- Duplicados.
- Gráficas.
- Interpretaciones.
- Conclusiones del análisis.

---

## 8. Recomendaciones de ejecución

Para evitar errores, se recomienda:

- Mantener los datasets en la carpeta correcta.
- Ejecutar las celdas en orden.
- Instalar las librerías antes de correr el notebook.
- Revisar que los nombres de los archivos coincidan con los nombres usados en el código.
- Usar Google Colab si no se desea configurar un entorno local.
- Guardar capturas de las gráficas más importantes para documentar evidencia.

---

# Principio GIGO

El principio **GIGO** significa **Garbage In, Garbage Out**, que en español puede interpretarse como “basura entra, basura sale”.

Este principio establece que si los datos utilizados en un análisis son incorrectos, incompletos, inconsistentes o de mala calidad, los resultados obtenidos también serán incorrectos o poco confiables.

En las prácticas del repositorio se observa este principio en varios casos:

- Edades negativas o imposibles.
- Montos negativos.
- Correos inválidos.
- Valores nulos.
- Duplicados.
- Fechas con formato incorrecto.
- Facturas canceladas.
- Datos categóricos inconsistentes.

Por ejemplo, si se calcula el promedio de edad usando registros con edades negativas o valores extremadamente altos, el resultado no representará correctamente la realidad. De la misma manera, si se analizan ventas sin eliminar facturas canceladas o montos negativos, las conclusiones financieras pueden ser equivocadas.

Por esta razón, antes de generar gráficas o interpretar resultados, es necesario realizar un proceso de limpieza y validación de datos.

---

# Modelo DIKW

El modelo **DIKW** representa la transformación de los datos hasta llegar al conocimiento y la toma de decisiones.

DIKW significa:

- **Data:** Datos.
- **Information:** Información.
- **Knowledge:** Conocimiento.
- **Wisdom:** Sabiduría.

---

## Datos

Los datos son valores sin procesar. Por ejemplo:

- Edades.
- Países.
- Fechas.
- Montos.
- Cantidades.
- Nombres.
- Correos.
- Plataformas.

Por sí solos, estos datos no explican mucho si no se organizan o analizan.

---

## Información

Los datos se convierten en información cuando se organizan y procesan.

Por ejemplo:

- Cantidad de películas y series en Netflix.
- Total de ventas por país.
- Promedio de edad de usuarios.
- Cantidad de valores nulos por columna.
- Número de registros duplicados.

---

## Conocimiento

El conocimiento surge cuando se interpreta la información.

Por ejemplo:

- Se puede identificar qué país genera más ventas.
- Se puede observar qué columnas tienen más problemas de calidad.
- Se puede reconocer qué tipo de contenido predomina en Netflix.
- Se puede detectar si un dataset necesita limpieza antes de ser usado.

---

## Sabiduría

La sabiduría consiste en tomar decisiones basadas en el conocimiento obtenido.

Por ejemplo:

- Decidir limpiar valores nulos antes de entrenar un modelo.
- Eliminar o corregir registros con datos imposibles.
- No utilizar facturas canceladas para calcular ventas reales.
- Documentar los cambios realizados en los datasets.
- Mejorar la calidad de los datos antes de realizar análisis o modelos de Machine Learning.

---

# Interpretación general de resultados

Durante el desarrollo de las prácticas se pudo observar que cada dataset presenta características diferentes. Algunos datasets son generados de manera sintética, mientras que otros contienen información real o semirreal.

En los datasets limpios o bien estructurados, el análisis es más directo y confiable. Sin embargo, en los datasets sucios se requiere aplicar procesos de limpieza antes de obtener resultados útiles.

Las prácticas relacionadas con Netflix, Titanic, facturas y datos sucios permitieron identificar la importancia de revisar la estructura del dataset antes de hacer cualquier interpretación.

También se observó que las visualizaciones ayudan a comprender mejor el comportamiento de los datos, ya que permiten detectar patrones, concentraciones, anomalías y diferencias entre categorías.

---

# Buenas prácticas aplicadas

En este repositorio se aplican diferentes buenas prácticas, como:

- Separación de notebooks y datasets en carpetas.
- Uso de nombres descriptivos para archivos.
- Documentación general mediante README.
- Uso de comentarios dentro de los notebooks.
- Carga de datos desde archivos CSV.
- Limpieza de valores nulos.
- Revisión de duplicados.
- Análisis descriptivo antes de interpretar.
- Uso de gráficas para apoyar conclusiones.
- Organización de prácticas por laboratorio.
- Uso de GitHub para evidenciar avances.
- Mantenimiento de una estructura clara para facilitar la revisión.

---

# Conclusiones generales

El desarrollo de este repositorio permitió comprender la importancia de la limpieza, organización e interpretación de datos dentro de un proyecto de análisis.

A través de los diferentes laboratorios se practicó el uso de Python y pandas para cargar, explorar y transformar datasets. También se utilizaron herramientas de visualización como matplotlib y seaborn, las cuales ayudan a representar los datos de forma más clara y comprensible.

Una de las principales conclusiones es que la calidad de los datos influye directamente en la calidad de los resultados. Si un dataset contiene valores nulos, datos duplicados, formatos incorrectos o registros inválidos, las conclusiones pueden ser erróneas. Por ello, la limpieza de datos es una etapa fundamental antes de realizar análisis descriptivos o modelos de Machine Learning.

También se aprendió que los datos sintéticos son útiles para practicar análisis, hacer pruebas y simular escenarios reales sin comprometer información sensible. Herramientas como Faker y SDV permiten generar datasets con estructuras realistas, lo cual resulta útil para el aprendizaje y la experimentación.

El principio GIGO fue uno de los conceptos más importantes trabajados en el repositorio, ya que demuestra que los resultados de un análisis dependen directamente de la calidad de los datos de entrada. Si los datos son incorrectos, los resultados también serán incorrectos.

Finalmente, el uso de GitHub permitió mantener una mejor organización del proyecto, almacenar evidencias, documentar el avance de las prácticas y presentar el trabajo de forma profesional. La documentación mediante README facilita que cualquier persona pueda comprender el objetivo del repositorio, los datasets utilizados, las herramientas aplicadas y los resultados obtenidos.

---

# Conclusión personal

Como alumno, considero que estas prácticas fueron útiles para comprender el proceso completo de trabajo con datos, desde la carga inicial hasta la interpretación de resultados.

Antes de realizar estas actividades, podría parecer que analizar datos consiste únicamente en ejecutar código o generar gráficas. Sin embargo, durante el desarrollo de los laboratorios se observa que una parte fundamental del análisis es revisar la calidad de los datos, corregir errores, justificar decisiones y explicar los resultados obtenidos.

El repositorio representa una evidencia del aprendizaje adquirido durante el primer parcial y demuestra la importancia de trabajar de forma ordenada, documentada y responsable en proyectos relacionados con bases de datos y análisis de información.

---

# Estado del proyecto

Este repositorio corresponde a la evidencia del **primer parcial** de la materia **Extracción del Conocimiento de Base de Datos**.

El proyecto contiene notebooks, datasets, análisis, limpieza de datos, visualizaciones, interpretación de resultados y documentación general.

---

# Referencias internas del repositorio

- Notebooks de prácticas ubicados en `NoteBook/Practicas/`.
- Datasets utilizados ubicados en `NoteBook/Datasets/`.
- Capturas sugeridas ubicadas en `NoteBook/Imagenes/`.
- README principal ubicado en la raíz del repositorio.

---

# Resumen final

Este README documenta el contenido del repositorio, las herramientas utilizadas, los datasets trabajados, las instrucciones generales de ejecución, las prácticas realizadas y las conclusiones obtenidas.

El repositorio evidencia el proceso de aprendizaje del primer parcial y cumple con el propósito de integrar análisis descriptivo, limpieza de datos, visualización, interpretación y generación de conocimiento mediante el uso de Python y GitHub.
