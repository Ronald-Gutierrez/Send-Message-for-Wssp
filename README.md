# Automatización de envío de mensajes de WhatsApp

Este script en Python automatiza el envío de mensajes de WhatsApp a través de la web.whatsapp.com utilizando las bibliotecas `urllib.parse`, `webbrowser`, `time`, y `pyautogui`.

## Instalación de Dependencias
Asegúrate de tener las siguientes bibliotecas instaladas:
- `urllib3`
    ```bash
    !pip install urllib3
    ```
- `webbrowser`
    ```bash
    !pip install webbrowser
    ```
- `pyautogui`
    ```bash
    !pip install pyautogui
    ```

## Uso
1. Define los números de teléfono de destino en la lista `numeros_telefono`.
2. Escribe tu mensaje en el espacio provisto por la variable `msg`.
3. Ejecuta el script.

El script abrirá la interfaz web de WhatsApp, insertará los números de teléfono proporcionados y el mensaje especificado, y enviará el mensaje automáticamente después de 10 segundos.

**Nota:** Asegúrate de estar conectado a Internet y haber iniciado sesión en WhatsApp Web antes de ejecutar el script.
