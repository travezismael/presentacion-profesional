# presentacion-profesional
Presentacion Profesional de Ismael Travez
  
## Objetivo del Proyecto
Crear un mockup de alta fidelidad de un sitio de presentación profesional, desarrollarlo utilizando HTML5 y CSS externo, y desplegarlo en un contenedor Docker utilizando Nginx como servidor web. 

## Tecnologías Utilizadas
* HTML5: Estructura semántica del sitio.
* CSS3: Estilos externos y diseño visual.
* Docker: Contenerización del proyecto.
* Nginx: Servidor web.
* GitHub: Control de versiones y alojamiento del código fuente.

## Estructura del Proyecto
/
├── archivos/
│   ├── estilos.css  # Hoja de estilos externa
│   └── foto.png     # Imagen de perfil/presentación
├── Dockerfile       # Instrucciones para crear la imagen Docker con Nginx
├── index.html       # Estructura principal del sitio web
└── README.md        # Documentación del proyecto

## Instrucciones para Construir y Ejecutar la imagen Docker
1. Construir la imagen localmente:
Abre una terminal en la raíz del proyecto y ejecuta el siguiente comando:
docker build -t ismaeltravez/presentacion-profesional .

2. Ejecutar el contenedor:
Para levantar el servidor y probar el sitio web localmente, ejecuta:
docker run -d -p 8080:80 ismaeltravez/presentacion-profesional

Una vez en ejecución, abre tu navegador web y visita: http://localhost:8080

## Enlace a Docker Hub
https://hub.docker.com/r/ismaeltravez/presentacion-profesional
