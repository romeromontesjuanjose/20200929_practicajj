**Intalación MongoDB:**

* Primeramente accederemos a la pagina de MongoDB mediante el siguiente link (   https://www.mongodb.com/try/download/community), una vez allí iremos al botón downloas en la parte inferior de la página web, con esto descargaremos el instalador de MongoDB.

* Al ejecutar el instalador pasaremos a la fase de instalación y nos aparecerá en pantalla una ventana a la que clickaremos siguiente y lo mismo haremos con la siguiente ventana. En la tercera ventana optaremos por hacer una instalación completa y en la cuarta seleccionaremos instalar MongoDB como un servicio, tras dar todos estos pasos nos saldrá una penúltima ventana en la que debemos DESELECCIONAR la opción de instalar MongoDB compass pues lo instalaremos aparte. Una vez se instale podremos personalizar mongo, esta pestaña puede ser rellena de distintas opciones, pero yo las dejare todas marcadas. Tras esto rellenaremos los datos solicitados por Mongo en caso de no tener una base de datos para crearla. Con esto finaliza la instalación y podemos cerrar Mongo.

* Ahora debemos añadir Mongo a la variable path del sistema para ello debemos llegar a la carpeta donde esta Mongo, acceder a bin y copiar el directorio. El directorio por defecto es “C:\Program Files\MongoDB\Server\ 4.2\bin. Tras esto hacemos click derecho a este equipo y accedemos a propiedades, despues entramos en configuracion avanzada lo cual nos abrira una ventana emergente donde debemos clickar varables de entorno allí accedemos a path y le damos a editar y a nuevo allí pegamos una ves hagamos esto le damos a aceptar e iniciamos una consola de comandos escribiendo cmd en el buscador de windows 10. En esta consola de comandos debemos escribir mongo y si la consola de comandos no nos da error habremos instalado el programa correctamente.