### Ejercicio 2: Para la aplicacion que se está haciendo, escribir una serie de aserciones y probar que efectivamente no fallan. Añadir test para una funcionalidad, probar que falla y escribir el código para que no lo haga (vamos, lo que viene siendo un TDD).


En mi caso, la clase que voy a hacer es una representación simple de lo que sería mi aplicación. Lo que te permite es gestionar, crear y modificar eventos en una fecha concreta y con una duración concreta. 

En esta captura se puede ver que una de las funciones nos permite testear la modificación de una tarea, el requisito de esta función es que el string que se le pasa por argumento tiene que ser igual al que se modifica en la clase.

![Captura1](https://github.com/jomaenfe/Ejercicios-IV1819/blob/master/Sesion%204/Capturas%20de%20pantalla%20sesion%204/Ejercicio2_1.png?raw=true)

En la siguiente captura podemos ver como al ejecutar los test con pytest, los pasa sin ningún problema.

![Captura2](https://github.com/jomaenfe/Ejercicios-IV1819/blob/master/Sesion%204/Capturas%20de%20pantalla%20sesion%204/Ejecicio2_2.png?raw=true)

Para forzar un error en los test voy a cambiar la supuesta salida de la función por un número entero. Como tiene que retornar un array igual que el de entrada va a dar error. Esto se puede ver en las siguientes dos capturas.

![Captura3](https://github.com/jomaenfe/Ejercicios-IV1819/blob/master/Sesion%204/Capturas%20de%20pantalla%20sesion%204/Ejercicio2_3.png?raw=true)
![Captura4](https://github.com/jomaenfe/Ejercicios-IV1819/blob/master/Sesion%204/Capturas%20de%20pantalla%20sesion%204/Ejercicio2_4.png?raw=true)

### Ejercicio 3: Crear algún conjunto de scripts de test, usando tu lenguaje favorito, y ejecutarlos desde el marco de test más adecuado (o el que más te guste) para ese lenguaje.

Aprovechando el ejercicio 2, en el que he modificado una función de los test. He añadido más test a mi aplicación para que prueben sus diferentes funcionalidades. En la captura que se muestra debajo se puede ver como pasa los diferentes test. 

![Captura5](https://github.com/jomaenfe/Ejercicios-IV1819/blob/master/Sesion%204/Capturas%20de%20pantalla%20sesion%204/Captura3_1.png?raw=true)