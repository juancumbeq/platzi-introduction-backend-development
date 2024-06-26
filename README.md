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

  ## [FRONTEND, BACKEND AND FULL STACK]()
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
  <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/how-api-work.png?raw=true" width= "65%" alt="how-api-work">
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

A través de los endpoints se le pide información al dominio, por lo general, se nos devuelve la información empaquetada en un JSON.

  ### CRUD
CRUD es el índice de unas plabras clave, y en el protocolo HTTP tenemos métodos para llevarlas a cabo:
  * Create (crear) → POST.
  * Read (leer) → GET.
  * Update (actualizar) → PUT / PATCH. Put envía la totalidad de los datos, mientras que patch envía solo los datos destinados a actualizarse.
  * Delete (eliminar) → DELETE.


  ### Ejemplo de CRUD 
<p align="center">
  <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/end-points.png?raw=true" width= "65%" alt="end-points">
</p>

<br>
<br>

  ##  [INSOMNIA AND POSTMAN]()
  Postman e [Insomnia](https://insomnia.rest/) son dos aplicaciones que nos permiten consumir los recursos de una API, indicando las variables necesarias.

  Para probar el funcionamiento necesitamos un API, para ello, Platzi nos permite usar la suya: [Platzi API](https://fakeapi.platzi.com/). Es necesario revisar la documentación para entender cómo se han de configurar las peticiones. 

  * Las peticiones GET (lectura) no tienen información para enviar en el body.
  * Insomnia te permite modificar el nombre de las peticiones para identificarlas.
  * Si envías un identificador inexistente en la base de datos, recibirás un código de estado 404 NOT FOUND.
  * Para enviar una petición con el método POST, debes adjuntar la información en el body. Insomnia te permite modificar todos estos parámetros.
  * El identificador único lo asigna automátocamente la fakeAPI de Platzi.
  * Una tarea importante del backend es asegurar y validad la integridad de la información. Si no envías toda la información necesaria de una categoría, recibirás un código de estado 400 BAD REQUEST.
  * Una vez modifiques una categoría en la API conn PUT o PATCH, puedes consultarla con normalidad a través del método GET.

<br>
<br>
<br>

# BACKEND ON A DAILY BASIS
  ## [THE CLOUD]()
  * La nube es donde se alojan los servicios (código) para exponerlos, y que los clientes puedan hacer request (peticiones). Ofrecen servicios para distribuir y desplegar aplicaciones.
  * La nube es el ordenador de alguien más (tu proveedor). Tinen un CPU, una RAM y un SSD, como cualquier otro ordenador.
  * Los proveedores poseen granjas de servidores configurados (data centers) ubicadas en diferentes lugares del mundo.
  * Mientras más cerca estés al data center que te conectes, experimentarás menor latencia, por lo que los recurso llegarán con mayor rapidez.
  * Como parte de esa "nube", según la que escojas, puedes tener tu sistema replicado en diferentes lugares, y elegir en dónde estarán tus sistemas corriendo, y optimizarlos para desplegar tu aplicación.

  Proveedores más conocidos:
  <p align="center">
    <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/cloud-providers.png?raw=true" width= "65%" alt="cloud-providers">
  </p>

<br>
<br>

  ## [DEVOPS]()
  DevOps es un enfoque de colaboración y comunicación que fomenta la integración continua y la entrega continua de software. Se basa en la idea de que las áreas de desarrollo y operaciones deben trabajar juntas para lograr la entrega rápida y constante de software de alta calidad.

  <p align="center">
    <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/devops-concepts.webp?raw=true" width= "65%" alt="devops-concepts">
  </p>


  El objetivo de DevOps es mejorar la eficiencia y la efectividad de los procesos de desarrollo y entrega de software, reduciendo los tiempos de inactividad y los errores durante el proceso de implementación. Esto se logra a través de la automatización de tareas y procesos, la mejora continua de la calidad del software y la colaboración cercana entre desarrolladores y operadores.

  - Existe un workflow (flujo de trabajo) para hacer que el código trabajado de forma local llegue al servidor y exponer el servicio a miles de usuarios.

  - Las aplicaciones son expuestas a muchas zonas, potencialmente a todo el mundo.

  - El request del cliente tiene que estar lo más cerca posible al data center para reducir la latencia, y por ende, el tiempo de respuesta.

  - Git es un sistema atómico de control de versiones utilizado para crear repositorios de código. Github es un servicio de repositorios remotos.

  - Centralizamos nuestro código en un repositorio remoto (Github), al que los miembros del equipo de desarrollo equipo aportarán el código. La rama principal (main) tiene todo el código que debe cumplir estándares a través de pruebas, calidad y seguridad.
  Se denomina automation al rol de los desarrolladores que se encargan de realizar las automatizaciones para hacer las verificaciones en el código.

  - El servidor de repositorios nos ayuda a reunir desarrollo y operaciones; el repositorio remoto se conecta con la nube, ambos se comunican, y si cumplen con las pruebas, calidad y seguridad, se despliega la app y nos conectamos a esos servidores.

  - Así el equipo de desarrollo puede lanzar rápidamente y operar el código en producción, normalmente después se vuelve un flujo:
    - Plan (planificación).
    - Code (código).
    - Build (construcción)
    - Test (pruebas).
    - Release (lanzamiento).
    - Deploy (despliegue).
    - Operate (operar).
    - Monitor (monitorear).

  - Este flujo es la cultura de trabajo conocida como DevOps.

  <p align="center">
    <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/devops-stack.webp?raw=true" width= "65%" alt="devops-stack">
  </p>

<br>
<br>

  ## [THE SERVER]()
Dentro del servidor podemos implementar diferentes arquitecturas, las más conocidas son: SaaS, PasS e IaaS.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/devops-arch.png?raw=true" width= "65%" alt="devops-arch">
</p>

SaaS: Netflix. PaaS: Windows Azure. IaaS: Amazon Web Services.

- El servidor normalmente podemos implementar diferentes tipos de arquitecturas, existen tres tipos de arquitecturas principales.

- **Software as a Service** (software como servicio, SaaS):
  - No tienes control del estado de red, ni almacenamiento, ni los datos, ni sobre la aplicación en sí, pero puedes hacer uso de su servicio.

- **Platform as a Service** (plataforma como servicio, PaaS):
  - Tienes mayor capacidad de administración, comienzas a gestionar la aplicación y la data. Es la mas común a encontrar como backend developer. Te  permite distribuir tu aplicación, el código y controlar la data de la misma (bases de datos).

- **Infrastructure as a Service** (infraestructura como servicio IaaS):
  - Nos permite una todavía mayor capacidad de manejo. Tenemos que gestionar la aplicación, los datos, pero tambipen el runtine, el sistema operativo, etcétera. El proveedor sigue manejando la virtualización y servidores.

- **On-site**:
  - Te encargas absolutamente de todo, no dependes de un proveedor, sino que utilizas directamente el computador físico.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/arch-details.png?raw=true" width= "65%" alt="arch-details">
</p>

<br>
<br>

  ## [COOKIES AND SESSIONS]()
Las cookies son pequeños fragmentos de texto que los sitios web que visitas envían al navegador

Permiten que los sitios web recuerden información sobre tu visita, lo que puede hacer que sea más fácil volver a visitar los sitios y hacer que estos te resulten más útiles. En las Cookies podemos almacenar datos como:
  - De qué país te conectas
  - Preferencias como del idioma
  - Almacenar una sesión de login

  ### ¿Cómo funciona?
  - Desde el Cliente realizamos una solicitud al Servidor
  - Desde el servidor reconocemos el usuario y generamos una Cookie.
  - Esta Cookie se envía al navegador para que sea guardada.
  - Así se identifica un usuario.
  - Una vez almacenada, al momento que el cliente haga una petición al servidor, éste va a reconocer la cookie creada.
  - El Servidor podrá retornar una respuesta más apropiada a este cliente en especifico.

  ### Problema de las Cookies
Las cookies solamente funcionan entre navegador y servidor, si queremos utilizarlas en mobile apps, no serán compatibles.

Pero hay una alternativa que se llama JWT que funciona en mobile y en navegadores. .

  ### Json Web Tokens o JWT
Es un estándar abierto basado en JSON para la creación de tokens de acceso que permiten la propagación de identidad y privilegios. Por ejemplo, un servidor podría generar un token indicando que el usuario tiene privilegios de administrador y proporcionarlo a un cliente. El cliente entonces podría utilizar el token para probar que está actuando como un administrador en el cliente o en otro sistema.  El token está firmado por la clave del servidor, así que el cliente y el servidor son ambos capaces de verificar que el token es legítimo.

JWT (Json Web Tokens) es una tecnología que nos permite validar por medio de tokens las mismas características que las cookies pero en dispositivos móviles. Funciona tanto en dispositivos móviles como navegadores.

<br>
<br>

  ## [DATABASES]()
<p align="center">
  <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/server.png?raw=true" width= "65%" alt="server">
</p>
Una base de datos es una herramienta para recopilar y organizar información. Las bases de datos  pueden almacenar información sobre personas, productos, pedidos u otras cosas. Existen dos tipos de bases de datos: Relacionales y No Relacionales.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/bbdd.png?raw=true" width= "65%" alt="bbdd">
</p>

  ### Relacionales (SQL)
Se caracterizan por ser creadas con tablas que relaciona los datos con otros. usa SQL (Structured Query Language) que es un lenguaje de computación para trabajar con conjuntos de datos y las relaciones entre ellos. . Las BD relacionales más populares son:

  - MySQL
  - PostgreSQL
  - ORACLE
  - Microsoft SQL Server

Al trabajar todos con SQL, los frameworks aprovechan para trabajar con ORMS Object-Relational Mapping, que es una forma de abstraer la conexión a estas bases de datos, utilizando la POO (Programación Orientada a Objetos).

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/sql-orm.png?raw=true" width= "65%" alt="sql-orm">
</p>

  ### No Relacionales (No SQL)
Una base de datos no relacional es aquella que no usa el esquema tabular de filas y columnas que se encuentra en la mayoría de los sistemas de base de datos más tradicionales. en vez de SQL, usa un formato JSON o parecido. Las BD no relacionales más populares son:

  - MongoDB
  - Cassandra (Apache)
  - Couchbase

  ### Drivers
Por medio de los drivers el backend se comunica con las bases de datos.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/drivers.png?raw=true" width= "65%" alt="drivers">
</p>

También es importante tener en cuenta que el desarrollador backend no es quien administra el mantenimiento de las bases de datos, no gestiona backups, sincronización, etc, ésto lo hace el DB Admin. Sino que éste construye la lógica para consumir éste servicio por medio de los drivers.

  ### Proveedores de DB Administration
Ofrecen servicios para administrar las bases de datos en diferentes bases de datos y éstos cobran de acuerdo al servicio y puede salir más economico que crear un equipo para administrar toda nuestras bases de datos. Algunos son:
  - Heroku.
  - Firebase
  - Digital Ocean
  - Mongo Atlas
  - Couchbase Capella DBaaS

<br>
<br>
<br>

# BACKEND SCALABILITY
  ## [WHAT IS SCALABILITY?]()
En el momento en el que nuestro servidor donde tenemos alojada nuestra aplicación comienza a recibir demasiadas peticiones tiene a colapsar. En este momento sólo tenemos dos opciones: escalar verticalmente u escalar horizontalmente.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/vertical-vs-horizontal.png?raw=true" width= "65%" alt="vertical-vs-horizontal">
</p>

  ### Escalamiento vertical
Una forma de solucionar el problema es incrementar las prestaciones del servidor, es decir, aumentar la:
  - CPU
  - RAM
  - Disk

  #### Problemas
Esta solución de escalabilidad tiene tres problemas clave:

  - Costo: a medida que incrementamos las prestaciones del servidor, los costes de mantenimiento del mismo se elevan exponencialmente.

  - Difícil hacer downgrade: algunos proveedores una vez hemos ampliado las características de nuestro servidor no nos permite desescalar, es decir volver a la configuración anterior.

  - Disponibilidad: en el caso de que algo falle en el servidor, todo deja de funcionar, la solución a esto es el escalamiento horizontal.

  ### Escalamiento horizontal
En lugar de ampliar las características de un servidor lo que hacemos es replicar el que ya tenemos, es decir pasamos a tener 3 instancias del mismo servidor original.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/es-horizontal.png?raw=true" width= "65%" alt="es-horizontal">
</p>

Esta técnica resulta mucho menos costosa y permite hacer downgrade ya que si no necesitamos tantos servidores simplemente los deconectamos.

La gran ventaja del escalamiento horizontal radica en la disponibilidad, es decir, si alguno de los servidores falla, los restantes pueden asumir la carga de trabajo.

  ### Load Balancer
Es el intermediario que tiene conocimiento de nuestras instancias/servidores (al conjunto de servidores se denomina Clouster). Si un nodo(instancia) se cae o está saturado, el load balancer se encarga de desviar las peticiones hacia los nodos restantes.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/load-balancer.png?raw=true" width= "65%" alt="load-balancer">
</p>

  ### Problemas
Si tenemos la base de datos local en cada servidor los datos no se van a sincronizar, de modo que vamos a tener varias instancias distintas de la base de datos.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/database-server.png?raw=true" width= "65%" alt="database-server">
</p>

La solución radica en gestionar la base de datos fuera de estos servidores. Quizás como un servidor aparte que sirva como DB. Otra alternativa es la replicación.

<br>
<br>

  ## [WHAT IS REPLICATION?]()
En el escenario de partida tenemos varios servidores configurados en base a la escalabilidad horizontal, en cada uno de esos servidores tenemos la base de datos, lo cuál supone un problema ya que la data no se sincroniza entre si.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/initial-state.png?raw=true" width= "65%" alt="initial-state">
</p>

Una de las soluciones puede ser aislar la base de datos en un único servidor. Sin embargo, esto nos puede suponer "cuellos de botella". Una solución puede ser realizar escalamiento vertical sólo al servidor que tiene la base de datos.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/one-server-database.png?raw=true" width= "65%" alt="one-server-database">
</p>

Si nuestro sistema es lo bastante grande podemos hacer escalamiento horizontal de las bases de datos. Ya que si continuamos con la solución en el caso de que se caiga el servidor que contiene la base de datos, todo el sistema cae.

El escalamiento horizontal de las bases de datos consiste en instalar servidores dónde únicamente tenemos las bases de datos junto con un cluster que se encarge de gestionar las peticiones.

Sin embargo, todas las bases de datos siguen estando aisladas, lo que da pie a que cada una tenga datos diferentes.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/es-horizontal-databases.png?raw=true" width= "65%" alt="es-horizontal-databases">
</p>

Para solucionar el aislamiento de las bases de datos, cada vez que se realiza un escritura en una de las instancias de la base de datos se va llevar a cabo un proceso de sincronización conocido como replicación.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/replica-write.png.png?raw=true" width= "65%" alt="replica-write.png">
</p>

De esta manera, independientemente a qué base de datos se realize las operaciones de lectura, la data va a estar disponible.

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/replica-read.png.png?raw=true" width= "65%" alt="replica-read.png">
</p>

Una vez hemos aplicado la replicación en nuestro sistema, pasaríamos a tener una arquitectura como la siguiente:

<p align="center">
  <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/provider-offer.png?raw=true" width= "65%" alt="provider-offer">
</p>

Normalmente los proveedores de servicio de servidores ya nos proporcionan todo el sistema configurado, dando un sistema similar a:
<p align="center">
  <img src="https://github.com/juancumbeq/platzi-introduction-backend-development/blob/main/readme_images/es-horizontal-database-replication.png?raw=true" width= "65%" alt="es-horizontal-database-replication">
</p>






La replicación es un proceso mediante el cual los datos se copian y mantienen actualizados en múltiples bases de datos o servidores. Este mecanismo es esencial para mejorar la disponibilidad, la redundancia y el rendimiento del sistema. La replicación puede ser síncrona, donde las copias de datos se actualizan simultáneamente, o asíncrona, donde los cambios se propagan en intervalos regulares. En entornos de alta disponibilidad, la replicación permite que una réplica asuma el control en caso de fallo del servidor principal, garantizando la continuidad del servicio. También se utiliza para distribuir la carga de lectura entre varios nodos, mejorando así el rendimiento de las consultas. La replicación es fundamental en sistemas de bases de datos distribuidas, en la computación en la nube y en aplicaciones empresariales críticas, ya que asegura que los datos estén siempre disponibles y protegidos contra pérdidas.




Soluciones a desincronización de base de datos.
Aislar base de datos a un servidor en particular. Se le hace escalamiento vertical solo a la base de datos para evitar un cuello de botella.
Se puede hacer escalamiento horizontal a la base de datos con su propio load balancer para solventar el problema de la disponibilidad.
Cada vez que se realice escritura en una de las bases de datos, se realiza una sincronización para que el cambio ocurra en todas las bases de datos. Esto es conocido como replicación.
Normalmente el backend developer no se encarga de la parte de replicación y gestión de bases de datos, sino en la capa de los servidores y el escalamiento horizontal.


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