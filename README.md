## Generador de PDFs con Marca de Agua y Protección
---
Este programa es una aplicación de escritorio que permite:

- Añadir marcas de agua a archivos PDF.

- Proteger los PDFs con permisos que impidan la modificación, impresión o copia, pero permitan la apertura sin contraseña.

- Enviar los PDFs protegidos por correo electrónico a los destinatarios especificados.

- El programa se distribuye como un archivo ejecutable (.exe), por lo que no es necesario tener Python instalado para usarlo.

## Características Principales
---
- Interfaz gráfica intuitiva: Fácil de usar, con botones y menús claros.

- Protección de PDFs:

    - Añade marcas de agua personalizadas.

    - Protege los PDFs contra modificación, impresión y copia.

    - No requiere contraseña para abrir los PDFs.

- Envío de correos electrónicos:

    - Envía los PDFs protegidos directamente desde la aplicación.

    - Configuración flexible del servidor SMTP.

    - Compatibilidad: Funciona en sistemas Windows.

## Requisitos del Sistema
--- 
- Sistema operativo: Windows 7, 8, 10 o 11.

- Memoria RAM: Mínimo 2 GB (recomendado 4 GB).

- Espacio en disco: Mínimo 50 MB (dependiendo del tamaño de los PDFs).

## Instalación
---
- Descarga el archivo Generador-Pdf cifrado.exe desde la carpeta de lanzamientos (releases) o desde la ubicación proporcionada.

- Coloca el archivo .exe en una carpeta de tu elección (por ejemplo, C:\Generador-PDF).

- Si el programa requiere archivos adicionales (como un icono o configuración SMTP), asegúrate de colocarlos en la misma carpeta que el .exe.

## Configuración Inicial

1. Configuración del Servidor SMTP
Para enviar correos electrónicos, debes configurar los detalles del servidor SMTP:

    - Ejecuta el programa (Generador-Pdf cifrado.exe).

    - Haz clic en Configuración SMTP en el menú superior.

    - Ingresa los siguientes detalles:

    - Servidor SMTP: Por ejemplo, smtp.gmail.com (para Gmail).

    - Puerto SMTP: Por ejemplo, 587 (para Gmail).

    - Correo electrónico: Tu dirección de correo electrónico.

    - Contraseña: La contraseña de tu correo electrónico (preferiblemente contraseña de aplicacion).

*Haz clic en Guardar.*

2. Archivo Excel de Entrada
El programa requiere un archivo Excel con los datos de los alumnos. El archivo debe tener el siguiente formato:

ID	Nombre	Apellidos	Correo	DNI	Teléfono	Marca de Agua	Ruta de los PDFs
1	Juan	Pérez	juan@example.com	12345678A	600123456	CONFIDENCIAL	C:\ruta\a\pdfs
2	María	Gómez	maria@example.com	87654321B	600654321	CONFIDENCIAL	C:\ruta\a\pdfs
Ruta de los PDFs: Debe ser la ruta completa de la carpeta donde se encuentran los PDFs originales.

## Manual de Uso
---
1. Generar PDFs Protegidos
    - Haz clic en Generar PDFs.

    - Selecciona el archivo Excel que contiene los datos de los alumnos.

    - El programa procesará los PDFs en la carpeta especificada, añadirá la marca de agua y los protegerá.

*Los PDFs protegidos se guardarán en una carpeta llamada exportados dentro de la misma carpeta donde está el .exe.*

2. Enviar PDFs por Correo Electrónico
    - Haz clic en Enviar Correos.

    - Selecciona los alumnos a los que deseas enviar los PDFs.

    - Ingresa el asunto y el cuerpo del mensaje en la ventana emergente.

    - Haz clic en Enviar Correos para enviar los PDFs por correo electrónico.

3. Configuración SMTP
    - Si no has configurado el servidor SMTP previamente, sigue estos pasos:

    - Haz clic en Configuración SMTP en el menú superior.

    - Ingresa los detalles de tu servidor SMTP (servidor, puerto, correo electrónico y contraseña).

*Haz clic en Guardar.*

## Estructura del Proyecto ##
Después de ejecutar el programa, se crearán las siguientes carpetas y archivos:

Copy
Carpeta del Proyecto/
├── Generador-Pdf cifrado.exe
├── config/
│   ├── json/
│   │   └── smtp_config.json
│   └── icono/
│       └── icono.ico
├── exportados/
└── (Archivos adicionales, si los hay)
config/: Contiene la configuración del servidor SMTP y el icono de la aplicación.

exportados/: Aquí se guardan los PDFs protegidos.

*Preguntas Frecuentes*
---
1. ¿Necesito tener Python instalado?
No, el archivo .exe es independiente y no requiere Python instalado.

2. ¿Puedo usar otro servicio de correo electrónico?
Sí, siempre que conozcas los detalles del servidor SMTP (servidor, puerto, correo electrónico y contraseña).

3. ¿Qué hago si el programa no funciona?
Asegúrate de que el archivo Excel tenga el formato correcto.

    - Verifica que la ruta de los PDFs sea válida.

    - Si el problema persiste, contacta al soporte técnico.


*Soporte y Contacto*
---
Si tienes alguna pregunta o necesitas ayuda, no dudes en contactarme:

Nombre: SantiDev

Correo: santiago.luqueto@gmail.com

GitHub: SantiDev

Licencia
Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.

¡Gracias por usar este programa! Espero que te sea útil. 😊


¡Listo! Con este README.md, los usuarios tendrán toda la información necesaria para usar tu programa.