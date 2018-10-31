---
layout: beneficios
title: Seguridad
---

### Protección contra ataques de Cross Site Scripting (XSS)

Las vulnerabilidades XSS permite a los atacantes ejecutar comandos en el navegador de la víctima los cuales pueden robar las sesiones de usuario, dirigir al usuario hacia un sitio malicioso, entre otros.

**Mi Argentina** aplica técnicas de protección para resguardar a todos los usuarios de este tipo de ataques.

### Protección de datos sensibles

**Mi Argentina** permite que todas las conexiones sean seguras utilizando el protocolo seguro HTTPS con el fin de evitar que los atacantes puedan capturar tráfico de red y obtener el token de acceso.

### Protección contra redirecciones y reenvíos no validados

Con el fin de evitar cualquier redirección a sitios de phishing o malware, o redirecciones a sitios no autorizados, **Mi Argentina** requiere de forma obligatoria que todas las aplicaciones registren una URI de redirección. Al momento en que un cliente solicita a **Mi Argentina** una redirección, validará el URI de redireccionamiento con la lista de URIs válidas registradas.

### Protección contra Cross Site Request Forgery (CSRF)

Este ataque consisten en forzar a un usuario a ejecutar peticiones no deseadas a un sitio web en la que está autenticado sin que éste se de cuenta. Esto permite al atacante forzar al navegador de la víctima generar pedidos que la aplicación vulnerable piensa que son peticiones legítimas.
**Mi Argentina** aplica técnicas de protección para evitar este tipo de ataques.
