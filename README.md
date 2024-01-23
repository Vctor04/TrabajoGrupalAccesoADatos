# Trabajo Acceso a Datos

Este proyecto trata de una aplicación en MVC la cual podremos listar, borrar, crear y editar en los apartados de categorias, libros, usuarios y prestamos.
Cada apartado tiene su ventana para visualizar los datos y asi mismo a la hora de crear, editar o borrar.

## Comenzando 🚀

Mira **Deployment** para conocer como desplegarlo nuestro proyecto.

Una vez descargado del proyecto deberás de instalarle las librerias correspondientes.

### Requisitos 📋

Este proyecto trabaja con java jdk 17.
Debes de usar la libreria de hibernate-search-5.8.o.Final-dist
Para la conexión a la base de datos mysql debes de usarel mysql-connector-j-8.2.0
Proyecto creado en el editor de código Intellij 2023.3.2 (Ultimate Edition) 

## Despliegue 📦

Para poder desplegarlo puedes descargarlo con:

_Comando de Git_

```
git clone https://github.com/Vctor04/TrabajoGrupalAccesoADatos.git
```

_Descargando el archivo desde Code_

```
<> Code y luego pulsar Download ZIP
```

### Instalación 🔧

1.Una vez descargado instalar las librerias en Proyect Structure.
2.Establecer conexión con el docker de mysql 
3.Lanzar el programa

## Ejecutando el proyecto Biblioteca 📚 

_Para lanzar el programa lo haremos desde el fichero Biblioteca, miramos que todo está conectado y iniciaremos sesión_


## Construido con 🛠️

* [Java]((https://jdk.java.net/17/)) - El lenguaje de programación usado
* [Maven](https://maven.apache.org/) - Manejador de dependencias
* [Hivernate]([https://rometools.github.io/rome/](https://hibernate.org/search/releases/5.8/))


## Correspondencia entre clases y tabla ⚙️
Para ello hemos usado _Docker_, dentor del _Docker_ nos conecectamos a la base de datos Mysql, y allí nos hemos creado la base de datos Biblioteca, con nuestras diferentes tablas, prestamos, libros, usuarios y categorías 


## Implementación del patron de diseño observer.


## Dificultades encontradas, y que soluciones habeis propuesto.⛔️

1. Daba error en un constructor en la clase PrestamosDTO que se había creado un constructor por defecto al generar la clase.
2. Problemas con las sesiones de que algunos métodos han necesitado una sesión individual.
3. A la hora de insertar un prestamo en la tabla prestamos, se creaba doblemente, para ello hemos modificado el método **grabarEnLogIns**.

## Autores ✒️

* **Raúl Pacheco** - *Implementación de Hibernate y correción de errores* - [RaulPachecoo](https://github.com/RaulPachecoo)

* **Pablo Corral** - *Patrón observer y correción de errores* - [Heylo03](https://github.com/Heylo03)

* **Víctor Chaves** - *Patrón observer y correción de errores* - [Victor04](https://github.com/Vctor04))
  
* **Rafael González** - *Documentación* - [rafael2347](https://github.com/rafael2347))

---
Recuerda si puedes soñarlo, puedes programarlo ⌨️
