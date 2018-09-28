### Ejercicio 3: En general, cualquier ordenador con menos de 5 o 6 años tendrá estos flags. ¿Qué modelo de procesador es? ¿Qué aparece como salida de esa orden? Si usas una máquina virtual, ¿qué resultado da? ¿Y en una Raspberry Pi o, si tienes acceso, el procesador del móvil?

El modelo de procesador que tiene instalado mi ordenador es Intel(R) Core(TM) i7-4510U CPU @ 2.00GHz, y solo tiene el flag vmx. La salida para el comando 

``egrep '^flags.*(vmx|svm)' /proc/cpuinfo``

[Captura de salida](https://raw.githubusercontent.com/jomaenfe/Ejercicios-IV1819/master/Capturas%20de%20pantalla/Ejercicio3.png)