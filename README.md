# ⏱️ Temporizador Flotante para Windows

Temporizador visual y minimalista que se mantiene siempre visible sobre todas las aplicaciones.  
Ideal para sesiones de estudio, descansos, trabajo por bloques de tiempo (pomodoro) o cualquier actividad cronometrada.

---


<p align="center">
  <img src="https://github.com/user-attachments/assets/541e7664-9474-45ae-a70a-266302fa7747" width="200" alt="Mascota del temporizador">
</p>
## 🚀 Características

- ⌛ Temporizador visible en pantalla con cuenta regresiva.
- 🔁 Se reinicia con una tecla global (por defecto: `Ctrl + R`).
- ⚙️ Abre la ventana de configuración con una tecla global (por defecto: `Alt + F6`).
- 🔊 Reproduce tonos personalizados cuando llega a cero.
- 🔴 Cambia de color y comienza a contar en negativo al finalizar.
- 🕐 Muestra el reloj actual (formato 12 horas).
- 📌 Siempre encima de todas las ventanas.
- 🧩 Personalizable:
  - Tiempo inicial
  - Tamaño y color del texto
  - Atajos de teclado
  - Tonos de alerta (frecuencia + duración)
- 💾 Guarda posición en pantalla y configuración automáticamente.
- ❌ Incluye botón para cerrar desde la ventana.

---

## 🛠 Requisitos

- Python 3.10+
- Windows
- Permisos de administrador (para detectar atajos globales)

Instala la dependencia principal:

```bash
pip install keyboard
```
⚙️ Atajos por defecto
```bash
Acción	Atajo
Reiniciar timer	Ctrl + R
Abrir configuración	Alt + F6
```
Puedes modificarlos desde la ventana de configuración.

📁 Archivos importantes
Temporizador.py → Script principal

config.json → Configuración guardada automáticamente

![2025-05-22 00_13_07-dist](https://github.com/user-attachments/assets/a411a435-bdd9-4886-933f-41b0d71b4e9a)


🧠 Autor
Desarrollado por Wazazky
Un temporizador simple pero potente, hecho a medida para quienes valoran el enfoque sin distracciones.
