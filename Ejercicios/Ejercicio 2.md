## Ejercicio 2


### (1) ¿Qué es un servidor HTTP?

Un servidor HTTP es un software o hardware. Su función es almacenar, procesar y entregar contenido web a los navegadores de los usuarios a través del protocolo HTTP (Hypertext Transfer Protocol). Cuando los usuarios ingresan una URL en sus navegadores, estos le envían una solicitud al servidor HTTP correspondiente. El servidor, a su vez, responde con los recursos solicitados, como páginas HTML, imágenes, videos, etc.

### (2)	¿Qué son los verbos HTTP? Mencionar los más conocidos

Los verbos HTTP son comandos que indican la acción que el usuario desea realizar en el servidor.
Los verbos más conocidos son: Get, Post, Put, Delete, Patch, Head y Options.

### (3)	¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers?

Un request es un mensaje enviado por el cliente al servidor que indica qué acción desea realizar. Una response es el mensaje que el servidor envía de vuelta al cliente en respuesta a su solicitud. Los headers son líneas de información que se envían junto con una request y una response. Proporcionan metadatos sobre la solicitud o respuesta.

### (4)	¿Qué es un queryString? (En el contexto de una url)

Un query string (cadena de consulta) es una parte de una URL que se utiliza para enviar datos adicionales al servidor. Generalmente, se encuentra al final de la URL, después de un signo de interrogación (?).

### (5)	¿Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?

El responseCode es un número de tres dígitos que el servidor envía al cliente como parte de la respuesta HTTP. Este código indica el resultado de la solicitud realizada y ayuda al cliente a entender si la acción fue exitosa o si hubo algún problema. Cada valor devuelto tiene un significado especifico:

•	1xx – Informativos

•	2xx – Éxito

•	3xx – Redirección

•	4xx - Error del Cliente

•	5xx - Error del Servidor

### (6)	¿Cómo se envía la data en un Get y cómo en un POST? 

En el Get los datos se envían en la URL, son visibles, y hay limitaciones en la longitud. En un POST los datos se envían en el cuerpo de la solicitud, no son visibles en la URL, y permiten enviar más información de manera segura.

### (7)	¿Qué verbo http utiliza el navegador cuando accedemos a una página?

Cuando accedemos a una página el verbo HTTP que se utiliza es GET.

### (8)	Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.

JSON es un formato ligero de intercambio de datos que es fácil de leer y escribir para los humanos, y fácil de analizar y generar para las máquinas. Es comúnmente utilizado en aplicaciones web para enviar datos entre el cliente y el servidor. Por ejemplo:

{
  "nombre": "Nicolás",
  "edad": 26,
  "ciudad": "Buenos Aires",
  "intereses": ["deportes", "música", "películas"],
  "direccion": {
    "calle": "Buen Viaje",
    "numero": 243
  },
  "contacto": [
    {
      "tipo": "email",
      "valor": "nicolas@example.com"
    },
    {
      "tipo": "teléfono",
      "valor": "+54 11 1234 5678"
    }
  ]
}


XML es un lenguaje de marcado que define un conjunto de reglas para la codificación de documentos en un formato que es tanto legible por humanos como legible por máquinas. A diferencia de JSON, XML utiliza etiquetas para definir la estructura de los datos. Por Ejemplo:


<persona>
  <nombre>Nicolás</nombre>
  <edad>26</edad>
  <ciudad>Buenos Aires</ciudad>
  <intereses>
    <interes>deportes</interes>
    <interes>música</interes>
    <interes>películas</interes>
  </intereses>
  <direccion>
    <calle>Buen Viaje</calle>
    <numero>243</numero>
  </direccion>
  <contacto>
    <item>
      <tipo>email</tipo>
      <valor>nicolas@example.com</valor>
    </item>
    <item>
      <tipo>teléfono</tipo>
      <valor>+54 11 1234 5678</valor>
    </item>
  </contacto>
</persona>

### (9)	Explicar brevemente el estándar SOAP

SOAP es un protocolo de comunicación que permite el intercambio de información estructurada en la implementación de servicios web. Utiliza XML como formato de mensajería y se basa en estándares abiertos, lo que facilita la interoperabilidad entre diferentes plataformas y lenguajes de programación.

### (10) Explicar brevemente el estándar REST Full

RESTfull es un estilo arquitectónico para el diseño de servicios web que se basa en un conjunto de principios y restricciones que permiten la comunicación entre sistemas. REST utiliza los métodos HTTP y se centra en la manipulación de recursos a través de sus representaciones.

### (11)	¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?

Los headers en un request HTTP son componentes clave que proporcionan información adicional sobre la solicitud que se está enviando al servidor. Estos encabezados pueden incluir detalles sobre el cliente, la naturaleza de los datos enviados, la autenticación, las preferencias de caché y mucho más. 