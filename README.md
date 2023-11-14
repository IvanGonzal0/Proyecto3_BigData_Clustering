# Análisis de Datos Criminales y Urbanización en Estados Unidos

## Justificación del Informe y Propósitos

Este informe se enfoca en un conjunto de datos que abarca registros de crímenes desde 1973 en distintos estados de EE. UU. Además, se incluye el porcentaje de población que reside en zonas urbanas en esos estados. El propósito principal es clasificar los estados en diferentes categorías basadas en estos factores.

## Contenido

### 1. Importación de Librerías y Carga de Datos

En esta sección, se realizará la importación de librerías esenciales como `Pandas, NumPy y Scikit-Learn LabelEncoder` para la manipulación y preprocesamiento de datos. Se cargará el conjunto de datos para su posterior análisis.

### 2. Visualización de Datos con `Matplotlib y Seaborn`

Se emplearán las librerías `Matplotlib y Seaborn` para explorar y visualizar los datos. La visualización inicial proporcionará una comprensión detallada de las relaciones y distribuciones en el conjunto de datos, facilitando una primera interpretación visual.

### 3. Creación de Modelo `KMeans de Scikit-Learn`

En este apartado, se implementará el algoritmo `KMeans de Scikit-Learn`. Se utilizará la técnica de la "curva del codo" con `Matplotlib` para determinar el número óptimo de clusters. Además, se agregarán etiquetas ('Nivel_Seguridad') al DataFrame mediante `Pandas`, clasificando los estados en categorías como 'Seguro', 'Precaución' y 'Peligroso'. Se visualizarán los resultados con `Seaborn` y `Matplotlib` para una comprensión detallada de la clasificación.

### 4. Creación de Modelo `Mean Shift de Scikit-Learn`

Se implementará el algoritmo `Mean Shift de Scikit-Learn`. Se utilizará la función `estimate_bandwidth de Scikit-Learn` para determinar el ancho de banda adecuado. Los resultados se visualizarán con `Matplotlib y Seaborn` para evaluar la calidad del clustering.

### 5. Creación de Modelo `DBSCAN de Scikit-Learn`

En esta sección, se implementará el algoritmo `DBSCAN de Scikit-Learn`. Se realizará un análisis de los Nearest Neighbors para ajustar el parámetro epsilon (eps). Los resultados se visualizarán con `Matplotlib y Seaborn` para entender la composición y la definición de los clusters.

## Conclusiones y Resultados

Este análisis completo proporciona insights valiosos sobre la clasificación de estados basada en crímenes(asesinatos, asaltos, violaciones y urbanización). Los modelos de `KMeans, Mean Shift y DBSCAN` ofrecen perspectivas distintas, complementando cada uno la interpretación del conjunto de datos. La clasificación final en categorías de seguridad ('Seguro', 'Precaución', 'Peligroso') facilita la toma de decisiones basada en el análisis de datos. 
