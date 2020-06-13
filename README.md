# Procesamiento de Lenguaje Natural con Dialogflow MariosPizza
# Dialogflow
Dialogflow es una plataforma de comprensión del lenguaje natural utilizada para diseñar e integrar una interfaz de usuario conversacional en aplicaciones móviles, aplicaciones web, dispositivos, bots, sistemas interactivos de respuesta de voz, etc.

Dialogflow es un servicio de Google que se ejecuta en Google Cloud Platform, lo que permite escalar a cientos de millones de usuarios.

Dialogflow es fácil de usar, intuitivo y tiene sentido. Su Procesamiento de Lenguaje Natural (PNL) es el mejor.

# Tecnologías utilizadas
1. DialogFlow - https://dialogflow.com/
2. Firebase   - https://firebase.google.com/?hl=es_419
3. Vue.js     - https://vuejs.org/v2/guide/
4. Vuetify.js - https://vuetifyjs.com/en/getting-started/quick-start/

# Versiones
A continuación se muestra en la tabla el detalle de cada versión especificando el commit y su descripción de la funcionalidad incluida.

| No. | Commit | Descripción |
|-----|--------|-------------|
|  1  |295529013e943f0962fc106f6a94272803d1cbd6        | se crearon las entidades e intentos, parametros y frases para el entrenamiento|
|  2  |295529013e943f0962fc106f6a94272803d1cbd6        | se crearon modelos de sugerencias y se reestructuraron los intentos y entidades|
|  3  |295529013e943f0962fc106f6a94272803d1cbd6 - cea465c3ab2c0e97f8dd4757e22f234c12644e34 | se creó una base de datos en Firebase en tiempo real y configuro Facebook Messenger para su integración al Asistente Virtual, el segundo commit es el proyecto realizado en página web con vue y vuetify integrando el Asistente Virtual en la página web|
|  4  | 561f251a2423d05c251646ca406dce54761f8a42 | se genero la licencia para la integracion del Asistente Virtual a la pagina web |
|  5  | ec88bd2dec4d54a6aa5fa1079888477bd4100d56 | codigo que debe ir en fulfillment de dialoflow para crear los modelos de sugerencias y el codigo para la conexion a la base de datos con firebase y guardar la informacion en ella. |

Posdata: en el commit (295529013e943f0962fc106f6a94272803d1cbd6) se hizo, la primera, segunda y una parte de la tercera entrega establecida, no se pudo ir haciendo commits por parte, ya que todo se trabajaba en la consola de dialogflow por lo que se descargo el archivo hasta el final, cuando ya estuviera completo el asistente virtual y funcionando y así descargar los archivos del agente completo y subirlo en el repositorio. por tal razon, en ese commit van los primeros dos entregables y una parte del tercer entregable.
