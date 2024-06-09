# Introduction to Backend Development

<p align="center">
  <img src="https://img.shields.io/badge/Curso%20-Finalizado-brightgreen"/>
</p>

<br>

## What did I learn through this course:


<br>

# INDEX


# WEB DEVELOPMENT ROLES
  ## BACKEND DEVELOPMENT ROLES
  ## FRONTEND, BACKEND AND FULL STACK
# BACKEND FOUNDATIONS
  ## HOW THE BACKEND IS BUILD?
  ## HOW TO CHOSE THE LANGUAGES AND FRAMEWORKS FOR THE BACKEND?
  ## HTTP
# REST APIS
  ## WHAT ARE THE APIS?
  ## REST API STRUCTURE
  ## INSOMNIA AND POSTMAN
# BACKEND ON A DAILY BASIS
  ## THE CLOUD
  ## DEVOPS
  ## THE SERVER
  ## COOKIES AND SESSIONS
  ## DATABASES
# BACKEND SCALABILITY
  ## WHAT IS SCALABILITY?
  ## WHAT IS REPLICATION?
  ## WHAT IS THE CACHE?
  ## TASK QUEUE
  ## SERVER-SIDE RENDERING
# NEXT STEPS
  ## WHAT TO LEARN NOW?
# AUTHOR




## Demo

[Click this link to check the finished website]()

<br>
<br>
<br>

# WEB DEVELOPMENT ROLES
  ## [BACKEND DEVELOPMENT ROLES]()
Your primary role as a Backend Developer involves writing code related to:

  * Business rules
  * Validation
  * User authorization
  * Database connections
  * Code that runs on the server side
  * A Backend Developer may also be involved in other roles such as:

**DB ADMIN**

  * Manages a database, its policies, and how we will access that database through the code, as well as the security measures that should be in place.

**SERVER ADMIN**

  * Responsible for managing the security of the servers where the code is deployed.

  <br>
  <br>

  ## [FRONTEND, BACKEND AND FULL STACK]()
En este apartado hacemos una diferenciación entre las areas de backend y frontend. Ya que cómo desarrolladores backend vamos a desarrollar servicios, los cuales los clientes se conectarán, entre los distintos clientes encontramos:

  * Browsers
  * Mobile devices
  * IOT

  ### Clientes (Frontend)
- Navegadores
  - HTML y Markdown
  - CSS: Tailwind, Bootstrap o Foundation
  - JS: Angualar, React, Vue

- Mobile
  - IOS: Swift o Objective C
  - Android: Kotlin o Java

- CrossPlatforms
  - React Native
  - Flutter
  - .NET MAUI

  ### Backend
Tenemos un amplio abanico de lenguajes, los cuáles normalmente van acompañados de un framework que nos permite escribir código más ágil.

- Python - Django
- JavaScript - Express
- TypeScript - NestJS
- Ruby - RubyRails
- PHP - Laravel
- Java - Spring
- Go - Gin
- C# - .NET

  ### APIS
La manera en la que se conectan la parte del cliente con el backend es mediante las APIS.
 

  ### Fullstack
Este rol en la combinación entre un frontend y un backend developer.
<br>
<br>
<br>

# BACKEND FOUNDATIONS
  ## [HOW THE BACKEND IS BUILD?]()
  * Los usuarios se conectan través del cliente de un dispositivo (ya sea un navegador, dispositivo móvil, etc…).
  * Se realiza una solicitud en el frontend a través del cliente.
  * En el listado de solicitudes, cada posible solicitud es conocida como un endpoint.
  * La API (application programming interface) es la encargada de recibir la solicitud y hacerla llegar al backend, a lo que el frontend espera una respuesta.
  * El backend recibe la solicitud y dispara una respuesta con el endpoint correspondiente.
  * Las bases de datos porporcionan la información que requiere el backend para satisfacer la solicitud hecha por el cliente.
  * Las librerías son herramientas (piezas de código) pre-fabricadas por otros desarrolladores, que pueden ser importadas al proyecto para evitar la necesidad de crear código ya existente (no hay que reinventar la rueda).
  * Los framework son un conjunto de librerías que en conjunto conforman un marco de trabajo utilizado para responder a una necesidad específica existente en un proyecto.

<br>
<br>

  ## [HOW TO CHOSE THE LANGUAGES AND FRAMEWORKS FOR THE BACKEND?]()
Lo principal es escoger un lenguaje en el cual especializarte, acorde a sus características y tus preferencias, luego de aprender el lenguaje, puedes profundizar aun mas en uno o varios de sus framework.

Cada framework (en su mayoría) se utiliza para montar servidores web, los cuales disponen de varios funcionalidades, las cuales se ejecutan sobre el protocolo HTTP.



Frameworks son herramientas que nos ayuda a ir más ágil y desarrollar nuestro proyecto en el dia a dia. entre ellos tenemos para Python:

Django

Flask

FastAPI

En JavaScript

Express

NextJS

En PHP

Laravel

Symphony

En Java

Spring
En Go

Gin
En Rubi

Ruby Rails
En C#

.NET


Django: es un framework de Python que se enfoca en el desarrollo rápido y en la seguridad. Es muy completo y viene con un montón de herramientas y características que facilitan la creación de aplicaciones de backend.

Flask: es otro framework de Python que es muy ligero y flexible. Es ideal para proyectos más pequeños y para aquellos que desean tener un mayor control sobre su código.

Ruby on Rails: es un framework de Ruby que ha sido muy popular en la comunidad de desarrollo web. Es conocido por su enfoque en la productividad y en la facilidad de uso.

Express.js: es un framework de JavaScript basado en Node.js que es muy popular para el desarrollo de aplicaciones web y de API.

Spring: es un framework de Java que se enfoca en la creación de aplicaciones empresariales escalables y seguras.

Estos son solo algunos ejemplos de frameworks para backend, hay muchos más disponibles dependiendo de la plataforma y del lenguaje de programación que elijas. Es importante evaluar cuál es el mejor para tu proyecto en particular, teniendo en cuenta tus necesidades y preferencias personales.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/languages-frameworks.png?raw=true" width= "65%" alt="Frameworks">
</p>

<br>
<br>

  ## [HTTP]()
  ### URL structure
Cuando queremos acceder a un recurso de internet lo hacemos a través de una URL. La URL se compone de diversas partes, como son: protocolo, dominio y end-point.

Protocolo: tenemos http y https, la "s" indica que toda la comunicación hacia el dominio indicado está cifrada, por lo que representa un protocolo más seguro.

Dominio: hace referencia a la página web a la que solicitamos el recurso, mediante el protoco DNS ese dominio se traduce a una dirección IP que hará referencia a un servidor específico, en el que se encuentra alojada la web a la que queremos acceder, así como todos los recursos extra.

End-point: mediante esta elemento podemos acceder a un recurso o servicio en concreto. El servidor se encargará de procesar la petición en referencia a un end-point en particular, recogiendo todos los recursos requeridos y retornándolos al cliente.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/url.png?raw=true" width= "100%" alt="Url structure">
</p>

  ### Request-Response structure

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/request-response-structure.png?raw=true" width= "100%" alt="request-response-structure">
</p>

Las respuestas por parte del servidor pueden venir en varios formatos. Cómo podemos ver pueden ser archivos para renderizado (HTML, CSS y JS) o archivos de datos (XML, JSON)

  ### Http codes
El rango de 1xx indica información hacia los clientes.
<p align="center">
  <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/1xx-codes.png?raw=true" width= "65%" alt="1xx-codes">
</p>

El rango de 2xx es el rango más usado, e indica éxito en la petición.
<p align="center">
  <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/2xx-codes.png?raw=true" width= "65%" alt="2xx-codes">
</p>

El rango de 3xx es el rango usado para indicar a los clientes que se han movido recursos. De esta manera podemo redireccionar al usuario a otra página web.
<p align="center">
  <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/3xx-codes.png?raw=true" width= "65%" alt="3xx-codes">
</p>

El rango de 4xx indica errores por parte del cliente. El error más común es el 404, donde el cliente solicita una página web que no existe.
<p align="center">
  <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/4xx-codes.png?raw=true" width= "65%" alt="4xx-codes">
</p>

El rango de 5xx indica errores por parte del sevidor. Por ejemplo, el error 504 indica que se consumido el tiempo para retornar el recurso solicitado al cliente.
<p align="center">
  <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/5xx-codes.png?raw=true" width= "65%" alt="5xx-codes">
</p>

Resumen de los http codes:
<p align="center">
  <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/status-code.png?raw=true" width= "65%" alt="status-code">
</p>
<p align="center">
  <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/http-status-code.png?raw=true" width= "65%" alt="http-status-code">
</p>


<br>
<br>
<br>

# REST APIS
  ## [WHAT ARE THE APIS?]()
Las APIs son interfaces que nos permiten, a través de código, la comunicación entre sistemas. Como backend developers, nos interesan las APIs que son servicio web y corren en el protocolo HTTP. La API utiliza una lista de rutas conocidas como endpoints, que provee las respuestas a las solicitudes del cliente. La solicitud debe ser empaquetada y retornada, y existen distintos tipos de empaquetado: JSON. XML.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/how-api-works.png?raw=true" width= "65%" alt="how-api-works">
</p>

Un vistazo a lo que es un Rest API:
<p align="center">
  <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/api-def.png?raw=true" width= "65%" alt="api-def">
</p>

<br>
<br>

  ## [REST API STRUCTURE]()

REST (Representational State Transfer) API es un estilo de arquitectura de software que se utiliza para construir servicios web. Una API REST es una interface que se utiliza para interconectar sistemas o aplicaciones, y permite que estos sistemas o aplicaciones envíen y reciban datos entre sí a través de la red.

Una API REST se basa en el protocolo HTTP, y utiliza operaciones HTTP como GET, POST, PUT y DELETE para realizar diversas acciones sobre los datos almacenados en un servidor. Estas operaciones son conocidas como métodos HTTP, y corresponden a las acciones CRUD (Create, Read, Update, Delete) que se pueden realizar sobre los datos.

Por ejemplo, si tienes una aplicación web que almacena información de contactos, podrías utilizar una API REST para permitir que otras aplicaciones accedan y utilicen los datos de tus contactos. La aplicación podría exponer una API REST que permita a otras aplicaciones realizar operaciones como crear un nuevo contacto, obtener la lista de todos los contactos, modificar la información de un contacto existente o eliminar un contacto.

Una API REST se utiliza a menudo para construir servicios web que pueden ser utilizados por diversas aplicaciones o sistemas, y es una forma común de permitir la integración entre diferentes sistemas y plataformas.



API REST es un estandar para desarrollar APIs que funcionan en el protocolo HTTP .
A través de los endpoints se le pide información al dominio, por lo general, se nos devuelve la información empaquetada en un JSON.
CRUD es el índice de unas plabras clave, y en el protocolo HTTP tenemos métodos para llevarlas a cabo:
Create (crear) → POST.
Read (leer) → GET.
Update (actualizar) → PUT / PATCH.
Delete (eliminar) → DELETE.
Put envía la totalidad de los datos, mientras que patch envía solo los datos destinados a actualizarse.



La diferencia entre PUT y PATCH es:

PUT == enviará todos los datos
PATCH == enviará los datos que se están actualizando




<br>
<br>

  ## [INSOMNIA AND POSTMAN]()

<br>
<br>
<br>

# BACKEND ON A DAILY BASIS
  ## [THE CLOUD]()

<br>
<br>

  ## [DEVOPS]()
   dfshdhasdassdasfsadf
<br>
<br>

  ## [THE SERVER]()

  <br>
  <br>

  ## [COOKIES AND SESSIONS]()

  <br>
  <br>

  ## [DATABASES]()

<br>
<br>
<br>

# BACKEND SCALABILITY
  ## [WHAT IS SCALABILITY?]()

  <br>
  <br>

  ## [WHAT IS REPLICATION?]()

  <br>
  <br>

  ## [WHAT IS THE CACHE?]()

  <br>
  <br>

  ## [TASK QUEUE]()

  <br>
  <br>

  ## [SERVER-SIDE RENDERING]()

<br>
<br>
<br>

# NEXT STEPS
  ## [WHAT TO LEARN NOW?]()

<br>
<br>
<br>

# AUTHOR

This project was developed by *Juan Cumbe*. If you have any questions or suggestions about the project, feel free to contact me via [e-mail](mailto:hello@juancumbe.com) or my [Linkedin](https://www.linkedin.com/in/juancumbeq/) profile. 