# QRGo.py v.1.0


QRGo.py es una herramienta intuitiva y fácil de usar para generar códigos QR personalizados, es funcional tanto para Linux como para Windows. Este programa permite a los usuarios ingresar  mensajes o URL's, y luego genera un código QR que puede ser escaneado para acceder a esa información de manera rápida y eficiente.
Características

    QRGo.py: Permite ingresar texto con instrucciones, URL's o mensajes que quieres que sean privados, y luego genera un código QR que almacena dicha información.

    Interfaz Gráfica Intuitiva: Con una interfaz limpia y profesional, los usuarios pueden ingresar texto fácilmente y generar los QR sin complicaciones. La ventana tiene un tamaño fijo y opciones claras para realizar cada acción.

    Selección de Carpeta de Destino: Los usuarios pueden seleccionar la carpeta donde desean guardar el código QR generado, facilitando la organización de los archivos.

    Actualización Automática: El programa incluye una opción para verificar si hay actualizaciones disponibles directamente desde GitHub, lo que asegura que siempre estés utilizando la última versión.

    Formatos de Exportación: Los QR generados se guardan en formato PNG.

    Fácil de Usar: La herramienta está diseñada para ser simple y accesible, sin necesidad de configuraciones complejas, lo que la convierte en una opción ideal para quienes buscan eficiencia en el proceso de creación de códigos QR.

## Requisitos

    Python 3.x
    Tkinter (Para la interfaz gráfica)
    Pillow (Para manejar imágenes)
    qrcode (Para generar los códigos QR)
    winshell (Para la interacción con el sistema de Windows)

## Instalación

Si sos usuario de Windows y no tenes instalado git , es recomendable hacerlo antes de clonar el repositorio.

### Link de descarga para git:

    https://git-scm.com/downloads/win

### Opciones para usar QRGo

## 1. Ejecutar directamente el programa (recomendado)

### Windows:
Descarga el archivo QRGo.exe desde la sección Releases. Haz doble clic en el archivo, ¡y listo!
No necesitas realizar ningún paso adicional.

### Linux:
Descarga el archivo QRGo desde la sección Releases.
Asegúrate de dar permisos de ejecución al archivo descargado:

    chmod +x QRGo

Luego, ejecútalo:

    ./QRGo

## 2. Instalar manualmente desde el repositorio (para desarrolladores o usuarios avanzados)

Clona este repositorio en tu máquina local:

    git clone https://github.com/EzeTauil/QRGo.git

Instala las dependencias necesarias:

    pip install -r requirements.txt

Ejecuta el programa:

    python QRGo.py

__Contribuciones__

Si tienes sugerencias, mejoras o correcciones, no dudes en abrir un "issue" o enviar un "pull request". ¡Toda contribución es bienvenida!

_Licencia_

Este proyecto está bajo la Licencia MIT. Para más detalles, consulta el archivo LICENSE.
