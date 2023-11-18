# Login Parte 3
Este proyecto es un Sistema de Gestión de Usuarios desarrollado con Flask, un framework web ligero de Python. Proporciona funcionalidades básicas de inicio de sesión y gestión de usuarios, incluyendo roles de usuario y autenticación mediante una base de datos MySQL.

## Características Principales
Inicio de Sesión: Los usuarios pueden iniciar sesión utilizando sus credenciales.

## Roles de Usuario
Se asigna un tipo de usuario (normal o administrador) para gestionar diferentes niveles de acceso.
Gestión de Usuarios: Los administradores tienen acceso a una interfaz especial para gestionar usuarios y sus roles.
Persistencia de Datos: La información de usuario se almacena en una base de datos MySQL.

## Requisitos
- Python (versión x.x)
- Flask
- MySQL

## Uso
Clona el repositorio y configura la base de datos en config.py.
Instala las dependencias con pip install -r requirements.txt.
Ejecuta la aplicación con python app.py.

La aplicación estará disponible en http://127.0.0.1:5000/. Puedes iniciar sesión como administrador con las credenciales predefinidas o como usuario normal mediante registros en la base de datos.

## Instalación
1. Clona este repositorio:

```bash
git clone https://github.com/tu_usuario/tu_proyecto.git
```
## Instala dependencias
pip install -r requirements.txt

## Configura la base de datos en config.py
```bash
# config.py
class DevelopmentConfig:
    MYSQL_HOST = 'localhost'
    MYSQL_USER = 'tu_usuario'
    MYSQL_PASSWORD = 'tu_contraseña'
    MYSQL_DB = 'nombre_de_tu_base_de_datos'
```
## Ejecuta la app
python app.py

## Conclusion
En conclusión, este proyecto de Sistema de Gestión de Usuarios con Flask proporciona una solución ligera y efectiva para la autenticación y gestión de usuarios en una aplicación web. La aplicación incluye características esenciales como el inicio de sesión, roles de usuario y persistencia de datos en una base de datos MySQL.

La estructura modular del proyecto facilita su comprensión y extensión, permitiendo a los desarrolladores agregar nuevas funcionalidades o realizar ajustes según las necesidades específicas del proyecto. La aplicación se beneficia de las capacidades de Flask y Flask-Login para simplificar el manejo de sesiones y autenticación.

En el futuro, se pueden explorar mejoras adicionales, como la implementación de más funcionalidades de administrador, mejoras en la interfaz de usuario y la incorporación de medidas de seguridad adicionales. En general, este proyecto sirve como punto de partida sólido para aplicaciones que requieren gestión de usuarios y roles en un entorno web.
