# Curso Python

Para el seguimiento de este curso, recomendamos la instalación de [**anaconda**](https://www.anaconda.com/).
Dependiendo de vuestro **sistema operativo**, deberéis elegir la instalación correspondiente y seguir los pasos indicados en el siguiente [**link**](https://docs.anaconda.com/anaconda/install/).

Igualmente, Google tiene una plataforma para trabajar con Python sin necesidad de descargar ningún software. Se trata de la plataforma [**Google Colab**](https://colab.research.google.com), en la cual podemos interactuar con nuestros archivos de Google Drive y URL de GitHub cómodamente.

Al acceder a Google Colab, nos mostrará inmediatamente una pantalla como ésta:
<div align="center">
   <img src="https://bebi103a.github.io/_images/colab_splash.png" width="600">
</div>
 
 en la que, si pincháis en el apartado de **GitHub**, aparecerá un buscador de URL y podéis poner esta misma dirección en él y aparecerán todos los notebooks que están recogidos en este curso.
 
 Por último, comentar que GitHub suele tener problemas al cargar algunos notebooks en web, por lo que, cuando suceda esto, podemos copiar la dirección web y pegarla en la página de [**nbviewer**](https://nbviewer.jupyter.org/). 
 

## Estructura del Curso

La estructura del curso es eminentemente práctica, enfocando al alumno a la realización de diversos ejercicios para afianzar las ideas que se irán desarrollando a lo largo de distintos [**jupyter notebooks**](https://jupyter.org/); recomendamos que, si queréis seguir el curso de manera **local**, modificar los ficheros y probar los ejemplos por vosotros mismos, os [**descarguéis el repositorio**](https://github.com/AfiQuants/Curso_Python/archive/main.zip)

Veamos ahora cómo se irán distribuyendo estos **notebooks** según el tema que tratemos:

### **Python Básico:** 

<div align="center">
   <a href="https://github.com/AfiQuants/Curso_Python/tree/main/1.%20Python_Basico/">
   <img src="https://3.bp.blogspot.com/-I-pXRG4ijSA/XYGcA9iILII/AAAAAAAACVg/HHB9ROtp1mUpkCTCKkjB_froP1dWbTmIACK4BGAYYCw/s1600/introToPython1.webp">
   </a>
</div>

En esta parte del curso veremos los elementos básicos del lenguaje y daremos los primeros pasos con el mismo; aprenderemos:

   * [**Sintaxis y Elementos básicos**](1.%20Python_Basico/1.Sintaxis%20y%20elementos%20basicos.ipynb)
   * [**Estructuras de datos**](1.%20Python_Basico/2.Estructuras%20de%20datos.ipynb)
   * [**Estructuras de control**](1.%20Python_Basico/3.Estructuras%20de%20control.ipynb)
   * [**Funciones y Modulos**](1.%20Python_Basico/4.Funciones%20y%20modulos.ipynb)
   * [**Trabajo con ficheros**](1.%20Python_Basico/5.Trabajo%20con%20ficheros.ipynb)
   
    
### **Numpy:** 

<div align="center">
   <a href="https://github.com/AfiQuants/Curso_Python/tree/main/2.%20Numpy/">
   <img src="https://bids.berkeley.edu/sites/default/files/styles/400x225/public/projects/numpy_project_page.jpg?itok=flrdydei">
   </a>
</div>

En esta parte del curso veremos una de las librerías básicas para el análisis numérico en python, **Numpy**; aprenderemos:

   * [**Introducción a Numpy**](2.%20Numpy/1.%20La%20base%20de%20NumPy%20-%20ndarray.ipynb)
   * [**Operaciones básicas**](2.%20Numpy/2.%20Operaciones%20sobre%20ndarrays.ipynb)
   * [**Ficheros**](2.%20Numpy/3.%20Entrada%20y%20salida%20de%20ficheros.ipynb)
   * [**Álgebra y Números Aleatorios**](2.%20Numpy/4.%20Álgebra%20lineal%20y%20generación%20de%20numeros%20aleatorios.ipynb)
    
### **Pandas:** 

<div align="center">
   <a href="https://github.com/AfiQuants/Curso_Python/tree/main/3.%20Pandas/">
   <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ-tHuIMswK4H-VjtPuTBSS07lSya4YNeh3FQ&usqp=CAU">
   </a>
</div>

En esta parte del curso veremos una de las librerías básicas para la manipulación de datos en python, **Pandas**; aprenderemos:

   * [**Introducción a Pandas**](3.%20Pandas/1.%20ructuras%20datos.ipynb)
   * **Operaciones básicas**:
      * [**Tratamiento de Dataframes**](3.%20Pandas/2.1.%20Operaciones%20básicas.ipynb)
      * [**Indexación y Slicing**](3.%20Pandas/2.2.%20Operaciones%20básicas.ipynb)
      * [**Construcción de Estructuras**](3.%20Pandas/2.3.%20Operaciones%20básicas.ipynb)
   * [**Lectura y Escritura de información**](3.%20Pandas/3.%20Lectura%20y%20escritura%20de%20informacion.ipynb)
   * [**Preparación y Exploración de datos**](3.%20Pandas/4.%20Preparación%20y%20exploración%20de%20datos.ipynb)
   
### **Visualización:** 

<div align='center'>
   <table><tr>
   <td> 
      <p align="center">
         <a href="https://github.com/AfiQuants/Curso_Python/blob/main/4.%20Visualizaci%C3%B3n/1.Matplotlib.ipynb">
         <img src="https://matplotlib.org/_static/logo2_compressed.svg" width="320">
      <br>
      </p> 
   </td>
   <td> 
      <p align="center">
         <a href="https://github.com/AfiQuants/Curso_Python/blob/main/4.%20Visualizaci%C3%B3n/2.Plotly.ipynb">
         <img src="https://images.prismic.io/plotly-marketing-website/bd1f702a-b623-48ab-a459-3ee92a7499b4_logo-plotly.svg?auto=compress,format" width="320">
      <br>
      </p> 
   </td>
   </tr></table>
</div>

Como en todo software, una de las partes más importantes y báscias es saber hacer gráficos. Veremos las principales librerías que existen actualmente, como son:

   * [**Matplotlib**](4.%20Visualización/1.Matplotlib.ipynb)
   * [**Plotly**](4.%20Visualización/2.Plotly.ipynb)
   * [**Seaborn y Altair**](4.%20Visualización/3.Seaborn_y_Altair.ipynb)
   
### **Descarga de Datos:** 

<div align="center">
   <a href="https://github.com/AfiQuants/Curso_Python/tree/main/5.%20Descarga%20de%20Datos%20-%20Web%20Scraping/">
   <img src="https://www.octoparse.es/media/6720/001-efficient-web-scraping.png">
   </a>
</div>

En esta parte del curso veremos formas de obtener datos directamente de la web; aprenderemos:

   * [**Introducción a Pandas Datareader**](5.%20Descarga%20de%20Datos%20-%20Web%20Scraping/1.%20Pandas%20DataReader.ipynb)
   * [**Web Scraping a través de BeautifulSoup y Selenium**](5.%20Descarga%20de%20Datos%20-%20Web%20Scraping/2.%20Web%20Scraping.ipynb)
 
 ## Ejercicios
 A lo largo de estos módulos se han introducido varios **conceptos** y podéis haberlo seguido a lo largo de los distintos **notebooks** proporcionados.
 No obstante, siempre es de agradecer la existencia de algún **ejercicio para practicar**; podéis encontrar los ejecicios para cada módulo en las siguientes carpetas:
 
   * [**Python Básico**](https://github.com/AfiQuants/Curso_Python/tree/main/Ejercicios/1.%20Python%20b%C3%A1sico)
   * [**Numpy**](https://github.com/AfiQuants/Curso_Python/tree/main/Ejercicios/2.%20Numpy)
   * [**Pandas**](https://github.com/AfiQuants/Curso_Python/tree/main/Ejercicios/3.%20Pandas)
   * [**Visualización**](https://github.com/AfiQuants/Curso_Python/tree/main/Ejercicios/4.%20Visualización)
   * [**Descarga de Datos**](https://github.com/AfiQuants/Curso_Python/tree/main/Ejercicios/5.%20Descarga%20de%20Datos%20-%20Web%20Scraping)
  
 ## Material Adicional
 Además del material proporcionado, podemos recomendar la realización de **distintos cursos**, como son los siguientes (sin ningún orden de preferencia):
 
   #### Cursos Gratuitos
   * [**Python and Statistics for Financial Analysis**](https://es.coursera.org/learn/python-statistics-financial-analysis)
   * [**Python Programming: A Concise Introduction**](https://es.coursera.org/learn/python-programming-introduction)
   * [**Data Processing Using Python**](https://es.coursera.org/learn/python-data-processing)
   
>*Cabe destacar que en muchos de ellos se repetirán temas ofrecidos aquí, o se tratarán de manera distinta.*

   #### Proyectos Guiados
   * [**Pandas Python Library for Beginners in Data Science**](https://es.coursera.org/projects/pandas-python-library-beginners-data-science)
   * [**Statistical Analysis using Python Numpy**](https://es.coursera.org/projects/statistical-analysis-using-python-numpy)
   
Por último, queremos recomendaros que, para cualquier duda que podáis tener, uséis los **omnipotentes**:

<div align='center'>
   <table><tr>
   <td> 
      <p align="center" style="padding: 10px">
         <a href="https://www.google.com/">
         <img src="https://www.google.es/images/branding/googlelogo/2x/googlelogo_color_160x56dp.png" width="320">
      <br>
         <em style="color: grey">Google</em>
      </p> 
   </td>
   <td> 
      <p align="center" style="padding: 10px">
         <a href="https://stackoverflow.com/">
         <img src="https://apifriends.com/wp-content/uploads/2018/04/stackoverflow.png" width="320">
      <br>
         <em style="color: grey">StackOverflow</em>
      </p> 
   </td>
   </tr></table>
</div>

Esperamos que todo el contenido os haya resultado de utilidad.

## Contacta con nosotros
En caso de cualquier duda o aclaración adicional, podéis contactar con nosotros libremente; nuestros perfiles de **Linkedin**:

<div align='center'>
   <table><tr>
   <td> 
      <p align="center" style="padding: 10px">
         <a href="https://linkedin.com/in/manuel-rueda-álvaro-8422b1141">
         <img src="https://github.com/mlrueda/My_Private/blob/main/Images/Manuel_Rueda.png?token=8107c3ee213a3426b04c954653634074e0ef24ca" width="150">
      <br>
         <em style="color: grey">Linkedin<br>Manuel Rueda Álvaro</em>
      </p> 
   </td>
   <td> 
      <p align="center" style="padding: 10px">
         <a href="https://linkedin.com/in/jos%C3%A9-javier-calder%C3%B3n-coronado-698b41b1/">
         <img src="https://github.com/mlrueda/My_Private/blob/main/Images/Javier_Calderon.png?token=8107c3ee213a3426b04c954653634074e0ef24ca" width="150">
      <br>
         <em style="color: grey">Linkedin<br>Javier Calderón<br> Coronado</em>
      </p> 
   </td>
   </tr></table>
</div>

¡Esperemos que os haya sido útil !

<div align="center">
   <a href="https://www.youtube.com/watch?v=wJO-MTh6NNo">
   <img src="https://blog.sagitaz.com/wp-content/uploads/2015/11/gracias.jpg">
</div>
