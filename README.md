# PoC-AEC
Este repositorio contiene las versiones en las que se desarrolló la prueba de concepto asociada al proyecto Automatic Evidence Collector.

El proyecto tiene como objetivo automatizar el proceso de recolección de evidencia. Dicho proyecto se comunicará con Google Classroom para recolectar evidencia de atributos de egreso de la UABC, y con Google Drive para almacenar dicha evidencia. 
Esta prueba de concepto presenta una interfaz gráfica con la que se pueden observar algunas de las funciones simuladas que estarán presentes en el proyecto.

- Diagramas de la arquitectura.
Dentro de la pequeña aplicación creada como muestra, se puede observar un menú que nos permite observar algunas opciones. 
El diagrama que mejor describe esta prueba de concepto es el siguiente:

![image](https://user-images.githubusercontent.com/108479596/188427840-6efc3087-4293-4d02-8626-15e8816a5845.png)

En la prueba de concepto diseñada se puede observar en su gran mayoría los metodos que permitirán el funcionamiento gráfico básico del proyecto.

Dentro del documento de Arquitectura tenemos otras clases relacionados con el control del proyecto, dado que estas clases están formuladas para comunicarse con las aplicaciones externas, no han sido desarrolladas, así como también las clases que guardan información.

![image](https://user-images.githubusercontent.com/108479596/188428091-09f02f9c-739b-466a-823d-3eacf1abc64e.png)

Por último, tenemos el siguiente diagrama que representa la comunicación con los distintos servicios a los que esta fuertemente ligado.

![image](https://user-images.githubusercontent.com/108479596/188427913-275715a8-020e-4523-a847-9507937d092f.png)

- Requerimientos para ejecutar el código.
La prueba de concepto fue desarrollada en C# para mostrar un funcionamiento gráfico. Para ejecutar el código será necesario algún compilador de C#.
La aplicación se realizó en Visual Studio 2019 a través de los formularios de Windows en .net Framework, por lo que si se cuenta con dicha versión será posible observar los diseños de las diferentes ventanas y ejecutar la solución abriendo el archivo con extensión .sln ubicado en la carpeta principal.

- Instrucciones para ejecutar el programa.
Descargar el zip correspondiente, descomprimir, ir a la carpeta bin, después Debug, y por último abrir la aplicación ejecutando el .exe en dicha carpeta.
