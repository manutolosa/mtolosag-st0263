# info de la materia: ST0263 Temas especiales en telemática
#
# Estudiante(s): Manuela Tolosa Gracia, mtolosag@eafit.edu.co
#
# Profesor: Edwin Nelson Montoya Múnera, emontoya@eafit.edu.co
#

# Procesos comunicantes por API REST, RPC y MOM
#
# 1. breve descripción de la actividad
#
<texto descriptivo>
En este proyecto, desarrollé dos microservicios mserv1 y mserv2 que se comunican con  API Gateway a través de RPC y MOM. Usamos REST API  y gRPC para RPC y elegimos MOM para  RabbitMQ. Los microservicios se centran en enumerar y buscar archivos. Cada microservicio tiene un archivo de configuración que se carga al inicio. MOM se utiliza como respaldo en caso de problemas de comunicación RPC. Implementó una puerta de enlace API  en Node.js usando Express para probar la funcionalidad de sus microservicios. En resumen, este proyecto permite una comunicación sólida y flexible entre microservicios para proporcionar servicios relacionados con archivos.


## 1.2. Que aspectos NO cumplió o desarrolló de la actividad propuesta por el profesor (requerimientos funcionales y no funcionales)

# 2. información general de diseño de alto nivel, arquitectura, patrones, mejores prácticas utilizadas.
Se trató de implementar la arquitectura planteada por el profesor, en la cual se tiene el Postman que se conecta al API Gateway mediante el API rest , el API Gateway tiene dos conexiones, la primera con el servidor 2 y están conectados a través de la comunicación gRPC y la segunda conexión es con el servidor 1 y entre esa conexión esa la conexión con el servidor MOM.

# 3. Descripción del ambiente de desarrollo y técnico: lenguaje de programación, librerias, paquetes, etc, con sus numeros de versiones.

## como se compila y ejecuta.
## detalles del desarrollo.
## detalles técnicos
## descripción y como se configura los parámetros del proyecto (ej: ip, puertos, conexión a bases de datos, variables de ambiente, parámetros, etc)
## opcional - detalles de la organización del código por carpetas o descripción de algún archivo. (ESTRUCTURA DE DIRECTORIOS Y ARCHIVOS IMPORTANTE DEL PROYECTO, comando 'tree' de linux)

## 
## opcionalmente - si quiere mostrar resultados o pantallazos 

# 4. Descripción del ambiente de EJECUCIÓN (en producción) lenguaje de programación, librerias, paquetes, etc, con sus numeros de versiones.

# IP o nombres de dominio en nube o en la máquina servidor.

## descripción y como se configura los parámetros del proyecto (ej: ip, puertos, conexión a bases de datos, variables de ambiente, parámetros, etc)

## como se lanza el servidor.

## una mini guia de como un usuario utilizaría el software o la aplicación

## opcionalmente - si quiere mostrar resultados o pantallazos 

# 5. otra información que considere relevante para esta actividad.

# referencias:
<debemos siempre reconocer los créditos de partes del código que reutilizaremos, así como referencias a youtube, o referencias bibliográficas utilizadas para desarrollar el proyecto o la actividad>
## sitio1-url 
## sitio2-url
## url de donde tomo info para desarrollar este proyecto

