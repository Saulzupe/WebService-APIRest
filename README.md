# WebService-APIRest
![APIs](https://github.com/Saulzupe/WebService-APIRest/assets/62227970/7a81192b-4b1e-409a-8c9f-6e2c12e12526)


## Descripción ✍️
Esta es una APIrest que permite administrar un catalogo de cursos por lo cual puedes utilizar el cliente que desees. Es un proyecto
educacional la cual me permitio introducirme a los conceptos de JAAS, JAX-RS y JAX-WS o webservices. El catalogo muestra un listado de 
cursos almacenados en una base de datos de MySQL permite observar el titulo del curso, descripción, instructores y duración. Cuenta con
una relación ciclica pero a la vez se soluciona el problema de recursividad. También se implementa RESTEasy. Este proyecto puede
servir para una aplicación de registro de cursos o un sitio web que muestre la oferta de las escuelas.

## Estado del proyecto.
✔️ El proyecto ha sido finalizado ✔️ 

## 🛠️ Funcionalidades del proyecto
Funcionalidad 1: Implementa el metodo GET para mostrar los diferentes Cursos registrados.
Funcionalidad 2: Cuenta con Seguridad JAAS, por lo cual se necesita hacer un login y estar autenticado para poder realizar diferentes tareas.
Funcionalidad 3: Podemos realizar una peticiones http como POST, PUT, DELETE para administrar los cursos.
Funcionalidad 4: La administración de los cursos va depender del rol del usuario que se encuentre registrado.
Funcionalidad 5: Se puede implementar en cualquier cliente

## 📁 Acceso al proyecto
- Realizar un fork o descargar y descomprimir el zip.

#### Pequeña demostración.

![api1](https://github.com/Saulzupe/WebService-APIRest/assets/62227970/84dbb73a-d09f-4253-91a4-5ccd24b480c5)
![api3](https://github.com/Saulzupe/WebService-APIRest/assets/62227970/aee681bd-a22d-4bb6-90ec-f8f5a1437b26)
![api2](https://github.com/Saulzupe/WebService-APIRest/assets/62227970/a6869dd7-fbea-4d76-9707-fcd5d112f5d9)

## 🛠️ Abre y ejecuta el proyecto
* Descargar e Instalar el servidor Wildfly.
* Crear usuarios en la aplicación.
 - Abrir la terminal    
 - Dirigirse a la ruta de instalación del servidor  ejemplo: `cd D:\TuCarpeta\Wildfly-preview-25.0.0.final\bin`.
 - Ejecutar el comando: `.\add-user.bat` (dependera del sistema puede ser .sh windows o bash unix)
 - Seleccionar la opción: `Application User` (letra b)
 - Ingresar nombre de usuario y contraseña.
 - Confirmar los datos ingresados.
 - Colocar los roles (Debes ingresarlos con Mayuscula)
 - Confirmar con enter. [Repetir los pasos si desea registrar más usuarios]
 

## 👨‍💻 Tecnologías utilizadas.
* Java 19.
* Hibernate
* Jakarta JPA
* MySQL
* JAAS
* RESTEasy
* MAVEN
