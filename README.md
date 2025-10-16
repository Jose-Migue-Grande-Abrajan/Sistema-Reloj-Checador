# Sistema-Reloj-Checador
Sistema web de control de asistencia para trabajadores que permite registrar entradas y salidas mediante formulario, código QR y servicios SOAP. Incluye visualización del historial en tiempo real y reloj digital, utilizando PHP, MySQL y Java con WebServices SOAP.

Tecnologías utilizadas:

- Java: Servicios web SOAP con WSDL, ejecutados en Tomcat.

- MySQL: Base de datos para almacenar los registros de asistencia.

- PHP: Para consumir los servicios SOAP y generar la interfaz web.

- HTML / CSS / JS: Frontend del sistema, incluyendo reloj digital, formularios y tablas.

- XAMPP: Entorno de desarrollo con Apache, MySQL y Tomcat.
- Configuración Java + Tomcat

El IDE debe estar integrado con Tomcat.

- Si se usa Tomcat de XAMPP, es necesario colocar el JAR de MySQL Connector en el directorio lib de Tomcat para que los servicios SOAP funcionen correctamente.

- Al abrir el proyecto en el IDE, asegúrate de volver a referenciar el JAR en la ubicación donde esté guardado.

- Consumo de servicio SOAP que se deben mantener los estilos predefinidos del proyecto al hacer echo de las respuestas.

Frontend:

- Utiliza JavaScript para el reloj digital y manejo de formularios.

- Los estilos CSS están incluidos y requieren conexión a Internet para cargar la fuente desde Google Fonts.

- Administrador: Permite conexión directa a la base de datos.

- No requiere cambio de usuario/contraseña por defecto.

Funciones principales:

Registrar eventos de los trabajadores:

- Entrada

- Salida de comida

- Regreso de comida

- Salida

- Registro mediante QR opcional.

- Visualizar historial completo de asistencia en tabla dinámica.

- Mostrar reloj digital en tiempo real.

Requisitos:

- XAMPP instalado con Apache, MySQL y Tomcat.

- PHP 7+
  
- Java JDK compatible con Tomcat.
  
-Conexión a Internet para cargar fuentes y estilos (opcional para offline si se agrega localmente).

Java JDK compatible con Tomcat.

Conexión a Internet para cargar fuentes y estilos (opcional para offline si se agrega localmente).
