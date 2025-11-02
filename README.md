###### Madelaine Reyes

# Trabajo de Investigación 

# 1. Diferencia entre HTTP y HTTPS

- **Explica qué significa cada sigla.**

  - _HHTTP (hypertext transfer protocol), es un protocolo de transferencia de texto o cojuntos de reglas de la comunicacion cliente-servidor._
  
  _**Es la tecnología subyacente que impulsa la comunicaión de red. es el protocolo seguro de transferencia de datos.**_  
    
    - _HTTPS (hypertext transfer protocal secure) es la version segura del http e incluye un sistema de cifrado para proteger la información trasmitida._
    
     _**Es una versión segura o una extensión de HTTP**_

- **Investiga cómo funciona el **cifrado SSL/TLS** en HTTPS.**

    - **HTPP**

     _Funciona como un protocolo de capa de aplicación en el modelo de comunicación de redes de interconexión de sistemas abiertos (OSI). Esto significa que la informacion enviada desde un navegador puede ser interceptada y leída por terceros. _
     
     Es como una carta sin sobre expuesta a terceros

    - **HTPPS**
     _Funciona como un protocolo donde cifra los datos entre el cliente (tu navegador) y el servidor,ya que los sitios web HTTPS deben obtener un certificado SSL/TLS de una autoridad de certificación (CA) independiente evitando que terceros puedan leer o modificar la información. 
     
     Es como una carta con sobre cerrado y con sello de seguridad.

- **¿Por qué HTTPS es más seguro?**

     _Porque tienen mayor seguridad a manejar los datos que se estan transmitiendo ya que tienen el certificado SSL/TLS esto es un objeto digital que permite a los sistemas verificar la identidad y poseteriomente tener una conexción de red cifrada. Además de su seguridad tambien esta su autoridad, rendimiento y análisis._

- **Muestra un ejemplo visual (puede ser una captura del candado del navegador).**



###### Madelaine Reyes

# Trabajo de Investigación 

# 1. Diferencia entre HTTP y HTTPS

- **Explica qué significa cada sigla.**

  - _HHTTP (hypertext transfer protocol), es un protocolo de transferencia de texto o cojuntos de reglas de la comunicacion cliente-servidor._
  
  _**Es la tecnología subyacente que impulsa la comunicaión de red. es el protocolo seguro de transferencia de datos.**_  
    
    - _HTTPS (hypertext transfer protocal secure) es la version segura del http e incluye un sistema de cifrado para proteger la información trasmitida._
    
     _**Es una versión segura o una extensión de HTTP**_

- **Investiga cómo funciona el **cifrado SSL/TLS** en HTTPS.**

    - **HTPP**

     _Funciona como un protocolo de capa de aplicación en el modelo de comunicación de redes de interconexión de sistemas abiertos (OSI). Esto significa que la informacion enviada desde un navegador puede ser interceptada y leída por terceros. _
     
     Es como una carta sin sobre expuesta a terceros

    - **HTPPS**
     _Funciona como un protocolo donde cifra los datos entre el cliente (tu navegador) y el servidor,ya que los sitios web HTTPS deben obtener un certificado SSL/TLS de una autoridad de certificación (CA) independiente evitando que terceros puedan leer o modificar la información. 
     
     Es como una carta con sobre cerrado y con sello de seguridad.

- **¿Por qué HTTPS es más seguro?**

     _Porque tienen mayor seguridad a manejar los datos que se estan transmitiendo ya que tienen el certificado SSL/TLS esto es un objeto digital que permite a los sistemas verificar la identidad y poseteriomente tener una conexción de red cifrada. Además de su seguridad tambien esta su autoridad, rendimiento y análisis._

- **Muestra un ejemplo visual (puede ser una captura del candado del navegador).**


    ![Candado de seguridad](https://github.com/Made-cloud/research-lab-api/blob/main/ejemplo%20de%20sitio%20no%20seguro.png)

- **¿Qué sucede si un sitio no usa HTTPS?**

    _Significa que no cifra la información que viaja entre tu navegador y el sitio web. esto trae demasiadas consecuencias:_ 
     
        - Los datos estan a la vista 👀.
        - Los sitios puenden ser falsificado 👩‍✈️.
        - Lo marcan como sitios no seguros 🔒.
        - Peor posicionamiento y no generan confianza 😕.

### **2. Puertos de comunicación**

- **Explica qué es un **puerto** en redes y por qué es importante para HTTP.**

    _Un puerto es un punto de acceso que permiten la transferencia de datos entres los dipositivos en una red, actuando como una interface específicas que direccionas el tráfico de informacion de una manera eficiente y organizada. 
    Esto es importante ya que ayuda a que facilita la identificación y organización._
    
    _Garantiza la comunicación, da seguridad y control de acceso, optimiza el rendimiento y tiene protocolos y servicios específicos._ 

- **Investiga el propósito de los puertos **80** y **8080**, y qué tipo de tráfico suelen manejar.**

    _ el prorposito del puerto 80 es un puerto determinado para el tráfico HTTP. Se utiliza para el transmitir paginas web sin cifrado entre un servidor web y navergador. Estos estan bloqueados por firewalls ni ISP._
    
    _El propósito del puerto 8080 es un puerto alternativo que se utiliza a menudo como puerto HTTP que sirve para servidores web y aplicaciones. Y no estan bloqueados por Firewalls ni ISP.

- Menciona **otros puertos conocidos** (por ejemplo: 21, 22, 443, 3306) y su función.
    ## Puertos  conocidos

    | Puerto conocido  | Right columns |
    | -------------    |:-------------:|
    | 22               | _SSH (Secure Shell) es un protocolo de red que proporciona una conexión segura para acceder y gestionar servidores remotos._|
    | 443              | _HTTPS (Hypertext Transfer Protocol Secure) es la versión segura del protocolo HTTP, utilizado para la comunicación segura a través de la red._      |
    | 110              | _Es el puerto utilizado por el protocolo POP3 (Post Office Protocol version 3), que se utiliza para recibir correo electrónico en un cliente de correo electrónico._    |



- **Ejemplo: ¿Qué puerto utiliza HTTPS por defecto?**

    _El puerto por defecto es el 443 utilizado para la comunicación segura a través de la red.



### **3. Códigos de estado de respuesta HTTP**

- Investiga qué son los **status codes** y para qué sirven.

    _Son indicaciones del resultado de una solucitud entre el cliente (navegador) y el servidor_
    _ Cda solicitud tiene **tres dígitos**, y el **primer número** representa su categoria._


- Crea una **tabla organizada por categoría**:


| **Categoría** | **Rango de códigos** | **Descripción** | **Ejemplos comunes** |
|----------------|----------------------|-----------------|----------------------|
| 🟦 **1xx – Informativos** | 100–199 | Indican que la solicitud fue recibida y el proceso continúa. | `100 Continue`, `101 Switching Protocols` |
| 🟩 **2xx – Éxito** | 200–299 | La solicitud fue procesada correctamente. | `200 OK`, `201 Created`, `204 No Content` |
| 🟨 **3xx – Redirección** | 300–399 | Se necesita una acción adicional, como redirigir a otra URL. | `301 Moved Permanently`, `302 Found`, `304 Not Modified` |
| 🟥 **4xx – Error del cliente** | 400–499 | Error causado por el cliente (malas solicitudes o falta de permisos). | `400 Bad Request`, `401 Unauthorized`, `403 Forbidden`, `404 Not Found` |
| ⬛ **5xx – Error del servidor** | 500–599 | El servidor no pudo procesar la solicitud correctamente. | `500 Internal Server Error`, `502 Bad Gateway`, `503 Service Unavailable` |

---

💡 **Ejemplos comunes:**
- ✅ `200 OK` → Todo funcionó correctamente.  
- 🚫 `404 Not Found` → El recurso solicitado no existe.  
- ⚠️ `500 Internal Server Error` → Error general del servidor.

_Estos códigos nos ayudara en el momento que este creando un proyecto ya que según ya con la información estudiada nos darán el error que se cometio y poder resolverlo de una manera mas eficiente._


### **4. Métodos HTTP**

Investiga los principales métodos HTTP utilizados en APIs RESTful:

- **GET**, **POST**, **PUT**, **DELETE**
    
    y responde:
    
    - ¿Qué hace cada uno?
        
        _**Get** se usa pra solicitar datos de un recurso, se puede: 
     se puede almacenar en caché, permanece en el historial del navegador, se pueden marcar, nunca se se debe usar para datos confidenciales, tiene restricción de longitud y solo se usa para pedir datos no modificarlos._
        
        _**POST** se utiliza para enviar datos a un servidor para crear o actualizar un recurso, esto siginifica: Las solicitudes nunca se almacena en el caché, no permanece en el historial del navegador, no se pueden marcar y no tiene restricciones en cunato a la longuitud de datos._

        _**PUT** se utiliza para enviar datos a un servidero para crear o actualizar un recurso la diferencia entre el post y el put es que en el pust puedes enviar una misma soliciyud varias veces siempre producirá el mismo resultado. En cambio el post a enviar una solicitud repetidamente causa efectos secundarios creando el mismo recurso varias veces._ 

        -_**DELETE** Elimina un recurso especificado._

         -_**HEAD** Es casi idéntico a GET, pero sin el cuerpo de respuesta, en otras palabras HEAD se usa para verficar si la información existe sin el contenido solo el encabezado._

        -_**PATCH** Se usa para aplicar modificaciones parciales a un recurso._

         -_**OPNTIONS* Describe las opciones de comunicación para el destino._

        -_**OPNTIONS* Describe las opciones de comunicación para el destino._

    - ¿En qué tipo de operación se usa (consultar, crear, actualizar, eliminar)?


        
        ※ _El GET se usa para consultar datos ya que este pide información a un servidor._

       ※ _El POST sirve para crear ya que este envia datos a un servidor._

        ※ _EL PUT sirve para actualizar ya que este permite enviar datos a un servidor repetidamente sin crear un recurso varia veces._

        ※_El DELETE sirve para eleiminar un recurso especifico._


    - Agrega un ejemplo práctico de cada uno con una URL o pseudocódigo.


        🌐 Ejemplos de métodos HTTP
        🔹 GET — Obtener información

        📥 Leer datos de un recurso

        GET /usuarios/123 HTTP/1.1

        Host: api.ejemplo.com


        💻 Respuesta del servidor

        HTTP/1.1 200 OK

        Content-Type: application/json

        {

        "id": 123,

        "nombre": "Ana",

        "email": "ana@example.com"

        }

        🔹 POST — Crear un nuevo recurso

        🆕 Enviar datos para crear un recurso

        POST /usuarios HTTP/1.1

        Host: api.ejemplo.com

        Content-Type: application/json

        {

        "nombre": "Carlos",

        "email": "carlos@example.com"

        }


        💻 Respuesta del servidor

        HTTP/1.1 201 Created

        Content-Type: application/json

        {

        "id": 456,

        "nombre": "Carlos",

        "email": "carlos@example.com"

        }

        🔹 PUT — Actualizar completamente un recurso

        ✏️ Reemplazar todos los datos de un recurso existente

        PUT /usuarios/123 HTTP/1.1

        Host: api.ejemplo.com

        Content-Type: application/json

        {
        "nombre": "Ana López",

        "email": "ana.lopez@example.com"

        }


        💻 Respuesta del servidor

        HTTP/1.1 200 OK

        Content-Type: application/json

        {

        "id": 123,

        "nombre": "Ana López",

        "email": "ana.lopez@example.com"

        }

        🔹 DELETE — Eliminar un recurso

        🗑️ Borrar un recurso específico

        DELETE /usuarios/123 HTTP/1.1

        Host: api.ejemplo.com


        💻 Respuesta del servidor

        HTTP/1.1 204 No Content


        ⚠️ El código 204 indica que el recurso se eliminó correctamente y no hay contenido que devolver.

### **5. Tema adicional sugerido: Cabeceras (Headers)**

    🔹 **¿Qué son los headers en una solicitud HTTP?**

    📌 _Los headers son información adicional que acompaña a una solicitud o respuesta HTTP.
    son Etiquetas de información que sirven para decirle al servidor o al cliente cómo intrepretar la solicitud._


    🔹 **¿Qué tipo de información contienen?**

    | Header            | Función                               | Ejemplo             |
    | ----------------- | ------------------------------------- | ------------------- |
    | **Content-Type**  | Tipo de datos enviados                | `application/json`  |
    | **Authorization** | Credenciales de autenticación         | `Bearer token12345` |
    | **User-Agent**    | Información sobre el cliente          | `MyApp/1.0`         |
    | **Accept**        | Tipo de datos que acepta el cliente   | `application/json`  |
    | **Cookie**        | Enviar cookies al servidor            | `sessionId=abc123`  |
    | **Host**          | Dominio al que se dirige la solicitud | `api.ejemplo.com`   |

🔹 **¿Por qué son importantes al consumir APIs?**

    Es importante ya que permiten una comunicación segura y eficiente entre el cliente y el servidor.

🔹 **Muestra un ejemplo de una solicitud completa con cabeceras incluidas.**

// Example of a random customer generator

var faker = require('faker'); // Faker.js

api.customer  = {

    id:    random.special(4, 8),

    name:  faker.name.findName(),

    phone: faker.phone.phoneNumber("(###) ###-####"),

    address: {

        street: faker.address.streetAddress(),

        city: faker.address.city(),

        state: faker.address.state(),

    }
};

Muestra el servidor 

{

  "customer": {

    "id": "04973560",

    "name": "Edwardo Lowe",

    "phone": "(934) 880-1066",

    "address": {

      "street": "498 Reichert Mountains",

      "city": "Rohanberg",

      "state": "Maine"

    }
  }

}

**Resumen de investigación**

_En conclusión luego de toda la información adquirida de la investigación sera util en los futuros proyectos que realizare ya que esto me ayudara a manejar la información que sera usada durante el servicio, igual el cifrado de datos cuando sea necesario ademas de poder a reconocer errores con los códigos estudiados tambien con los metodos de HTTP para recopilar, crear, actualizar y eliminar. Esto me ayudara a poder visualizar y solucionar los errores y manejar la información de una manera segura y eficiente._