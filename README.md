# Gestor de horarios cesde

aplicacion web que permite gestionar los horarios de clase de un instituto.

## Introducción / Contexto

En muchas instituciones educativas, la gestión de horarios sigue siendo un proceso complicado. En el caso de CESDE, los profesores y administradores aún dependen de hojas de cálculo y registros manuales para organizar las clases, lo que genera errores, confusión y pérdida de tiempo. La falta de un sistema centralizado también dificulta la comunicación sobre cambios de horario, causando inconvenientes tanto para docentes como para estudiantes.

Para solucionar esta problemática, se propone el desarrollo de una aplicación web que automatice la gestión de horarios. Este sistema permitirá a los profesores visualizar y modificar sus clases en tiempo real, recibir notificaciones automáticas sobre cambios y acceder a un Chatbot de soporte para resolver dudas. Además, garantizará un acceso seguro mediante autenticación de usuarios.

Este documento explica el funcionamiento y alcance de la aplicación, detallando sus principales módulos y características. El objetivo es proporcionar una solución eficiente que facilite la administración de horarios en CESDE, mejorando la organización y comunicación dentro de la institución.


## Objetivos

**Objetivo General**  
Desarrollar una aplicación web para la gestión de horarios, enfocada en la asignación de clases y alertas en tiempo real.

**Objetivos Específicos**  
- OE1 – Implementar un sistema de autenticación que garantice la seguridad y el control de acceso de los usuarios, diferenciando roles y aplicando medidas como autenticación en dos pasos.
- OE2 – Desarrollar una plataforma web que permita a los profesores gestionar sus horarios en tiempo real, incluyendo la creación, modificación y visualización de clases.
- OE3 – Implementar un sistema de notificaciones y alertas en tiempo real para mantener informados a los docentes sobre cambios en los horarios. 
- OE4 – Integrar un módulo de soporte técnico basado en un chatbot que brinde asistencia a los usuarios y escale consultas a un administrador cuando sea necesario.

## Alcance del Proyecto (Scope)

**Qué se va a desarrollar:**  
- Inicio de sesión: Garantiza la autenticación segura de los usuarios mediante credenciales y roles diferenciados. Se implementará con autenticación basada en correo y contraseña, con opción de autenticación en dos pasos.

- Gestor de horario administrador y profesor: Permite tanto a los profesores como administradores crear, modificar, visualizar y compartir sus horarios en tiempo real mediante una interfaz web con calendario interactivo.

-Notificaciones: Envió de alertas sobre cambios en los horarios mediante correo electrónico y notificaciones en la plataforma.

-Chatboot:Chatboot integrado en la plataforma para resolver dudas frecuentes de los usuarios sobre el sistema.

**Qué NO se va a desarrollar en esta versión (fuera de alcance):**  
- Version movil o app movil

## Tecnologías y Herramientas (Tech Stack)

- **Frontend**: Streamlit, javascript, react.  
- **Backend**: Python, java.   
- **Base de datos**: PostgreSQL, sqlServer  
- **Otras herramientas**: Git, GitHub, Docker, Postman, Swagger, copilot, claude, chatgpt, gemini.

## Integrantes del Equipo

| Nombre                  | Rol principal              | Usuario GitHub     |
|-------------------------|----------------------------|--------------------|
| Daniel lema             | Líder / Backend            | @daniellema11    |
| Leidys aparicio         | Frontend Lead              | @dianabello22    |
| Alejandra correa        | Backend / Base de datos    | @alejacorrea     |
| victoria valero         | Backend                    | @VictoriaBel788  |