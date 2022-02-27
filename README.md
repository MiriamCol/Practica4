# Practica4 JAVASCRIPT
Miriam Colino Ruipérez- 201804334


-La página principal es: index.html y las secundarias: UltimasNoticias.html, Registrarse.html, IniciarSesion.html, Proyectos.html y Cotizacion.html

-La URL de inicio del portal web es: https://miriamcol.github.io/Practica4/

-En index.html nos encontramos con un nav con las 4 páginas secundarias. En el footer de la misma, debajo de las redes sociales, hay un botón que abre un pop-up de información.

-En Inicio de sesión, el email es el que el usuario quiera y la contraseña es: contraseña.

-En Proyectos.html, hay un "carousel slide" para ir pasando cada uno de los proyectos.

-En UltimasNoticias.html hay una alerta de información.

-Desde cualquiera de las páginas secundarias, se puede volver a la principal con el botón Home arriba a la derecha.

NUEVO:

-En Cotizacion.html se hace uso de una API de cotizacion en bolsa de la compañia Repsol. Hago fetch de la API en versión JSON de la página web: https://www.alphavantage.co/.
Se muestra una tabla con información diaria, semanal y mensual, en cuanto se pulse el boton correspondiente. Se leen los datos del JSON y se muestran en la tabla los 15 primeros datos de cada uno.
Si tarda en aparecer la tabla después de dar al botón, puede ser debido a que la API solo puede ser llamada en una frecuencia de 5 veces por minuto. 