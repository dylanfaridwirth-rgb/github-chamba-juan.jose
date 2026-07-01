GitHub y manejo de datos de usuario en aplicaciones web
 
1. GitHub como herramienta de desarrollo
GitHub no solo sirve para guardar código, también es una herramienta clave en el desarrollo profesional.
Funciones adicionales importantes:
•	Commits: registros de cambios realizados en el proyecto 
•	Branches (ramas): permiten trabajar en distintas versiones sin afectar el proyecto principal 
•	Pull requests: sirven para revisar y unir cambios 
•	Issues: ayudan a organizar errores o mejoras 
Importancia en proyectos web
GitHub permite trabajar de forma ordenada, documentar avances y colaborar con otros desarrolladores sin perder control del proyecto.
________________________________________
2. Manejo de datos del usuario en el frontend y backend
El almacenamiento de datos puede dividirse en dos partes:
Frontend (lado del cliente)
•	Se ejecuta en el navegador 
•	Usa cookies o almacenamiento local 
•	Es más rápido pero menos seguro 
Backend (lado del servidor)
•	Se ejecuta en el servidor 
•	Maneja sesiones y bases de datos 
•	Es más seguro y controlado 
________________________________________

3. Cookies: aspectos técnicos
Además de guardar datos, las cookies tienen atributos importantes:
•	Expires / Max-Age: define cuánto tiempo duran 
•	Secure: solo se envían en conexiones HTTPS 
•	HttpOnly: evita acceso desde JavaScript (más seguridad) 
•	SameSite: protege contra ataques CSRF 
Ejemplo conceptual
Una cookie puede decir:
“Este usuario ya inició sesión y prefiere idioma español”
________________________________________
4. Sesiones: control del usuario
Las sesiones funcionan como una “identidad temporal” del usuario.
Elementos clave:
•	ID de sesión único 
•	Almacenamiento en el servidor 
•	Tiempo de expiración 
Ejemplo práctico
Cuando entras a una página y no te pide iniciar sesión en cada clic, eso es gracias a una sesión activa.
________________________________________







5. Eliminación de sesiones y cierre de sesión
Cerrar sesión no solo es salir del sistema, también implica:
•	Invalidar el ID de sesión 
•	Borrar datos almacenados 
•	Evitar reutilización de la sesión 
Esto es muy importante en:
•	Bancos 
•	Redes sociales 
•	Tiendas en línea 
________________________________________
6. Problemas comunes en el manejo de datos
Algunos errores frecuentes son:
•	Guardar contraseñas en cookies 
•	No cerrar sesiones automáticamente 
•	No proteger las cookies 
•	No usar cifrado 
________________________________________
7. Buenas prácticas
Para un buen manejo de datos se recomienda:
•	Usar sesiones para datos sensibles 
•	Limitar el tiempo de vida de cookies 
•	Implementar cierre de sesión automático 
•	Validar siempre la identidad del usuario 
________________________________________


Conclusión
GitHub es una herramienta esencial para el desarrollo web moderno, mientras que el manejo adecuado de cookies y sesiones permite almacenar y proteger la información del usuario. Aplicar buenas prácticas garantiza aplicaciones seguras, eficientes y confiables.
