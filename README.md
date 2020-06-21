--------------------------     Español     --------------------------

# Calculadora-PHP-BD
App que consiste en una calculadora simple, hecha en PHP que va guardando resultados en BD MySQL, y te muestra coincidencias de resultados.

Esta app cuenta con dos ficheros PHP, uno de ellos (calcluadora.php), como Frontend, donde se plasman los dos campos de introducción de valores y los botones operadores, más un botón que borra los campos introducidos y otro que limpia los últimos resultados obtenidos en pantalla.

Además en este fichero se controlan los eventos de clickado de los botones y se llama a las funciones pertinentes, alojadas en el segundo fichero.

El segundo fichero consta de funciones que calculan la operación dada por los valores obtenidos más el botón de operador pulsado. Además de otra función que guarda el resultado reciente y lo compara con los resultados almacenados anteriormente, informando al usuario de las veces que ya ha sido mostrado su resultado o si es la primera vez que se muestra este mismo.

**INSTRUCCIONES BASE DE DATOS**
Esta app hace uso de base de datos MySQL, donde los resultados obtenidos se guardan en la tabla "calculadora", en tipo VARCHAR.
Estos son los datos de la BD para mi caso:

servername = "localhost";
username = "root";
password = "alumnado";
dbname = "prueba1";






--------------------------     English     --------------------------

# Calculator-PHP-BD
App consisting of a simple calculator , made in PHP that is storing results in SQL databases , and displays matching results .

This app has two PHP files, one of them ( calcluadora.php ) as frontend , where the two fields enter values ​​and operators buttons, plus a button that clears the input fields and other cleaning are reflected recent results obtained on the screen.

Also in this file clicked events of the buttons are monitored and calls on the relevant functions , housed in the second file .

The second file consists of functions that calculate the operation specified by the values ​​obtained over the operator button pressed. Plus another function that stores the recent results and the results compared with previously stored , informing the user of the time that has already been shown the outcome or is the first time that this same sample.

**DATABASE INSTRUCTIONS**
This app makes use of MySQL database where the results are stored in the table "calculadora" in VARCHAR .
These are the data of the BD for my case :

servername = "localhost";
username = "root";
password = "alumnado";
dbname = "prueba1";
