# ISGlobal.sesión4.Exposoma
<img src="figures/isglobal.png" alt="ISGlobal logo" width="500"/>

## **Introducción al concepto del Exposoma y sus metodologías. Sesión 4 - Estrategias para el análisis de datos de Exposoma.**

<img src="figures/exposoma.png" alt="ISGlobal logo" width="600"/>

**Alan Dominguez**, Investigador Predoctoral del Instituto de Salud Global de Barcelona - ISGlobal  
**Augusto Anguita-Ruiz**, Investigador Postdoctoral del Instituto de Salud Global de Barcelona - ISGlobal

El exposoma, descrito como **"la totalidad de las exposiciones ambientales humanas  desde la concepción en adelante"**, reconoce que los individuos estamos expuestos simultaneamente a multiples factores ambientales diferentes adoptando un efoque holístico para el descubrimento de factores etiológicos de la enfermedad. La ventaja prinicipal del enfoque del exposoma sobre otros más tradicionales "una exposición, una enfermedad o desenlace de salud" es que proporciona un framework para el estudio de múltiples riesgos ambientales (urbanos, químicos, estilo de vida, sociales, etc...) y sus efectos combinados. 

El objetivo de este curso es 



**Nota:** Los datos proporcionados en este curso introductorio fueron simulados a partir de los datos de la subcohorte HELIX. Detalles del projecto HELIX y el origen de los datos colectados pueden ser consultados en la siguiente publicación: https://bmjopen.bmj.com/content/8/9/e021311 y website: https://www.projecthelix.eu/es.  

# Guía del repositorio
En este repositorio encontraras el código y los materiales usados durante la **Sesión 4 - Estrategias para el análisis de datos de Exposoma**. Para ayudarte a navegar por el repositorio, abajo se detalla su organización.

El repositorio contiene los siguientes documentos:

**1.- curso_exposoma_modulo_4.ipynb:** contiene el notebook para la sesión práctica con el código necesario para realizar el análsis de datos en proyectos de exposoma. 

**2.- data:** Esta carpeta contiene el **codebook** y los sets de **datos**, que seran utilizados durante la sesión.  

Las bases de datos estan compuestas por:
* `phenotype` (outcomes)
* `exposome` (exposiciones) 
* `covariates` (covariables)  

La descripción de cada variable (nombre, estructura, tipo de variable, transformacion, ...) esta detallada en el [codebook](https://github.com/alldominguez/ISGlobal.sesion4.Exposoma/blob/main/data/codebook.csv). 
   
**Nota:** Para unir las bases de datos es necesario utilizar la key variable **ID**. 

 




