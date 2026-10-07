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

                                                