# Practica 1-DER2 Esta es mi primera práctica de los comandos :
1. pwd SIN PUNTOS NI MAYUSCULAS este comando es para revisar la ruta donde esta almacenaje actual.
2. ls SIN PUNTOS NI MAYUSCULAS este comando es para listar el contenido total del directorio.
3. git status. comando que sirve para revisar todos los cambios del proyecto.
4. git add . comando que prepara los archivos y cambios para adjuntar.
5. git commit -m " Ejemplo 1ra sesion de aprendizaje de comandos ". Este comando se usa como una bitácora.
6. git push SIN PUNTOS NI MAYUSCULAS. comando para enviar los archivos al repositorio remoto.
7. git pull SIN PUNTOS NI MAYUSCULAS. comando por si en algun momento sale un error al empujar algunas   
   referencias, intentamos ejecutarlo y nuevamente git push
8. git remote -v comando para revisar la URL del repositorio remoto.
9. git --online comando para ver commits recientes.
10. git branch comando para saber en la rama que estoy.

( NOTA: HOY 27/09/2026: Agendar mentoria ya que no se encuentra la casilla donde se debe pegar URL de envio de trabajos. )
R// No pude agendar para el día 28/09/2026 por que no aparece agenda disponible.  
dejaré un mensaje en "Slack", lo mas temprano posible. Aun asi continuaré con las lecturas.

COMO SOLUCIONAR POSIBLES ERRORES:

1. pwd arroja la direccón de almacenaje local donde se guarda el proyecto (Debería mostrar: /workspaces/    -nombre-de-proyecto) 

        R// EN CASO DE NO NAVEGAR AL PROYECTO:
        - ejecutar cd seguido de la ruta exacta a la carpeta que quiero ingresar, esta me la da pwd
    
        R// En caso de ser la dirección diferente   

        - Navegar al repositorio bifucardo o FORKEADO y (verifica que la URL tenga TU nombre de usuario).
        - Verifica que el repositorio exista en GitHub. 
        - Comprueba que tienes permisos para hacer push.
        
Domingo 27 y Lunes 28/09/2026 : En estos dos dias se hace una introducción a la lectura acerca de como funciona  
                                tecnicamente el sistema de internet. 

- R// Se concluye simplificando que internet es un sistema conformado por ruters y servidores a esto se le llama (RELACION CLIENTE-SERVIDOR),
 directamente funcionando con la conexión de los proveedores de servicio que a su vez, conecta los dipositivos ya sean computadoras ó telefonos móbiles qlos cuales envían y reciben los requerimientos devuelta Ejemplo: Música, videos, fotografías etc. teniendo en cuenta de que estamos hablando de comunicacion, no de máquinas. 
 La relación cliente servidor, son roles que pueden variar dependiendo de lo que se esté efectuando al momento, un PC actua como cliente, cuando este está requiriendo algún servicio en especifico, pero este actua como servidor cuando este comparte datos.  


VERBOS DE USO DIARIO :

1. GET: Recuperar información (por ejemplo, cargar tu feed) -- Cuando damos actualizar o descargar nuevas publicaciones
2. POST: Enviar nueva información (por ejemplo, publicar una foto o dar me gusta a una publicación)
3. PUT/PATCH: Actualizar información existente (por ejemplo, editar tu perfil)
4. DELETE: Eliminar información (por ejemplo, borrar un comentario)

CODIGOS DE ESTADO HTTPS
 
 1. 200 OK: Solicitud Exitosa 
 2. 404 No Encontrado: El elemento solicitado no existe, por lo general el servidor contesta esto cuando la publicaciòn fue eliminada.
 3. 401 No autorizado: No se ha iniciado sesión o no se tiene permiso. intentar acceder a saldo bancario sin iniciar sesión 
 4. 500 error interno del servidor: Fallo temporal en el servidor.

 INTERACCION CLIENTE SERVIDOR.

 PASO 1. Cliente (navegador) prepara la solicitud HTTP GET - LINEA DE SOLICITUD: GET / HTTP/1.1
 
 PASO 2. Encabezados como Host: nytimes.com 
         (HOST es todo elemento conectado a una red que genere un IP ) esta puede compartir, enviar y recibir recursos.

 PASO 3. Cookies opcionales o tokens de autenticación. (averiguar para que es esto).

VERBOS PRINCIPALES DE HTTP 

1. GET: Recupera Datos. R//: Pide al servidor información sin modificar nada. (GET /api/posts/feed)
2. POST: Enviar Nuevos datos. R//: Envia información al servidor para que sea guardada. (POST /api/posts).
3. PUT/PATCH: Actualiza datos existentes. R// Edita perfiles, fotografias o archivos ya creados en el servidor (PATCH /api/users/123/profile).
4. DELETE: Elimina datos. R// Le pide al servidor que borre algo. Eliminar un comentario de facebook, envia solicitud DELETE.(DELETE /api/comments/456).

07/10/2026.

APRTENDIENDO A ORGANIZAR PROMPTS EN MARKDOWN

EJERCICIO: Convierte esta solicitud no estructurada en un prompt claro y estructurado en Markdown:

-Quiero planear un viaje de 2 semanas a Japón incluyendo ciudades, actividades y presupuesto."

# VIAJE A JAPÓN.  
## TIEMPO DE ESTANCIA.
- SEMANA 1: Okinawa. 
- SEMANA 2 Nagasaki.
### ACTIVIDADES.
-SEMANA 1: Senderismo, rapel y viaje turístico por las partes mas icónicas e históricas de la ciudad incluido la alimentación y seguros de estadía.


-SEMANA 2: Navegar por los puertos más representativos, además de la visita a los ´restaurantes mas importantes de la zona´.  
### COSTO. 
 -SEMANA 1: 1450 euros sin vuelo incluido.

 -SEMANA 2: 1930 euros sin vuelo incluido.

                                                
  ## APRENDIENDO A ORGANIZAR TABLAS Y ESTRUCTURAR PROMPST EN MARKDAWN.

  * MOSTRAR barras verticales (|) separar columnas. 
  * GUIONES (-) definir encabezados.
  * :--- alinea a la izquierda
  * :---: centra
  *  ---: alinea a la derecha
  *  [XXXXXX] (URL) Enlace para referenciar fuentes o contenido directamente dentro de la indicación.

 ### EJERCICIO PRÁCTICO

-Crea una indicación en Markdown solicitando un esquema para una publicación de blog que incluya:

1. Referencias enlazadas a sitios oficiales
2. Tabla comparativa de tres plataformas de redes sociales (por ejemplo, Instagram, Twitter, TikTok)
3. Encabezados para organizar claramente las secciones
4. tablas, enlaces y encabezados para estructurar tu indicación de manera efectiva.


### SOLUCIÓN AL EJERCICIO ANTERIOR.

R//.


## RESUMEN

- Comparativo de tres redes sociales en tendencia.

## PLATAFORMAS (Redes Sociales)
- Instagram
- X(twitter) 
- Tiktok


## TABLA COMPARATIVA

|Instagram|X(Twitter)|Tiktok|
|:---:|:---:|:---:|
|fotos y videos cortos en alta definición|noticias y tendencias|Videos cortos y entretenimiento|
|Usuarios aproximados: 3.000 millones|Usuarios aproximados: 600 millones|Usuarios aproximados: 2.000 millones|
|[Instagram](https://www.instagram.com/)|[X](https://x.com/)|[Tiktok](https://www.tiktok.com/)|


# COMANDOS J/SON (JAVA SCRIPT OBJECTS NOTATION)

Un *OBJETO* es una coleccion de pares, denominados clave-valor encerrados entre llaves { }.
Cada clave es una cadena envueltas entre comillas simples y luego su valor correspondiente tambien entre comillas y separados por dos puntos ( : )

* EJEMPLO

  - {
  "username": "john_doe",
  "email": "john@example.com",
  "age": 28,
  "is_active": true
}

## Arreglos JSON.

Un *ARREGLO* es una lista de valores encerreados entre corchetes, [ ] tener en cuenta los valores de adentro deben estar entre " " comillas los numeros *NO*

* EJEMPLO

["manzana", "banana", "naranja"]

* EJEMPLO DE UN ARREGLO DE OBJETOS, COMO UN CATALOGO DE PRODUCTOS.

{
  "products": [
    {"id": 1, "name": "Laptop", "price": 999.99, "in_stock": true},
    {"id": 2, "name": "Mouse", "price": 29.99, "in_stock": false}
  ]
}

## REGLAS ClAVE de la Sintaxis JSON:

    - Usa comillas dobles para todas las claves y valores de cadena.
    - Separa los pares clave-valor con comas, pero *evita comas finales después del último ítem* .
    - Los números y booleanos no llevan comillas.
    - Se permiten objetos y arreglos anidados para estructuras de datos complejas.

## Errores Comunes a Evitar:
 
    - Falta de comillas en claves o cadenas.
    - Uso de comillas simples en lugar de dobles.
    - Comas finales después del último ítem.
    - Mezclar tipos de datos incorrectamente (por ejemplo, poner números entre comillas).


## Ejercicio Práctico 1.

Escribe JSON para un libro con los siguientes campos, prestando atención a:

     - Usar comillas dobles para claves y valores de cadena
     - No poner comillas en números o booleanos
     - Usar corchetes para arreglos 
     - Colocar las comas correctamente

*Campos:

1. title (cadena)
2. author (cadena)
3. publication_year (número)
4. genres (arreglo de cadenas)
5. available (booleano)
6. Tu JSON: (Intenta escribirlo antes de verificar la validación)

## R//

{ "Tittle":"Viaje al Centro de la Tierra"
  "Author":"Julio Verne"
  "publication_year": 1864
  "generes":["ciencia ficcion", "novela cientifica", "novela de aventuras"]
  "available": true 
}

## EJERCICIO PRACTICO 2.

El Desafío: Sistema de Hotel para Mascotas

Crea un objeto JSON principal que contenga la siguiente información:
1. Datos de la veterinaria (Cadenas y Booleanos):
	• El nombre del hotel (cadena).
	• La dirección física (cadena).
	• Si está abierto las 24 horas o no (booleano).
2. Mascota Registrada (Objeto Anidado):
	• Crea una propiedad llamada mascota que sea un objeto con:
		• Nombre (cadena).
		• Especie (cadena, por ejemplo: "Perro", "Gato").
		• Si tiene la vacuna de la rabia al día o no (booleano).
3. Detalles de la Estancia (Objeto Anidado dentro de Mascota):
	• Dentro del objeto de la mascota, añade un objeto llamado estancia que contenga:
		• Fecha de ingreso (cadena).
		• Habitación asignada (cadena, por ejemplo: "Suite Premium 4").
		• Si incluye servicio de peluquería o no (booleano).

## EJERCICIO PRACTICO 3.

 1. ejercicio de vuelo.

## EJERCICIO PRACTICO 4.

1. Crea un objeto llamado restaurante que contenga la siguiente estructura: 
   Datos generales: Nombre del restaurante y dirección (que debe ser un objeto con calle, ciudad y codigoPostal).

2. ​Menú: Un objeto anidado que tenga dos categorías principales: entrantes y
   platosPrincipales.

3. Platos con ingredientes: Cada categoría debe ser una lista (array) de
   objetos. Cada objeto representará un plato con su nombre, precio e ingredientes (los ingredientes deben ser una lista de cadenas de texto).

4. ​Reserva activa: Un objeto anidado dentro de restaurante llamado 
   ultimaReserva que contenga el nombreCliente, la hora y un objeto anidado de detallesMesa con el numeroMesa y el número de personas.