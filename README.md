# EjercicioJavaMySQL_Maven_1.00

Como los últimos ejercicios subidos en éste repositorio, éste es un ejercicio sencillo de administración de base de datos con Java mediante
una interfaz gráfica.

En este ejercicio en particular se incorpora a las funcionalidades del EjercicioSencilloMySQL_Maven una nueva que consiste en otra forma de
generar informes PDF. 

De manera que ahora tenemos dos formas de generar informes PDF, mediante la librería Jasper y mediante iTextPDF. 

Para generar documentación mediante Jasper tendremos el botón 'Generar Informe', y para hacerlo mediante iTextPDF el botón 'Generar PDF'. 
Éste último guarda por defecto el PDF en el escritorio. 

El programa en Java está desarrollado con NetBeans.

La base de datos -llamada sistema- es de tipo localhost. Para realizarla usé mediante XAMPP el phpmyadmin (la dirección http://localhost/phpmyadmin/ en un navegador, y aparte el XAMPP Control Panel abierto con el Apache y MySQL iniciados).

El puerto es en mi caso el habitual, el 3306.

La base de datos que yo cree se llama 'sistema', y dentro de ella cree una tabla (con la que trabaja el programa) llamada 'usuario'. La tabla usuario tiene 5 columnas: Id, Nombre, Apellidos, Edad, Correo.

Para acceder a la base de datos y su tabla yo tengo de nombre de usuario simplemente 'root' y no puse contraseña.

Si desea probarlo con otro puerto (si no es el habitual 3306 para MySQL) y con otro nombre de base de datos, tabla, usuario o contraseña, tendrá que ir al paquete del programa 'modelo', luego a su clase 'Modelo', y ahí en el método 'Conexion()' hacer las modificaciones pertinentes.

El programa se ejecuta desde la clase 'Principal', no desde el JFrame Form 'Vista'.

Un saludo.


