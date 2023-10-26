# CircleTalk 
<h5 align="center">Circle Talk: ChatMultiUsuario</h5>

CircleTalk es un proyecto de chats/red social desarrollado en Django, permite que los usuarios creen su cuenta, la editen, inicien sesión y puedan platicar con otros perfiles registrados.

## ¿En qué consiste?

Este proyecto es un Chat desarrollado en Django (Framework de Python). El entorno virtual se ha configurado cuidadosamente para asegurar una experiencia de desarrollo óptima y segura. La tecnología utilizada incluye Python, JavaScript, HTML, Bootstrap/CSS, jQuery y MySQL. Todas las páginas del sitio web son dinámicas y gestionables por administradores.

## Características destacadas

- Administrador: Puede agregar nuevas páginas o información de contexto para los usuarios y puede manejar y administrar los usuarios registrados en la base de datos
- Usuario: Puede crear una cuenta, cambiar su información de su perfil, y comenzar chats en tiempo real con otros usuarios.

## Ventanas

Ventana Principal y Ventana de Información:
<p align="center">
   <img src="https://github.com/Nivaniz/WebChat/blob/main/imagenesweb/Main.png" alt="Main" style="width: 40%;">
    <img src="https://github.com/Nivaniz/WebChat/blob/main/imagenesweb/Paginas.png" alt="Páginas" style="width: 40%;">
</p>

Ventana de Perfiles:
<p align="center">
   <img src="https://github.com/Nivaniz/WebChat/blob/main/imagenesweb/Perfiles.png" alt="Perfiles" style="width: 40%;">
</p>

Ventana de Edición de Perfil:
<p align="center">
  <img src="https://github.com/Nivaniz/WebChat/blob/main/imagenesweb/EdicionPerfil.png" alt="Edición de Perfil" style="width: 40%;">
</p>

Ventana de Inicio de Sesión:
<p align="center">
  <img src="https://github.com/Nivaniz/WebChat/blob/main/imagenesweb/InicioSesión.png" alt="Inicio de Sesión" style="width: 40%;">
</p>

Ventana de Registro:
<p align="center">
  <img src="https://github.com/Nivaniz/WebChat/blob/main/imagenesweb/Registro.png" alt="Registro" style="width: 40%;">
</p>

Ventana de Mensajes:
<p align="center">
   <img src="https://github.com/Nivaniz/WebChat/blob/main/imagenesweb/Mensajes.png" alt="Mensajes cuenta" style="width: 40%;">
</p>
<br>
<p align="center">
   <img src="https://github.com/Nivaniz/WebChat/blob/main/imagenesweb/MensajesChat.png" alt="Mensajes chat" style="width: 40%;">
</p>

## Ejecución 

Es necesario tener instalado los requerimientos necesarios para ejecutarlo posteriormente con `python manage.py runserver` desde la terminal en el directorio de la carpeta clonada. Una vez realizado es necesario abrir localhost:8000 para visualizar el sistema.

### Instalación

Para poder utilizar el proyecto o modificarlo puedes:

1.- **Clonar el repositorio en tu máquina local:**
`git clone https://github.com/Nivaniz/WebChat.git`
*(Hay que tener todos los requerimientos previamente instalados)*

2.- **Crea un entorno virtual e instala las dependencias necesarias.**

3.- **Configura la base de datos y realiza las migraciones.**

4.- **Ejecuta el servidor de desarrollo de Django.**

5.- **Navegar en el directorio del proyecto:**
`cd webplayground`

6.- **Instalar las dependencias necesarias:**
`pip install -r requirements.txt`

## Uso y cómo acceder al administrador

Para acceder al área de administración, sigue los siguientes pasos:

El sistema mediante el cual se maneja con localhost:8000/admin, para poder acceder a la ventana de administrador necesitas crear una cuenta desde la CMD o BASH utilizando `winpty python manage.py createsuperuser` para crear super usuario.

## Notas

Por cuestiones de seguridad la funcionalidad de SECRET_KEY, y contraseñas especificas están privadas. Es necesario que si quieres utilizarlo insertes tus credenciales necesarias para el correcto funcionamiento de la página accediendo a settings con contraseñas de acceso propias.

## Autoría

¡Tus contribuciones son bienvenidas! Si encuentras errores o mejoras para el proyecto, no dudes en enviar tus pull requests. Si tienes alguna pregunta o comentario, puedes encontrarme y visitar mi sitio web https://codingwithnirvana.pythonanywhere.com.

Espero que esta versión del README sea útil.
Creado por **Nirvana Belen González López** 
