# proyecto-web-personal

03/02/2022 - Quiero que en la vista de móvil el fondo tenga un gradiente transparente-negro-transparente, para que se vean mejor las letras del centro de la pantalla. Cuando intento poner el color transparente con rgba, se ve blanco; cuando lo intento con hsla, ni siquiera se muestra el gradiente, no lo procesa.

04/02/2022 - Solucionado el problema del gradiente: se lo estaba aplicando al body, no al main.

05/02/2022 - Solucionados diversos problemas con el tamaño y posición del nav, el main, etc. Ahora mismo funciona, que no es poco.
Hay que poner el footer como fixed y ponerle un background, o no se va a ver (quizás moverlo a la parte inferior del nav...).