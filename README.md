﻿﻿﻿﻿﻿﻿
# Proyecto 2: Interrupción Legal del Embarazo - Interpretabilidad y Auditoría de *Bias/Fairness*

En esta segunda parte del proyecto de Interrupción Legal del Embarazo tiene por objeto realizar sobre el modelo escogido seleccionado en el Proyecto1:

A. Interpretabilidad del Modelo
B. Auditoría de Bias y Fairness

## 1. Prerrequisitos

Se requiere tener instalado Python 3. Las versiones específicas de paquetes se encuentran recopiladas en el archivo **Requirements.txt**. Estos requerimientos tienen que ser instalados para poder correr los paquetes (Pandas, Numpy, Lime, Pickle).

También es necesario el paquete de archivos desarrollado anteriormente:
+ load_data


## 2. Instalación

Se adjunta un notebook "Interpretabilidad_Auditoria.ipynb". A este archivo se le tienen que hacer algunos cambios para especificar la ruta de los archivos que contienen los datos, imágenes y modelo. 

Se deben seguir los siguientes pasos:

 1. Descargar la carpeta de archivos *Proyecto_parte2* en alguna ruta específica (ejemplo: /home/bj/Documents/IntroDataScience/Proyecto). Dicha carpeta contiene las subcarpetas de Images, Data y Model

 2. Todos los archivos del paquete deben ser descargados, no necesariamente al mismo folder
 3. Abrir el archivo "Interpretabilidad_Auditoria.ipynb" (notebook) y realizar las siguientes acualizaciones dentro de la celda **# Cambiar rutas**:
              
      3.1. Carpeta *Data* que es la contiene los datos (x\_entrenamiento.csv, x\_prueba.csv, y\_prueba.csv) contenida en la variable **"PATH\_TO\_DATAFILE"** (ejemplo: /home/bj/Documents/IntroDataScience/Proyecto/Data).
              
      3.2. Carpeta *Images* que contiene las imágenes (vars\_auditadas.png, metricas\_grupo.png, metricas\_bias.png, fairness\_criteria.png) contenida en la variable **"PATH\_TO\_IMAGES"** (ejemplo: /home/bj/Documents/IntroDataScience/Proyecto/Images/; asegúrate de terminar esta ruta con "/") dentro de la celda **# Cambiar rutas**.
      
      3.3. Carpeta *Model* que contiene el modelo (final\_model\_ile.sav) contenida en la variable **"PATH\_TO\_MODEL"** (ejemplo: /home/bj/Documents/IntroDataScience/Proyecto/Model/; asegúrate de terminar esta ruta con "/") 
      
      3.4. Correr todo el código

## 3.Reporte

https://bcjg23.github.io/ILE_CDMX_2019_Parte2/Interpretabilidad_Auditoria_ILE_Reporte.html




