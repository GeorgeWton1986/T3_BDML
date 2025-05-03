# Problem set 3 - Making Money with ML 

## Integrantes: Nicolas Jácome; Zaira García; Jorge Viáfara; Laura Rivera 

### Introducción: 

El presente trabajo surge a partir de una solicitud realizada por una startup emergente enfocada en la compraventa de propiedades residenciales. La empresa ha contratado a nuestro equipo para desarrollar un modelo predictivo que le permita adquirir el mayor número posible de viviendas en la localidad de Chapinero, Bogotá, al menor costo. Para este fin, se dispone de una base de datos proporcionada por Properati, que contiene información detallada sobre inmuebles en Bogotá. El objetivo central de este estudio es estimar con precisión el precio de venta de las viviendas, utilizando el enfoque de precios hedónicos propuesto por Rosen (1974). Esta teoría plantea que los bienes diferenciados, como las viviendas, pueden descomponerse en un conjunto de atributos —como el número de habitaciones, la ubicación, el acceso a servicios o la calidad ambiental— que determinan su valor de mercado. 

Diversos estudios han profundizado en esta teoría. Glaeser, Gyourko, Morales y Nathanson (2014) integran la noción de equilibrio espacial, destacando cómo variables como la oferta de nuevas viviendas, el número de hogares, los ingresos y las amenidades locales inciden en los precios. De manera complementaria, Brueckner (2011) señala que los consumidores se reubican dentro de las ciudades buscando maximizar su utilidad, lo que genera una segmentación espacial en los precios de vivienda. En el contexto colombiano, investigaciones como las de Morales et al. (2013) y Revollo (2009) han evidenciado que las características estructurales, urbanas y sociales influyen significativamente en la valoración del suelo urbano, variando según la percepción del entorno y la calidad de vida. 

### Contenido 

El análisis se divide en diferentes etapas, comenzando por la adquisición y limpieza de los datos. Se trabajó con una base de 38.644 observaciones y 16 variables estructurales, a las que se sumaron atributos adicionales construidos a partir de descripciones textuales. Se aplicaron procesos de transformación y normalización de variables, así como técnicas de imputación para manejar valores faltantes, con el fin de conservar la mayor cantidad de información posible. 

Esta sección describe los modelos utilizados para la predicción, con modelos entrenados en siete algoritmos de regresión y aprendizaje de máquinas: Regresión Lineal, Red Elástica, CARTs, Random Forest, Boosting, Redes Neuronales y SuperLearners. Cada uno de estos enfoques ofrece ventajas particulares para capturar relaciones lineales, no lineales y complejas entre variables, permitiendo comparar su desempeño en términos de precisión y robustez. 

A lo largo del estudio se evaluaron estas técnicas bajo métricas de error estándar, destacándose el modelo de Random Forest por su capacidad para capturar relaciones no lineales y manejar interacciones complejas entre variables. Este ejercicio no solo permite optimizar las decisiones de compra de la startup, sino que también ofrece una visión detallada sobre cómo influyen las características físicas y contextuales de las viviendas en su valorización dentro del mercado inmobiliario de Bogotá, en particular en una zona estratégica como Chapinero. 

### 01_Documents 
En esta carpeta se encuentran dos archivos en formato PDF, el primero es el documento final con resultados y conclusiones y el segundo el documento guia para desarrollar el problem set. 

### 02_Script 
En esta carpeta se incluye el archivo en R Markdown donde se desarrolla el problem set y el script en R donde se deposita únicamente el código. 

### 03_Stores 
En esta carpeta se enceuntran varios archivos tipo .csv que incluyen las base de datos test y train empleadas para realizar las predicciones y múltiples archivos con las predicciones estimadas. 

### 04_Views 
En esta carpeta se evidencian los gráficos obtenidos del código en formato JPG y las tablas con algunos de los resultados. 
