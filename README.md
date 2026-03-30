# Instrucciones de Uso - Proyecto PRUEBAJR

Este proyecto es una aplicación Android que permite gestionar un catálogo de donuts consumiendo una API externa.

## Requisitos Previos
*   Android Studio Ladybug o superior.
*   Conexión a Internet (para la carga de datos).
*   Dispositivo físico o emulador con Android 8.0 (API 24) o superior.

## Configuración del Proyecto
1.  **Sincronización de Gradle**: Al abrir el proyecto, asegúrate de realizar un "Sync Project with Gradle Files".
2.  **SDK**: El proyecto está configurado para compilar con el SDK 36. Asegúrate de tenerlo instalado en el SDK Manager.

## Cómo Ejecutar la Aplicación
1.  Selecciona el módulo `app` en la configuración de ejecución.
2.  Elige tu dispositivo/emulador.
3.  Presiona el botón "Run" (flecha verde).

## Flujo de la Aplicación
1.  **Pantalla de Inicio (Login)**:
    *   La aplicación inicia en la pantalla de inicio de sesión.
    *   Puedes ingresar tus credenciales (si ya tienes una cuenta).
    *   Si no tienes cuenta, presiona el botón "Crear usuario nuevo" (color azul oscuro) para ir a la pantalla de registro.
2.  **Pantalla de Registro**:
    *   Completa los campos requeridos para crear un nuevo usuario.
3.  **Pantalla Principal (Catálogo)**:
    *   Una vez iniciada la sesión, verás una lista de donuts.
    *   La lista se carga automáticamente desde una API externa.
    *   Si hay problemas de red, aparecerá un mensaje de error (Toast).

## Personalización Visual
*   **Colores**: El proyecto utiliza un esquema de colores personalizado:
    *   Primario: #2699FB (Azul claro) - Usado en botones principales.
    *   Secundario: #0A2459 (Azul oscuro) - Usado en botones secundarios.
*   **Temas**: La aplicación utiliza un tema sin barra de título (`NoActionBar`) para aprovechar mejor el espacio de pantalla.
