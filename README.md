# REST - Roy Fielding
Representational state transfer, es una arquitectura de software
basado en conultas por mdeio de URI's

# API
Aplication programing interface, es una interfaz de aplicación que permite
la interacción con datos por medio de URI's

# Representación
El cliente puede elegir la representación del recurso, ejemplo:
JSON, XML, HTML, etc.

# REST API
La importancia en implementar este modelo de interacción de
datos es de prescindir del tipo del dispositivo, sitema operativo
y lenguaje de programación para servir datos por medio de URI's

# Express req.params and req.query
Express es una biblioteca hecha en node que sirve un servidor
http, en la URI params representa datos custom y en la query
representa datos de opciones.\

# cripto.randomUUID()
Funciona en el windows y también lo incluye node, sirve
para generar un UUID en v4

# safeParse || safeParseAsyn
Son funciones que provienen de Zod, una libreria de
node para crear objetos

# CORS
Cross origin the resource sharing, error de usu compartido de 
recursos entre dominios, este es una cabecera que tienen los
navegadores cuando se solicita datos de un host a otro host
es una medida de seguridad para las api y para el cliente.
Cuando la peticion de recursos provienen del mismo dominio
no se envia la cabecera origin

# CORS PRE-Flight | OPTIONS
Es una cabecera previa que se envia al servidor antes de
enviar request put/patch/delete, de este modo el agente
confirma si existe estos verbos en el servidor

# Libreria Cors
Agrega asterisco a todos los metodos, no se recomienda
porque se expone todas las URI's

# Servor
Es una libreria para node que permite habilitar un host
local y publico para paginas web en desarrollo
