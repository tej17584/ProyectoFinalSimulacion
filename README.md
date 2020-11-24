<h1 align="center">
<br>
  <img src="https://static.nationalgeographicla.com/files/styles/image_3200/public/bookstore-buenosaires-argentina.jpg?w=1900&h=1267" alt="UkronTadd" width="664"> 
<br>
<br>
Proyecto final Simulación: Librería Ateneo
</h1>
    
<p align="center">
  
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/static/v1?label=License&message=NoLicense&color=<COLOR>" alt="No license">
  </a>
</p>

<p align="center">University Project :mortar_board:</p>
<p align="center">Alejandro Tejada 17584</p>
<p align="center">Diego Sevilla 17238</p>
<p align="center">Modelación y Simulación</p>
<hr />

## Descripción

Este proyecto es parte del curso de modelación y simulación. 
El objetivo es simular la vida laboral de Michael.
Un librero que trabaja en la mejor librería del mundo: Ateneo Grand Splendid en Buenos Aires.
Él se encarga TODOS los días de ingresar libros en el sistema. Entre ellos, libros que se venden, libros alquilados y los propios claro. 
Michael calcula que en promedio, ingresa unos 20 libros al sistema por día. Ya que es un proceso super engorroso. También,  retorna de las mesas donde la gente lee un promedio de 50 libros al día. Y los que vende ascienden a unos 30. 
A veces, él quisiera vacaciones y piensa: "Ojalá supiera que tanto trabajo habrá en promedio para saber cuándo tomármelas". 

El proyecto, se trata de simular un día de Michael en el tiempo y calcular su mejor día de vacaciones. El periodo de tiempo es de 1 jornada laboral, es decir 1 día para cada iteración. Para cada situación se tomarán los siguientes valores.

* Venta de libros, **MU de 30**.
* Retorno de libros de mesas, **MU de 50**
* Ingreso de libros al sistema, **MU de 20**

Se realizarán simulaciones para las tres variables, a sabiendas de:
* Son eventos independientes ya que no influye si compran más, o menos que si alquilan más o menos que si ingresa más o menos. 
* Los tres experimentos mantienen el mismo margen de tiempo: 1 día equivale a 1 iteración. 

### Lista de herramientas y teoría:

- Python 3.8
- VS Code
- Distribución de Poisson
- Supuestos
- Mucha cafeína


### Archivos y distribución del proyecto

- `Proyecto.ipynb` THE LOGIC
  -  Es el jupyter notebook donde está la explicación de la simulación, resultados y gráficas.


### Referencias
* https://gist.github.com/sachinsdate/d48abefe2f75541c7d98f51599c927b0#file-poisson_sim-py
* https://www.w3schools.com/python/numpy_random_poisson.asp
* https://www.tutorialspoint.com/python_data_science/python_poisson_distribution.html
* https://stackoverflow.com/questions/17192158/nameerror-global-name-xrange-is-not-defined-in-python-3
