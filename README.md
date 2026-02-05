# An-lisis-comparativo-del-tama-o-corporal-dimorfismo-sexual-y-comportamiento-reproductivo-en-aves.

## Introduccion:

Este proyecto analiza cómo el tamaño corporal en las aves se relaciona con diferencias entre machos y hembras, con la reproducción y con patrones evolutivos generales. El tamaño corporal es un rasgo clave porque influye en la biología, el comportamiento y la ecología de las especies, por lo que entenderlo ayuda a interpretar muchas otras características.

A partir de un conjunto de datos comparativos ampliamente utilizado en ecología evolutiva, se estudia el dimorfismo sexual, la relación entre tamaño y fecundidad, y las similitudes y diferencias entre especies según su tamaño y forma. Además, se utilizan modelos de clasificación para explorar la relación entre el tamaño corporal, los sistemas de emparejamiento (monógamos vs no monógamos) y la complejidad de los rituales de exhibición.

Los datos provienen del trabajo de Lislevand, Figuerola y Székely (2007), quienes recopilaron información morfológica y reproductiva de numerosas especies de aves con el objetivo de facilitar estudios comparativos a gran escala sobre selección sexual y estrategias reproductivas.

## Objetivos

- Analizar el dimorfismo sexual en tamaño corporal en aves.
- Evaluar la relación entre tamaño corporal y fecundidad.
- Explorar patrones macroevolutivos de tamaño y forma.
- Clasificar sistemas de emparejamiento (monógamo vs no monógamo).
- Clasificar la complejidad de los rituales de exhibición.

## Datos

Se utilizan datos morfológicos y reproductivos de aves publicados por  
Lislevand, Figuerola y Székely (2007), incluyendo medidas corporales por sexo,
variables reproductivas y descriptores de comportamiento.

## Metodología

Se realizó análisis exploratorio de datos, visualizaciones comparativas y
análisis multivariado (PCA) para estudiar patrones de tamaño y dimorfismo.
Además, se entrenaron modelos de clasificación para evaluar
relaciones entre tamaño corporal, sistemas de emparejamiento y fecundidad.

## Tecnologias utilizadas

El proyecto fue desarrollado y ejecutado íntegramente en Google Colab, por lo que no requiere instalación local.
Los notebooks pueden ejecutarse directamente en el navegador, asegurando reproducibilidad y facilidad de uso.

Herramientas:
Google Colab (entorno de ejecución)
Python
Librerias: NumPy, Pandas, Matplotlib / Seaborn (visualización), scikit-learn (PCA, clasificación y modelos predictivos)

Sección de preguntas frecuentes con todas las preguntas planteadas hasta la fecha.
Información sobre derechos de autor y licencias.


## Estado del proyecto

El proyecto se encuentra actualmente en desarrollo. Entre las principales líneas de trabajo abiertas se incluyen:

Desbalance en clasificadores (Objetivos 4 y 5): aplicación de técnicas de balanceo de clases para mejorar el desempeño del modelo, con especial foco en el recall de las clases minoritarias.

Dilución del dimorfismo en análisis PCA (Objetivo 1): realización de análisis de componentes principales adicionales sobre subconjuntos específicos de rasgos morfológicos (por ejemplo, masa y tarso para dimorfismo inverso; ala y cola para ornamentación), con el fin de resaltar patrones biológicamente relevantes que pueden quedar atenuados en el PCA global.

Modelos alternativos para tamaño vs fecundidad (Objetivo 2): evaluación de modelos basados en Random Forest para análisis de regresión, como complemento a los enfoques lineales actuales.

## Referencias

Lislevand, T., Figuerola, J., & Székely, T. (2007).
*Avian body sizes in relation to fecundity, mating system, display behavior,
and resource sharing*. Ecology, 88, 1605.

