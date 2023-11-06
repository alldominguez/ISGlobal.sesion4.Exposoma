# ISGlobal.sesión4.Exposoma
## **Introducción al concepto del Exposoma y sus metodologías. Sesión 4 - Estrategias para el análisis de datos de Exposoma.**
<img src="figures/isglobal.png" alt="ISGlobal logo" width="300"/>  
<img src="figures/exposoma.png" alt="ISGlobal logo" width="500"/>

**Alan Domínguez**, Investigador Predoctoral del Instituto de Salud Global de Barcelona - ISGlobal  
**Augusto Anguita-Ruiz**, Investigador Postdoctoral del Instituto de Salud Global de Barcelona - ISGlobal

Una de las ventajas principales del enfoque del exposoma, en comparación con otros más tradicionales como "una exposición, una enfermedad", es que proporciona un marco para el estudio de múltiples riesgos ambientales (urbanos, químicos, estilo de vida, sociales, entre otros) y sus efectos combinados en la salud humana.

El **exposoma** se define como **"la totalidad de las exposiciones ambientales humanas desde la concepción en adelante"**. Este concepto reconoce que los individuos estamos expuestos simultáneamente a múltiples factores ambientales diferentes, adoptando un enfoque holístico para el descubrimiento de factores etiológicos de enfermedades. La ventaja principal del enfoque del exposoma, en comparación con otros más tradicionales como "una exposición, una enfermedad", es que proporciona un marco de trabajo para el estudio de múltiples riesgos ambientales (urbanos, químicos, de estilo de vida, sociales, entre otros) y sus efectos combinados.

El **objetivo** de esta sesión es ofrecer una **introducción a los distintos abordajes estadísticos** necesarios para responder a las principales cuestiones de **investigación en exposoma**; por lo tanto, esta sesión:

**1.- Análisis descriptivo:** En una primera parte de la sesión, se trabajará sobre el concepto de análisis descriptivo en exposómica, mediante el cual se extraen las primeras conclusiones sobre los datos. Entre otros objetivos, el análisis descriptivo persigue identificar posibles valores anómalos, factores de confusión o variables que requieran transformaciones previas al análisis. A su vez, permite comparar preliminarmente los grupos experimentales objeto de estudio, estudiar los patrones de correlación existentes entre factores de exposición e identificar fenómenos de agrupación en los datos (tanto a nivel de individuos como de características), pasos imprescindibles para elegir el abordaje estadístico posterior más adecuado.

Algunos de los contenidos que revisaremos en esta sección incluyen:
* **Visualización de la distribución y concentración de variables del exposoma.**
* **Correlación entre exposiciones.**
* **Análisis de Componentes Principales (PCA) aplicado a variables del exposoma.**

**2.- Análisis de asociación:** El análisis de asociación persigue la identificación de posibles factores de exposición ambiental asociados con distintos parámetros de salud. En este bloque, se presentarán distintos abordajes analíticos holísticos centrados en el estudio de los efectos de múltiples factores de exposición y sus mezclas sobre la salud. Esto incluye modelos como el ExWAS (Exposome-Wide Association Analysis), u otros para el estudio de interacciones o fenómenos de no linealidad (e.g., Bayesian Kernel Machine Regression). También se presentará una introducción a los métodos de clustering y mezclas de exposición (e.g., Weighted Quantile Sum Regression). Durante su estudio, se introducirán conceptos de gran importancia en el análisis del exposoma, como son la selección de características o la corrección de testeo múltiple.

Algunos de los contenidos que revisaremos en esta sección incluyen:
* **Exposure Wide Association Analysis (ExWas).**
* **Métodos para la selección de variables (Stepwise, Elastic net, DSA).**
* **Clustering.**
* **Weighted Quantile Sum Regression (WQSR).**
* **Bayesian Kernel Machine Regression (BKMR).**

Para esta sesión práctica, utilizaremos datos del estudio de exposoma HELIX. El estudio HELIX es un proyecto colaborativo entre seis estudios longitudinales de cohortes de nacimiento, basados en la población de seis países europeos (Francia, Grecia, Lituania, Noruega, España y Reino Unido).

<img src="figures/HELIX.png" alt="HELIX logo" width="500"/> 

**Nota:** Los datos proporcionados en este curso introductorio fueron simulados a partir de los datos de la subcohorte HELIX. Detalles del proyecto HELIX y el origen de los datos recopilados pueden ser consultados en la siguiente publicación: [BMJ Open - HELIX](https://bmjopen.bmj.com/content/8/9/e021311) y en el [sitio web del proyecto](https://www.projecthelix.eu/es).

# Guía del Repositorio
En este repositorio encontrarás el código y los materiales usados durante la **Sesión 4 - Estrategias para el análisis de datos de Exposoma**. Para ayudarte a navegar por el repositorio, a continuación se detalla su organización.

El repositorio contiene los siguientes documentos:

**1.- curso_exposoma_modulo_4.ipynb:** Contiene el notebook para la sesión práctica con el código necesario para realizar el análisis de datos en proyectos de exposoma.

**2.- data:** Esta carpeta contiene el **codebook** y los sets de **datos** que serán utilizados durante la sesión.

* Los **datos de exposoma (n = 1301)** que utilizaremos están contenidos en un archivo **Rdata**, que incluye los siguientes ficheros:
  1. `phenotype` (resultados).
  2. `exposome` (exposiciones).
  3. `covariates` (covariables).
  4. `codebook`

La descripción de cada variable (nombre, estructura, tipo de variable, transformacion, ...) esta detallada en el [codebook](https://github.com/alldominguez/ISGlobal.sesion4.Exposoma/blob/main/data/codebook.csv). 
   
**Nota:** Para unir las bases de datos es necesario utilizar la key variable **ID**. 

 




