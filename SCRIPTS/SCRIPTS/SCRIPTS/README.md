SCRIPTS UTILIZADOS

Durante las pruebas del laboratorio se utilizó un servidor HTTP temporal en el WEB Server para validar los perfiles de seguridad configurados en FortiGate.

SERVIDOR HTTP TEMPORAL

Se utilizó Python para levantar temporalmente un servicio HTTP mediante el puerto TCP 8080 dentro del entorno aislado de GNS3.

Este servicio se utilizó únicamente para validar la detección y bloqueo de intentos de SQL Injection mediante el perfil IPS, comprobar el bloqueo de archivos .exe mediante File Filter y generar tráfico de prueba para verificar los registros de seguridad de FortiGate.

El puerto TCP 8080 fue utilizado temporalmente durante las pruebas. La comunicación normal de los usuarios hacia el WEB Server está diseñada para realizarse mediante HTTPS por el puerto TCP 443.
