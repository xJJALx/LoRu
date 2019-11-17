###### Fecha creación del README: 13/11/2019
##### Componentes del equipo: Rafael Ruiz, Jhon Aristizábal  
___
###### Actualizado 14/11/2019 14:00  

Este será nuestro diario en el que quedará registrado la planificación, el seguimiento, y las reuniones de nuestro proyecto.  

Este es el vistazo principal de nuestro apartado de Cardboard.
![primeraImagen](imagesREADME/14_11_2019_1.png)  

Dentro del Cardboard se pueden apreciar las distintas secciones, entre las que se encuentran:  
- Tareas por hacer  
- En progreso  
- Hecho, necesario Revisar  
- Terminado, perfecto    
Así quedaría nuestro Cardboard actualmente:
![segundaImagen](imagesREADME/14_11_2019_2.png)  



## Reunión 1.
Tras la reunión numero 1, la primera de muchas, hemos avanzado gran parte del proyecto en temas de desarrollo y planificación de cara a futuro.  
    Para empezar, hemos pensado que es buena idea hacer los componentes en páginas separadas, para testear libremente y para tener menos líneas de código, para ser más precisos a la hora de escribir nuevas o cambiar continuamente la página.  
    Hemos empezado dialogando de por cual empezar, optando por los botones y la carta con la imagen. Lo hicimos por separado; los botones con hover y varios estados en el fichero llamado buttons.html con su respectivo buttons.css, y la carta con el fichero llamado card.html y card.css.  
    Los códigos creados por separado seran juntados al final con el fin de crear una sola página homogénea para entregarla con las directrices pedidas en el enunciado.

Hemos actualizado la pestaña de los cardboards, en la que hemos añadido nuevas columnas, las cuales son:  
- Ideas/Pensamientos (En la que unicamente escribiremos el resultado de los brainstorm)
- Prioridades (En la que se encuentran tareas por hacer pero que deben ser empezadas lo antes posible)  

También hemos desplazado las dos tarjetas que estaban en la columna de "En progreso" anteriormente ya que están completadas, además de las tarjetas de añadir las dos columnas que acabamos de crear.  

En la columna nueva "Ideas" hemos añadido los checkbox que queremos utilizar dinamicos, para que cuando los pulses cambie de color el componente (o la pagina completa), los indices de página, para que dentro de la pagina puedas navegar de abajo a arriba con botones redireccionados, y los colores que nos gustan ahora de los dos estados.  

En tareas por hacer hemos añadido el nombre de cada uno de los componentes que hay que realizar, ya que al principio no lo hicimos, y hemos desplazado a "en progreso" en los que estamos trabajando, que son los botones y la tarjeta con imagen.  

Este sería un resumen de la última actualización del cardboard:
![segundaImagen](imagesREADME/14_11_2019_3.png)  


Y por este día de trabajo y reunión hemos avanzado bastante. Siguiente reunión programada para el día 15/11/2019 después de mediodía.
###### Actualizado 14/11/2019 21:00 
___

###### Actualizado 15/11/2019 23:00 

La reunión programada para hoy, viernes 15 no se ha podido llevar a cabo por motivo de no coincidir en el horario.  
Aun así, hemos trabajado por separado, probando y testeando cosas para mejorar los componentes en los que estamos trabajando ahora, que son los botones y la tarjeta.
También hemos corregido alguna falta de ortografía del texto anterior y hemos añadido la captura de pantalla del Cardboard de ayer, que se olvidó adjuntarla.

###### Actualizado 15/11/2019 23:00 
___

###### Actualizado 16/11/2019 23:00 
## Reunión 2.

En esta segunda reunión hemos empezado decidiendo la estructura del código CSS, para que todo esté de la misma manera y ordenado sintácticamente igual. Lo haremos siguiendo este ejemplo  
body {  
    color: #000;  
}  
Estamos incluyendo espacios delante de la llave y detrás de los dos puntos (:) de cada sentencia.    

También hemos añadido a la columna "Ideas" la nota de añadir un botón checkbox con JavaScript para que cambie el color de toda la página, a la columna "Tareas por hacer" elegir otro fondo o quitar la marca de agua de la foto que tenemos actualmente.    
    
Hemos estado hablando sobre el botón que queremos hacer para que cambie toda la página a blanco y negro desde su estado normal que sería a color. Aunque es un poco complejo por ahora, esta idea esta en fase de pruebas.    
Se han movido las tarjetas desde "En progreso" a "Hecho, pero no revisado" del componente de los botones y el componente de la tarjeta ya que ya han sido creados, solo haría falta implementación en el codigo final, además de pequeñas modificaciones.  
Por motivo de esto, estamos trabajando actualmente en el componente de la barra de navegación tanto horizontal como vertical, y en el panel de información emergente (con su respectiva animación), por lo que ambas pasan a la columna "En progreso".    

En cuanto al css se refiere, también tenemos que valorar las variables globales que vamos a declarar en el código, aunque lo hemos dejado en segundo plano ya que ahora no influye en nada, por lo que lo haremos una vez tengamos todo el código maquetado

###### Actualizado 16/11/2019 23:00 
