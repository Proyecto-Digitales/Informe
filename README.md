INFORME
Tema: Suma y resta octal implementado en app inventor
1.	PLANTEAMIENTO DEL PROBLEMA
Sumar y restar dos números en el sistema octal diseñando una aplicación para Android en app inventor que nos permita ingresar números decimales, convertirlos a octales, realizar el cálculo y nos indique el resultado tanto en decimal como en octal.
2.	OBJETIVOS
2.1	Objetivo general
•	Diseñar una aplicación en app inventor que permita sumar y restar números en sistema octal.
2.2 Objetivo específicos
•	Investigar como transformar de números decimales a números octales.
•	Investigar cómo realizar las operaciones de suma y resta en octal.
•	Mostrar los resultados en decimal y octal mediante una aplicación de app inventor.
3.	ESTADO DEL ARTE
Según (Siliceo, 2018) en su trabajo de Tesis realizado en la Universidad nacional autónoma de México estudio las operaciones aritméticas aplicadas a códigos binarios, octales y hexadecimales con su respectiva transformación para realizar y aplicar sus algoritmos correspondientes el cual nos indica cómo realizar operaciones aritméticas suma resta multiplicación y división en cada uno de los casos propuestos utilizando el algoritmo definido para cada caso y concluyo que podemos usar un mismo algoritmo para realizar transformaciones a cualquier base.
El trabajo expuesto por Siliceo indica que los códigos son importantes para el proceso de operaciones aritméticas adjuntando códigos indispensables, sin embargo, lo planteado por el autor recalca que se debe tomar en cuenta que cada caso es diferente por lo tanto se puede realizar transformaciones de diferente tipo. 


4.	MARCO TEÓRICO
Para comenzar tenemos que tener claro las siguientes definiciones 
 
5.	DIAGRAMAS
 
Figura 1. Diagrama parte 1
 
Figura 2. Diagrama parte 2
6.	LISTA DE COMPONENTES
•	App inventor
7.	MAPA DE VARIABLES
 
Figura 3. Variables de entrada
Tenemos tres variables globales que almacenaran los datos en decimal.
8.	EXPLICACIÓN DEL CÓDIGO FUENTE
El programa requiere la introducción de valores de tipo entero decimal y devuelve valores tipo entero decimal y octal en pantalla
9.   DESCRIPCIÓN DE PRERREQUISITOS Y CONFIGURACIÓN
Es necesario para la utilización del programa tener a disposición un dispositivo Android por lo cual debe tener habilitada la instalación de paquetes de fuentes desconocidas ya que la aplicación no es verificada por Play Store
10.	APORTACIONES
Uso de binarios de tres bits para la transformación a cualquier base en este caso a octal y decimal como se indica en la siguiente imagen que menciona (Alulema, 2020) en Circuitos digitales
 
Figura 4. Otro método de conversión
En app inventor para tomar valores de una cadena debe usar el siguiente bloque, el cual hace parte de los bloques integrados en el conjunto de bloques de “Texto”
 
Figura 5. Bloque utilizado en app inventor
La idea es que, extrae los caracteres que necesitan, que podrían ser 1,2 o 3 y para ello en la cadena de caracteres que va a estar representada por el valor en binario, se a de tomar los que se requieren indicando el inicio y su longitud (la máxima longitud es tres). Para recorrer la cadena de caracteres, es decir el valor en binario se puede usar un ciclo for o while.  
11.	CONCLUSIONES
•	Se diseño en la plataforma de App inventor el un código que nos permite sumar y restar números en sistema octal, además el usuario puede ingresar dos números en sistema decimal con el fin de transformar en sistema octal y presentar la suma o resta. 
•	Se determina que para la transformación de números en sistema decimales a sistema octal se lo realiza por divisiones sucesivas, como también de octal a decimal mediante el método de pesos.
•	La suma octal se lo realiza como la suma normal en decimales teniendo en cuenta que no se visualizaran números mayores o iguales a 8, además el procedimiento de la resta octal se requiere 8 unidades prestadas de la siguiente suma y se resta 1 unidad del prestador.
•	La aplicación desarrollada indica mediante la manipulación de botones de suma, resta y transformación de los diferentes sistemas el cual da un resultado propuesto ya sea en sistema decimal u octal. 
12.	RECOMENDACIONES
•	Se recomienda que para el uso de la App Inventor se debe tener conocimientos previos de lenguaje de programación como Java, C++, PYTHON. 
•	Es importante conocer cuál es la lógica de la transformación de un sistema decimal a octal y viceversa, con el fin de aplicarlo para el diseño del código.  
•	Es necesario tener conocimientos de diversos métodos para la suma de números en sistema octal, con el fin de comparar los métodos e identificar cual es el mas simple de aplicar. 
•	Se recomienda diseñar una interfaz amigable para el usuario con el objetivo de facilitar el uso de la aplicación y evitar confusiones al momento de utilizar la aplicación. 
•	Es preciso planificar un cronograma con diagramas de Grant en las diferentes aplicaciones que existen y para el desarrollo se recomienda el software Project. 
13.	CRONOGRAMA
 
Figura 6. Cronograma de actividades
14.	BIBLIOGRAFÍA

Alulema, D. (2020). Circuitos Digitales. Quito, Ecuador.
Floyd, T. (2006). Fundamentos de sistemas digitales. Madrid: Pearson.
Ricoy, A. (14 de Junio de 2020). Appinventor en español. Obtenido de https://sites.google.com/site/appinventormegusta/primeros-pasos
Siliceo, R. (2018). Algoritmo de las operaciones aritmeticas aplicadas a los codigos binarios, octal y hexadecimal con sus respectivas conversiones. Ciudad de Mexico.

15.	ANEXOS
 
Figura 7. Interfaz de la aplicación
 
Figura 8. Entorno de trabajo parte grafica
 
Figura 9. Entorno de trabajo parte de bloques
15.1 MANUAL DE USUARIO
Calc Octal manual de usuario
Tener en cuenta:
•	Al ingresar evitar el ingreso de caracteres que no sean números como por ejemplo letras o caracteres especiales.
•	El resultado de la suma de los números en sistema octal se debe leer de derecha a izquierda.

 
Figura 10. Interfaz de la aplicación

La interfaz cuenta con diversos títulos que describen las diferentes salidas de resultados y los botones con letra resaltada en color amarillo describen cuál es su función.

Una vez el usuario ingreso sus dos números en la interfaz, se deben presionar los botones en el siguiente orden:

1.	Al presionar el botón “De decimal a octal” nos transforma nuestros ingresados en sistema decimal.
2.	Al presionar el botón “Sumar decimal”, nos suma nuestros valores ingresados ya transformados en sistema decimal. 
3.	Al presionar el botón “Restar decimal”, nos resta nuestros valores ingresados ya transformados en sistema decimal. 
4.	Al presionar el botón de “Transformar a octal el resultado”, nos transforma nuestro resultado a sistema octal,


15.2 HOJAS TÉCNICAS
Ficha Técnica de Calculadora de Octal

Lenguaje de Programación

Lenguaje de programación	Programación orientada a objetos y base de datos
Software de edición y programación	App inventor II
Formato de empaquetamiento	.APK
Software	Móvil Android
Tabla numero 1: Especificaciones
La aplicación móvil por Calculadora de octal es desarrollada elementos de código (lenguaje) programación orientada a objetos.

Utilizando App Inventor II como plataforma de edición y desarrollo, el cual optimiza las funciones de la app con los sistemas operativos Android al utilizar en algunas funciones Java así como POO permite ofrecer algunas funcionalidades en navegadores de cualquier sistema operativo para dispositivos móviles de escritorio a través de un código QR.
