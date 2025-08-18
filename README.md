# 📘 Instalación y Uso del Editor Xoconodo

Este documento te guiará a través de los pasos necesarios para instalar y ejecutar la aplicación de escritorio **Xoconodo** en un nuevo ordenador con Windows.

---

## 📥 Descarga del Programa

- **Descargar desde Google Drive:**  
  👉 [Xoconodo - Google Drive](https://drive.google.com/file/d/13VCGM1YDJWSNxFwjLinY3HcoO7TrTJ2t/view?usp=sharing)

- **Captura de pantalla y documentación:**  
![Vista previa de la app](https://xococode.github.io/Xocoflow-3/CapturaXoconode.JPG)

---

## 🔧 Requisitos Previos

- **Python 3.6 o superior** → [Descargar aquí](https://www.python.org/downloads/)  
- Durante la instalación, **marca la casilla**:  

  ```
  Add Python to PATH
  ```

  Esto es crucial para que los scripts funcionen correctamente.

---

## 📂 Archivos del Proyecto

Asegúrate de tener en una misma carpeta todos los siguientes archivos:

```
/tu-carpeta-del-proyecto/
│
├── data.txt
├── navegador_xoconodo.py
├── react.development.js
├── react-dom.development.js
├── reactflow.umd.js
├── requirements.txt
├── start.bat
└── xocoflow.html
```

> La carpeta `venv/` se creará automáticamente la primera vez que ejecutes el programa.

---

## ▶️ Instalación y Ejecución

1. Navega a la carpeta donde guardaste los archivos.
2. Haz doble clic en **`start.bat`**.
3. El script realizará automáticamente los siguientes pasos:
   - Creará un entorno virtual (`venv/`).
   - Instalará todas las dependencias listadas en `requirements.txt` (PyQt6, Watchdog, etc.).
   - Lanzará la aplicación **Xoconodo**.

> 💡 Para ejecuciones futuras, simplemente vuelve a hacer doble clic en `start.bat`.  
> El script detectará si ya existen las librerías, por lo que el inicio será mucho más rápido.

---

## 🖥️ Uso del Editor

1. Al abrir la aplicación, verás el nodo inicial:  
   **Fuente de Datos (data.txt)**
2. Para probar:
   - Abre el archivo `data.txt` con cualquier editor de texto (Bloc de notas, VS Code, etc.).
   - Escribe algo y guarda el archivo.
   - El contenido del nodo en Xoconodo se actualizará **en tiempo real**.

3. Desde ese nodo inicial, puedes conectarlo a otros nodos funcionales, como:
   - **Mayúsculas** → transforma el texto.
   - **Tarea Gemini** → procesa la información en tiempo real.

---

## ⚠️ Solución de Problemas

### ❌ Error: `"python' no se reconoce como un comando"`
- Python no está instalado o no se agregó al **PATH**.
- Vuelve a instalar Python asegurándote de marcar la opción **Add Python to PATH**.

---

### ❌ Fallos en la instalación de librerías
- Asegúrate de tener conexión a internet.
- Si persisten los errores, instala manualmente desde la terminal:

```bash
# 1. Activa el entorno virtual
.env\Scriptsctivate.bat

# 2. Instala las dependencias
pip install -r requirements.txt

# 3. Ejecuta la aplicación
python navegador_xoconodo.py
```

---

## ✅ Conclusión

Con estos pasos, tendrás **Xoconodo** instalado y funcionando en tu PC.  
Cada vez que quieras usarlo, solo abre **`start.bat`**.

---

