# cmi22

## ¿CUÁNTO SABES DE LOS HORÓSCOPOS?

Proyecto de Creación Multimedia Interactiva de la  Facultad de Bellas Artes de la Univesidad de Granada


# 1 Datos 

**Titulo** :  ¿Cuánto sabes de los Horóscopos?

*Web:**   (url github.io)

**Autor:** Laura Sánchez Poyatos

**Resumen** : Este proyecto se intenta demostrar tu conocimiento sobre los horóscopos a través de 15 preguntas.

**Estilo/género:**  Juego de Preguntas, conocimiento, astrología, horóscopos...

**Logotipo** : 



![logotipo](https://user-images.githubusercontent.com/106830381/172795459-4ef3a27b-3222-4334-b479-e0a3f76a735e.jpg)

**Probado en:** Hippani 5.1, Google Chrome

**Tamaño proyecto:** 21,1MB

**Licencia** Este proyecto tiene una Licencia CC Reconocimiento Compartir igual (CC BY-SA)

**Fecha** :  9/06/2022

# 2. Memoria del proyecto 

### 2.1 Storyboard: 
Este videojuego trata de mostrar tus conocimientos sobre los Horóscopos a través de una serie de preguntas en las que exis tres respuestas una de ellas correcta que te llevará a un pequeño juego en el que tendrás que elegir que símbolo corresponde a tu respuesta y moverlo hasta la caja situada abajo.  Al final del juego tendrás un resultado por cada pregunta correcta. El objetivo será conseguir el mayor numero de puntos posibles.  Máximo 300.  Por ortro lado, en el menú nos encontraremos dos apartados más en una especie de presentación de horóscopos y curiosidades.




![img1](https://user-images.githubusercontent.com/106830381/172800142-15af5dce-0033-4ff8-b244-ed9b02acccf0.jpg)
![img2](https://user-images.githubusercontent.com/106830381/172800145-4121e982-dd04-4564-af9e-4d3ea5fbd039.jpg)
![img3](https://user-images.githubusercontent.com/106830381/172800147-4df34329-ede8-494d-b1ba-912fc8b16c01.jpg)
![img4](https://user-images.githubusercontent.com/106830381/172800151-76addae6-933f-463d-9295-fb84a1ff046a.jpg)



### 2.2. Esquema de navegación 


![Esquema de navegación y storyboard Laura Sánchez Poyatos 2 E](https://user-images.githubusercontent.com/106830381/172800541-b4385930-dd97-4052-94c9-0c736758be64.jpeg)

Necesaria modificación por nuevas actualizaciones en su desarrollo.


# 3. Metodolog

Metodología de desarrollo de productos multimedia basado en una metodología de UX (User Experience)



### Etapa 1: Ideación de proyecto

**Investigación de campo**
En lo que es el diseño del videojuego no he tenido ningun referente en concreto, simplemente me he regido por el  prototipo de videojuegos de preguntas.
Por otro lado , a la hora de buscar la información para la realización de las preguntas si que he ido buscando información en páginas horoscopales y en uentas de redes sociales destinadas a ello. 

**Motivación de la propuesta** 
En cuanto se  explicó las diferentes propuestas de videojuegos yo desde un principio tenia claro  que  seria de  preguntas y respuestas. Tanto el tema como la realización de ello vino despu. A la hora de pensar temas tuve más dudas pero tampoco tardé mucho en elegir los horóscopos como el tema principal de este proyecto.
Aunque los horóscopos me llaman la atención he de decir que no soy una experta nata de ellos, de hecho se bastante poco, pero fue eso mismo un motivo para indagar mas en este tema.  Tanto los simbolos como las constelaciones, curiosi, fechas, características,etc.



**Publico / audiencia**

-  Mayores de   6 años, especialmente públic interesado en temas astrológico de este tipo.





### Etapa 2: Desarrollo / actividades realizadas

- Juego. 
Lo primero que hice para la realización de este juego fue buscar imágenes e información para hacerme una idea de como podria estructurarlo. Tras ello, realicé mi pantalla inicial en la que los simbolos horoscopales harían una abertura hacia el boton "EMPEZAR" de mi juego. Una vez hecho esto en la qque guí descubriendo y jugando con la linea de tiempo llegé a mi siguiente escena: "MENÚ", en la que la organicé en tres botones que llevarian a tes escenas diferentes; "HORÓSCOPOS" y "CURIOSIDADES" que a trabes de condicionales boolean realicé una presentación de  los  horóscopos que compondrian mi juego y curiosidades de ellos. Por otrolado, en el menú se encuentra el botón  "EMPEZAR" que daria comienzo a mi juego. Tras crear esta escena de creó un boton de "CONFIGURACIÓN" en el que se puede encontrar una lista para cambio de música y una barra para regular el sonido de esta y además yn tutorial con sus botones correspondientes de pause, reanudar y reproducir; además, cuando no se esté reproduciento el video habá una imagen. Para que la música de pudiese quitar el volumen y darselo se creó un boton en menú para ello.  Despues de esto comencé el desarrollo de mi juego en si, en el que seleccioné 15 preguntas cada una en una escena y para c ada una de estas preguntas 3 botones diferentes. De esos 3 botones uno es el correcto y los otros dos incorrectos.  Tras comentarlo con el profe me di cuenta de que era demasiado simple y escaso en el tema de programación e interacción y decidí que tras la respuesta correcta  estos botones se harian invisibles y se harian visibles otros 3 botones diferentes que serian los simbolos de las respuestas. De estos 3 botones 1 es el correcto y este a través de una función de movimiento y colisión al pulsarlo con el botón y arrastrarlo a la caja este pasará a la siguiente escena. Los otros dos botones incorrectos también pasarán directamente a la siguiente escena. Por último creeun contador para cada escena que tras cada respuesta correcta sumará 10 puntos. Creando una última escena "ESCENA FINAL" se encuentra el contador fimal en el que aparecerá la suma de la puntuación obtenida.




- Video
-Para el video  pimero importé un video extraido de youtube para poder darle funciones a los botones que correspondian a la reproducción del vodeo y a la barra de volumen y posteriormente una vez hecho el video tutorial tlo intercambié por este.
- Instrucciones y ayuda al usuario 
Para poder jugar a este juego simplemente hay que darle al botón empezar en el menú y hacer clic en el boton de la respuesta correcta que creas adecuada. En la segunda parte solamente pulsar en  la respuesta correcta mover hasta situar la imagen encima de la caja y volver a pulsar.
- Menús y elementos de navegación (botones)
El menú como anteriormente he dicho está compuesto por 5 botones; volumen, configuración, Horóscopos, Curiosidades y Empezar. Los botones posteriores al menú establecen cada uno una función. Los he querido difenrenciar en los blancos como respuestas, las imágenes como símbolos, y el botón cada de cada una de las escenas para volver al menú. En cuanto a la presentaciones los botonoes de las flechas para pasar de imagen donde se encuentran las funciones correspondientes para su funcionamient.

### Etapa 3: Problemas identificados
Dentro de los errores se encuentras modificadiones que en la exportación se han cnvertido en errores pero sin embargo el archibo reproducido en la aplicadión no existen esto y por otro lado dentro de esta aplicación al ampliarse la vista de la pantalla los botones de los símbolos de las imágenes se modifican, cosa que no he sido capaz de arregar. Y otro problema es el pause de la musica tras darle al botón empezar del menú.



# 4. Conclusiones 

Me ha parecido un proyecto muy interesante  por el poco tiempo sobre todo al final agobió un poco pero estoy muy contenta con el resultado. Considero que ante dodo problema he encontrado una solución que ha acabado mejorando mi proyecto. En lo que más complicación he encontrado ha sido el tema de la escena de configuración y  por otro lado,  la repetición de la creación de variables, funciones e interacciones ha requerido bastante esfierzo y concentración porque cuanquier error luego para rectificarlo era muy dificil al haber tantas variables. Me frustra bastante los errores y modificaciones que se producen al exportar el videojuego tanto como que la app al ser de pago era dificil seguir en casa pero aun así me quedo con un buen sabor de boca.







# 5 Referencias 

**Recursos y materiales audiovisuales:**

* Musica:  Musica ambiente
* Imágenes:  Goolgle Chrome
* Tipografía  ArialBlack 

**Herramientas utilizadas**

- Hippani Animator 5.1
-  Adobe PhotoShop 2022
-  Paint




Junio 2022
