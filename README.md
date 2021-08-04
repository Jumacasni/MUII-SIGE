# MUII-SIGE
Asignatura de Sistemas Inteligentes para la Gestión en la Empresa (SIGE) - Máster Profesional en Ingeniería Informática 2020/2021

<details open="open">
  <summary>Tabla de contenidos</summary>
  <ol>
  	<li>
      <a href="#teoria">Trabajo de teoría: Generación de deepfakes</a>
    </li>
    <li>
      <a href="#practica1">Práctica 1: Preprocesamiento de datos y clasificación binaria</a>
    </li>
    <li>
      <a href="#practica2">Práctica 2: Deep Learning para clasificación</a>
    </li>
  </ol>
    
<a name="teoria"></a>
## Trabajo de teoría: Generación de deepfakes

Trabajo de investigación sobre el término **deepfakes**, muy relacionado con las *fake news*. Contenido:

* Discusión de los distintos tipos de *fake news*
* Técnicas más utilizadas (*Generative Adversarial Networks*)
* Casos reales y sus impactos
* Demostración de cómo funcionan las redes GAN

La documentación se encuentra [aquí](deepfakes/CastilloNievasJuanManuel_teoria.pdf)

<a name="practica1"></a>
## Práctica 1: Preprocesamiento de datos y clasificación binaria

En esta práctica se han analizado datos del experimento **ATLAS** del CERN-LHC, que perseguı́a la identificación experimental de la partı́cula **bosón de Higgs**.

Se ha trabajado con el conjunto de datos ofrecido en la competiciónde **Kaggle Higgs Boson Machine Learning Challenge**. Este dataset está formado por 33 variables, siendo una de ellas una variable binaria clasificadora que indica si la instancia es un **bosón** (‘s’) o es **ruido de fondo** (‘b’). Todas las variables son numéricas exceptuando la variable binaria clasificadora que es de tipo carácter. Todos los valores perdidos se codifican con el número -999.0.

El script [practica1.Rmd](practica1/practica1.Rmd) muestra todo el preprocesamiento y clasificación obtenida.

Toda la documentación, análisis y conclusiones de esta práctica se encuentra [aquí](practica1/P1_JuanManuelCastilloNievas.pdf)

<a name="practica2"></a>
## Práctica 2: Deep Learning para clasificación

Práctica realizada junto con [Guillermo Bueno Vargas](https://github.com/Guillergood)

La idea fundamental de esta práctica consiste en desarrollar y proponer una solución a un
problema de clasificación con un determinado conjunto de datos. El conjunto de datos se llama
**Fakeddit** y está formado por un conjunto de noticias falsas.

El problema de clasificación consiste en predecir si una determinada publicación es una noticia
falsa o no. En un principio se trata de una clasificación binaria (es o no es una notifica falsa), pero
este problema se puede ampliar a una clasificación con seis clases, distinguiendo distintos tipos de
noticias falsas.

El script [practica2.Rmd](practica2/practica2.Rmd) muestra todo el proceso de preprocesamiento y clasificación realizado.

Toda la documentación, análisis y conclusiones de esta práctica se encuentra [aquí](practica2/documentacion.pdf)