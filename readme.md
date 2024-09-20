# 🎶 Controla el Volumen con Pausa/Reanudación Automática 🔊

¡Bienvenido! 🚀 Este script te permitirá ajustar el volumen de tu sistema Ubuntu al máximo 🔝, y si estás disfrutando de música 🎵 o videos 🎥, los pausará automáticamente. ¡Y no te preocupes! 😎 Cuando el volumen vuelva a su nivel original, también reanudará la reproducción 🟢. ¡Todo esto con notificaciones automáticas! 🔔

## 🚀 Instalación

1. **Clona este repositorio** en tu máquina local 🖥️:

   ```bash
   git clone https://github.com/PedroPab/toggle_volumen.git
   ```

2. **Instala las dependencias necesarias** ejecutando este comando mágico 🧙‍♂️:

   ```bash
   sudo apt update && sudo apt install playerctl libnotify-bin libcanberra-gtk-module -y
   ```

## 🛠️ Configuración del Script

1. **Navega al directorio clonado** 🚪:

   ```bash
   cd toggle_volumen
   ```

2. **Haz que el script sea ejecutable** 🧑‍💻:

   ```bash
   chmod +x toggle_volume.sh
   ```

3. **Pon el script en `/usr/local/bin`** para usarlo como comando desde cualquier lugar 🗺️:

   ```bash
   sudo mv toggle_volume.sh /usr/local/bin/toggle_volume
   ```

   ¡Y listo! Ahora puedes usar el comando `toggle_volume` desde cualquier terminal. 🎉

## 🎛️ Crea un Atajo de Teclado en Ubuntu 🎹

¡Haz que la magia sea aún más rápida! 🌟 Configura un atajo de teclado para ejecutar el script al instante:

1. Abre **Configuración** ⚙️ y ve a la sección **Teclado** ⌨️.
2. Haz clic en **Atajos** en la barra lateral izquierda.
3. Selecciona **Agregar un nuevo atajo** ➕.
4. Dale un nombre divertido 😄, como `"Control de Volumen"`, y en el campo de comando, escribe:

   ```bash
   /usr/local/bin/toggle_volume
   ```

5. Haz clic en **Establecer atajo** y elige una combinación de teclas rápida, por ejemplo, `Ctrl + Alt + V` 🎯.
6. ¡Guarda el atajo y listo! 🚀

## 😄 ¡Gracias por usar esta herramienta

Con este script, podrás controlar el volumen y la reproducción de música o video 🎶🎥 de una manera súper rápida y sencilla. Esperamos que lo disfrutes tanto como nosotros. ¡Gracias por probarlo! 🎉😊
