# Prueba Técnica Davivienda - Extracción Información

Se requiere extraer la información necesaria de gran cantidad de documentos para aumentar la eficiencia operativa, disminuir tiempos de respuesta y mitigar riesgos asociados a los procesos, la información solicitada será el nombre del cliente, la ciudad del cliente, fecha en la que se adquirió el compromiso y el monto que debe pagar. Para este análisis se utilizarán técnicas de procesamiento de lenguaje natural (NLP) para el procesamiento del texto y encontrar la mejor forma de extraer cada información solicitada a partir de un archivo csv que contiene dicha información.

## Descripción

A continuación se presenta un código que cumple con los requerimientos exigidos por Davivienda para la extracción de información como el nombre, ciudad, fecha y montos que se pueden encontrar en un documento tipo embargo.

## Para Empezar

### Librerías

 - import numpy as np
 - import pandas as pd
 - import spacy
 - import re
 - from datetime import datetime
 - import matplotlib.pyplot as plt
 - from sklearn.feature_extraction.text import CountVectorizer
 - from sklearn.decomposition import LatentDirichletAllocation
 - from scipy.sparse import csr_matrix
 - nlp = spacy.load('es_core_news_lg')

### Instalaciones posiblemente necesarias

 - conda install -c conda-forge pandas==1.2.3
 - conda install -c conda-forge pandas==1.2.3
 - conda install -c conda-forge spacy==3.4.4
 - !pip uninstall numpy
 - !pip install numpy
 - !python -m spacy download es_core_news_lg --user
 - !pip install -U scikit-learn --user
 - !pip install matplotlib --user


### Ejecutar el programa

Para ejecutar el programa sólo hay que instalar lo necesario, importar librerías, revisar que la dirección del documento esté bien y darle correr a todo en el apartado de celdas (cell--->Run All)


## Autores

Luván Stiven Tabares Bocanegra </b>   
Linkedin: [https://www.linkedin.com/in/luvan-tabares-501874136/](https://www.linkedin.com/in/luvan-tabares-501874136/)


## Renocimientos

 - Librería spaCy [https://spacy.io/](https://spacy.io/)
 - Librería scikit-learn [https://scikit-learn.org/stable/](https://scikit-learn.org/stable/)
 - Librería pandas [https://pandas.pydata.org/](https://pandas.pydata.org/)
