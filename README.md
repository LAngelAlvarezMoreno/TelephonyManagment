# TelephonyManagment

### Descripción
en el proyecto que se desarrolla se centra en abordar la gestion de datos telefonicos de la empresa, en la que al implementar una herramienta centralizada facilite sus labores a los colaboradores involucrados en la actividad.

### Problema Identificado
La creacion de un sistema que permita mitigar el riesgo de perdida de información, mantener ordenada la información y disponible un 99.9999% y evitar posibles fallos humanos al realizar reportes solicitados por dirección.

### Solución
- crear un sistema web dentro de la red privada de la empresa, en la que el administrador pueda registrar clientes y equipos telefonicos y ejecutar reportes
- permitir que usuarios del departamento de recursos humanos puedan visualizar información.
- crear una base de datos para el almacenamiento de la información
- crear servicios REST para la intercomunicacion del AppWeb y la base de datos
- generar un servidor Web para desplegar proyectos

### Arquitectura
El aplicativo se basa en una arquitectura web moderna, utilizados tecnologias .net Blazor para el frontend. 
Se crean servicios REST para realizar la integración con la base de datos. 
Se crea una base de datos SQL relacional para almacenar la información y la configuracion
