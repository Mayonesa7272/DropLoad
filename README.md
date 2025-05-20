# 📥 DropLoad: Descarga Videos y Audios de YouTube

**DropLoad** es una aplicación moderna y ligera para Windows que permite descargar videos y audios de YouTube en formato `.mp4` y `.mp3`, sin necesidad de conocimientos técnicos ni instalación de Python.

---

## 🚀 ¿Qué hace DropLoad?

DropLoad facilita la descarga rápida y directa de contenido multimedia desde YouTube, con opciones personalizables y una interfaz amigable.

Con DropLoad puedes:

- Descargar **videos** en formato `.mp4` con calidad de hasta **1080p**.
- Descargar **solo audio** en formato `.mp3`, ideal para música y podcasts.
- Realizar **conversión automática** mediante ffmpeg (se descarga la primera vez).
- Ver el **progreso de descarga en tiempo real**: porcentaje, tamaño, velocidad y tiempo restante.
- Cambiar **el tamaño de letra** de la interfaz.
- Cambiar el **color del botón de descarga** para personalizar la apariencia.

---

## 🔧 Funcionalidades de DropLoad

- **Interfaz intuitiva** desarrollada con **Tkinter**.
- **Modo claro, oscuro y sistema** disponibles.
- Botones para ajustar la **visualización y accesibilidad** de la interfaz.
- Permite cambiar la carpeta donde se guardan las descargas.
- Ejecutable `.exe` para Windows que **no requiere instalación de Python**.

---

## ⚙️ Características Técnicas

- **Lenguaje de programación**: Python 3.10+
- **Librerías utilizadas**:
  - `pytube` para descargar contenido desde YouTube
  - `ffmpeg` para convertir archivos multimedia
  - `tkinter` para la interfaz gráfica
- **Sistema operativo**: Compatible con **Windows 7, 10 y 11**
- **Empaquetado con**: `auto-py-to-exe` para generar un `.exe` independiente

---

## 💡 Nota Importante

Durante la **primera ejecución** o cuando se detecte una nueva versión de `ffmpeg`, el programa descargará automáticamente la herramienta.  
Esto puede tardar unos segundos, pero solo ocurre una vez.  
Las ejecuciones siguientes serán más rápidas. *(Estamos trabajando en soluciones para mejorar esta parte.)*

---

## 🛠️ Instalación

1. Descarga el archivo `DropLoad.exe` desde la sección de lanzamientos en GitHub.
2. Ejecuta el archivo directamente, **sin necesidad de instalar ni configurar nada**.
3. En la primera ejecución, ffmpeg se descargará automáticamente si no está disponible.
4. ¡Listo! Ya puedes empezar a descargar videos o audios de YouTube.

---

## 🧑‍💻 Contacto y Soporte

- GitHub: [https://github.com/Mayonesa7272](https://github.com/Mayonesa7272)
- Email: [mayonesaa72@gmail.com](mailto:mayonesaa72@gmail.com)

---

¿Quieres que también te genere este archivo `.md`, el `setup.py`, `requirements.txt` o el archivo de configuración para `auto-py-to-exe`? Puedo ayudarte con eso también.
