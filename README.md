# Estadia_CentroEscolarr
Proyecto de estadia Tecnica donde se desarrollara mi Proyecto y el backend y la base de datos 

## CONTROL ESCOLAR-registro de Asistencia 
🧩 Problemática-
Las instituciones de educación media superior, la asistencia se registra manualmente esto puede  generar  errores en los registros de asistencia

##💡 Propuesta de solución
Implementar un sistema web que permita registrar automáticamente las asistencias de los estudiantes mediante su número de NIA. El sistema divide los registros por grado y grupo, presenta listas organizadas por fecha y permite que los administradores consulten los accesos de forma rápida y confiable.

## Objetivo general
Desarrollar e implementar el módulo backend del sistema web de gestión de asistencia mediante códigos QR para el Centro Escolar General Rafael Cravioto Pacheco, que procesará los datos de escaneo, gestionará el almacenamiento de información, generará reportes automatizados y garantizará la comunicación segura con el frontend, con el propósito de optimizar el control de asistencia, reducir errores manuales y proveer información confiable para la toma de decisiones institucionales. 

##🎯 Objetivos específicos
1.Automatizar el registro de asistencia por NIA.
2.Dividir registros en listas por fecha, grado y grupo.
3.Proteger las rutas mediante autenticación con JWT.
4.Mostrar registros en tablas responsivas con filtros por fecha.
5.Implementar una interfaz de inicio de sesión segura.
6.Permitir el cierre de sesión y almacenamiento del token.

## ⚙️ Tecnologías utilizadas
Backend (API RESTful)
Node.js : entorno de ejecución de JavaScript en el servidor.
Express.js – Framework minimalista para crear rutas y gestionar peticiones.
MongoDB – Base de datos NoSQL orientada a documentos.
Mongoose – ORM para la interacción con MongoDB.
JWT (JSON Web Token) : sistema de autenticación de tokens.
Dotenv – Para la gestión de variables de entorno.
CORS – Control de acceso a recursos de la API.
Nodemon – Herramienta de desarrollo para reinicio automático del servidor.

## Funcionalidades principales
🔐 Autenticación
Inicio de sesión con verificación de credenciales desde MongoDB.
Protección de rutas del backend usando middleware verifyToken.
Almacenamiento seguro del token JWT en localStorage.
Cierre de sesión con limpieza de token.
📋 Registro de asistencias
Captura del número de NIA y registro automático del alumno.
Almacenamiento del grupo, grado, hora, semestre y si hubo retardo.
Registro dinámico y organizado por fecha y hora.
📄 Visualización y filtros
Visualización de listas filtradas por fecha, grado y grupo.
Tablas detalladas para los grados 1°, 2° y 3°.
Filtro dinámico por fecha de asistencia.
Consultas disponibles por semestre y grado.
 ## Base de Datos 
Registros de los alumnos de 2 semestre y de 4 semestre 
 ## 👥 Equipo de Desarrollo
|Integrante|Contacto|Rol|Observaciones|
|------------|--------|---|---|
|Carlos Isaac Fosado Escudero |[@CarlosFosadoo](https://github.com/CarlosFosadoo)|Lider del Desarrollo del Backend y de la base de datos|✅ Revisado y aprobado|
