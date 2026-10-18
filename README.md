💾 Analizador de Espacio en Disco para Navegador Web

Un analizador de almacenamiento de disco duro ejecutable 100% en el navegador web sin necesidad de instalar ningún software ni dependencias. Permite inspeccionar carpetas de tu sistema, medir el espacio consumido por tus archivos, explorar subdirectorios y analizar carpetas de aplicaciones en Windows 11.


![Tecnología](https://img.shields.io/badge/HTML5-JavaScript%20ES6+-orange.svg)

![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.x-38bdf8.svg)

---
🚀 Características Principales
🔒 100% Privado y Local: Funciona totalmente del lado del cliente. Ningún archivo, nombre o dato se sube a ningún servidor.
⚡ Sin Congelamiento (Procesamiento Asíncrono): Procesa decenas de miles de archivos en segundo plano utilizando lotes asíncronos (`async/await`) manteniendo la interfaz fluida en todo momento.
📊 Gráfica Interactiva & Breadcrumbs: Visualiza las carpetas más pesadas con gráficas dinámicas (Chart.js) y navega por los subdirectorios utilizando migas de pan (breadcrumbs).
🗂️ Categorización Automática: Clasifica el espacio ocupado según el tipo de archivo (Vídeos, Imágenes, Audio, Documentos, Archivos Comprimidos, Ejecutables).
🏆 Top 10 Archivos Más Pesados: Detecta automáticamente cuáles son los 10 archivos individuales de mayor tamaño dentro del área escaneada.
🛡️ Filtrado Inteligente de Archivos de Sistema: Ignora de forma transparente archivos y carpetas del sistema operativo inaccesibles o protegidos (como `$Recycle.Bin`, `System Volume Information`, `pagefile.sys`, etc.).
💻 Modo Especial para Programas en Windows 11: Guía e interfaz optimizada para medir el peso de tus aplicaciones y juegos analizando las carpetas `Program Files`, `Program Files (x86)` y `AppData`.

---
🛠️ Tecnologías Utilizadas

HTML5 & Vanilla JavaScript (ES6+): Lógica del explorador y manejo de eventos.

File System Access API & WebkitDirectory: Lectura local de archivos del navegador.

Tailwind CSS: Diseño moderno, limpio y responsive.

Chart.js: Gráficas interactivas para desglosar el almacenamiento.

FontAwesome 6: Iconografía intuitiva.

---
📂 Estructura del Proyecto
```text
.
├── index.html       # Aplicación completa (Single File App)
└── README.md        # Documentación del proyecto
```
---
💻 ¿Cómo Usarlo?

Opción 1: Ejecución Directa

Descarga el archivo `index.html`.

Haz doble clic en `index.html` para abrirlo en cualquier navegador moderno (Google Chrome, Microsoft Edge, Brave, Opera, Firefox, Safari).

Haz clic en Elegir Carpeta o arrastra cualquier carpeta directamente sobre la aplicación.

Opción 2: Usar con GitHub Pages

Haz un Fork o sube este repositorio a GitHub.

Ve a Settings > Pages en tu repositorio de GitHub.

Selecciona la rama `main` y guarda los cambios.

Tu herramienta estará lista y disponible en una URL web pública.

---
💡 Análisis de Programas en Windows 11

Por restricciones de seguridad de los navegadores, las aplicaciones web no pueden acceder directamente al Registro del Sistema. Sin embargo, el 95% del tamaño de tus programas y juegos se encuentra en tres rutas clave.

Para analizar el tamaño de tus programas en Windows 11:

Haz clic en el botón Analizar Programas Win 11.

Selecciona cualquiera de las siguientes carpetas de tu disco local `C:`:

`C:\Archivos de Programa` (`C:\Program Files`)

`C:\Program Files (x86)`

`C:\Users\TuUsuario\AppData` (Usa Win + R y escribe `%appdata%` para encontrarla fácilmente)

---
📄 Licencia
Este proyecto está bajo la Licencia GPL3. Puedes usarlo, modificarlo y distribuirlo libremente.

Autor:
Julio Sánchez Berro
