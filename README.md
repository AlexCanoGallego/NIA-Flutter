# Nia flutter app

**NIA** es un asistente virtual de inteligencia artificial diseñado para ayudar a las personas a aprender nuevos idiomas y mejorar sus habilidades de conversación. Utiliza la API de OpenAI para ofrecer respuestas avanzadas y adaptarse al contexto proporcionado por el usuario, creando una experiencia de aprendizaje personalizada.

## **Características principales**
- **Asistente virtual con inteligencia artificial**: Basado en la API de OpenAI, NIA puede responder en cualquier idioma y aprender del contexto de la conversación.
- **Interfaz amigable**: Registra tus conversaciones pasadas con NIA para mejorar la experiencia del usuario.
- **Funcionalidades clave**:
   - Chat con NIA utilizando el micrófono de tu dispositivo.
   - Cambia entre distintos idiomas según tu preferencia.
   - Sección de suscripción con opciones avanzadas.
   - Sección de preguntas frecuentes para resolver dudas sobre la aplicación.

## **Tecnologías utilizadas**
- **Lenguaje de programación**: Flutter (con el framework GetX para la gestión del estado y la navegación).
- **Backend**: Implementado en Go y alojado en Google Cloud App Engine.
- **APIs**:
  - **OpenAI API**: Para la generación de respuestas y procesamiento del lenguaje.
  - **Firebase**: Para la autenticación y almacenamiento de datos de usuarios.
- **SDKs utilizados**:
  - Micrófono y altavoces para interacción por voz.
  - WebSockets para la transmisión en tiempo real del audio y texto.

## **Instalación**
### Requisitos
- **Flutter**: Instalado en tu sistema.
- **Acceso a Firebase** para la autenticación y base de datos.
- **API Key de OpenAI** para habilitar las funcionalidades de NIA.

### Instrucciones
1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/nia-language-assistant.git
   ```
2. Configura las credenciales de Firebase y la API de OpenAI en el archivo de configuración del proyecto.
3. Compila y ejecuta la aplicación en tu entorno de desarrollo Flutter.

## **Cómo usar**
1. Al iniciar la app, pasarás por una serie de pantallas de bienvenida que explican las funcionalidades de NIA.
2. Regístrate o inicia sesión con tu cuenta de Google, Apple o Facebook.
3. En la pantalla principal, presiona el botón del micrófono para empezar a hablar con NIA.
4. Usa la sección de perfil para ajustar tus preferencias y cerrar sesión.

## Autores

* Marc Geremias (marc.geremias@students.salle.url.edu)
* Guillem Godoy (guillem.godoy@students.salle.url.edu
* Biel Carpi (biel.carpi@outlook.com)
* Alex Cano (alex.cano@students.salle.url.edu)

## **Licencia**
Este proyecto está bajo la licencia, consulta el archivo `LICENSE` para más detalles.

---

