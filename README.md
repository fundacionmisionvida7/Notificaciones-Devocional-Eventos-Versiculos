# Notificador Diario - Palabra del Día

Este repositorio contiene un workflow de GitHub Actions que se encarga de **enviar una notificación diaria por Firebase Cloud Messaging (FCM)** a todos los usuarios suscritos a la app "Misión Vida".

## ¿Qué hace?

- Ejecuta automáticamente todos los días a las **7:00 (Argentina)**.
- Envía una notificación FCM con el título "📖 Palabra del Día" y un mensaje de alerta a todos los dispositivos registrados.
- También permite disparar la notificación **manualmente** desde la pestaña "Actions" de GitHub.

## ¿Cómo funciona?

Este repositorio no tiene código de backend. Solo contiene un archivo:
