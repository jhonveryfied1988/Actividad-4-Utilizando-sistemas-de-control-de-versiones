El presente proyecto tiene como finalidad cubrir los siguientes aspectos en las funcionalidades de un software.

Historias de Usuario
Historia 1: Registro de Usuario
Descripción:
Como usuario, quiero poder registrarme en la aplicación proporcionando un correo electrónico y una contraseña para crear una cuenta.

Criterios de Aceptación:

El usuario debe proporcionar un correo electrónico válido.
La contraseña debe tener al menos 6 caracteres.
Debe mostrarse un mensaje de error si el correo electrónico ya está registrado.
Requisitos Técnicos:

Crear un modelo de usuario en MongoDB.
Implementar un controlador para el registro de usuarios.
Añadir una ruta para manejar la solicitud de registro.
Historia 2: Inicio de Sesión
Descripción:
Como usuario, quiero poder iniciar sesión en la aplicación proporcionando mi correo electrónico y contraseña para acceder a mi cuenta.

Criterios de Aceptación:

El usuario debe proporcionar un correo electrónico y una contraseña válidos.
Debe mostrarse un mensaje de error si las credenciales son incorrectas.
Debe generarse un token JWT si las credenciales son correctas.
Requisitos Técnicos:

Implementar un controlador para el inicio de sesión.
Añadir una ruta para manejar la solicitud de inicio de sesión.
Manejar intentos fallidos y bloquear al usuario después de 3 intentos fallidos.
Historia 3: Recuperación de Contraseña
Descripción:
Como usuario, quiero poder restablecer mi contraseña si la he olvidado para poder acceder nuevamente a mi cuenta.

Criterios de Aceptación:

El usuario debe proporcionar su correo electrónico registrado.
El usuario debe poder establecer una nueva contraseña.
Debe mostrarse un mensaje de error si el correo electrónico no está registrado.
Requisitos Técnicos:

Implementar un controlador para la recuperación de contraseña.
Añadir una ruta para manejar la solicitud de recuperación de contraseña.
