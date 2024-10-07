# OpenAI Realtime API Console

Este proyecto es una consola interactiva que utiliza la API en tiempo real de OpenAI y se integra con OpenWebinars para obtener información sobre cursos.

## Configuración

1. Clona este repositorio.
2. Copia el archivo `.env.example` a `.env`:
   ```
   cp .env.example .env
   ```
3. Edita el archivo `.env` y añade tus claves de API:
   - `OPENAI_API_KEY`: Tu clave de API de OpenAI
   - `REACT_APP_OPENWEBINARS_API_URL`: La URL completa de la API de predicción de OpenWebinars
   - `REACT_APP_OPENWEBINARS_API_KEY`: Tu clave de API de OpenWebinars

## Ejecución

1. Instala las dependencias:
   ```
   npm install
   ```
2. Inicia la aplicación:
   ```
   npm start
   ```

La aplicación estará disponible en `http://localhost:3000`.

## Características

- Interacción en tiempo real con la API de OpenAI
- Integración con OpenWebinars para obtener información sobre cursos
- Visualización de eventos y conversación
- Funcionalidades de grabación de voz y reproducción de audio

## Nota

Asegúrate de no compartir tus claves de API. El archivo `.env` está incluido en `.gitignore` para evitar que se suba accidentalmente a un repositorio.