# Procesamiento de Lenguaje Natural con Dialogflow MariosPizza
# Dialogflow
Dialogflow es una plataforma de comprensión del lenguaje natural utilizada para diseñar e integrar una interfaz de usuario conversacional en aplicaciones móviles, aplicaciones web, dispositivos, bots, sistemas interactivos de respuesta de voz, etc.

Dialogflow es un servicio de Google que se ejecuta en Google Cloud Platform, lo que permite escalar a cientos de millones de usuarios.

Dialogflow es fácil de usar, intuitivo y tiene sentido. Su Procesamiento de Lenguaje Natural (PNL) es el mejor.

# Ejemplos de los resultados que se obtiene con el Asistente Virtual en una página web
![image](https://user-images.githubusercontent.com/26776908/84577912-8c06e200-ad7d-11ea-838e-776d8ff1e0f7.png)
![image](https://user-images.githubusercontent.com/26776908/84577936-c1133480-ad7d-11ea-80df-d53fc1a1490a.png)
![image](https://user-images.githubusercontent.com/26776908/84577945-d5573180-ad7d-11ea-8bdf-f0a5a3f37ca8.png)
![image](https://user-images.githubusercontent.com/26776908/84577954-e6a03e00-ad7d-11ea-9aac-d9d25abe0016.png)
![image](https://user-images.githubusercontent.com/26776908/84577957-f0c23c80-ad7d-11ea-9ccd-45b0a2dfaad6.png)

# Ejemplos de los resultados que se obtiene con el Asistente Virtual integrado en Facebook Messenger
![image](https://user-images.githubusercontent.com/26776908/84577980-30892400-ad7e-11ea-8884-d48b9af09b9a.png)
![image](https://user-images.githubusercontent.com/26776908/84578003-57475a80-ad7e-11ea-9e2c-a41122b5f6f6.png)
![image](https://user-images.githubusercontent.com/26776908/84578011-675f3a00-ad7e-11ea-87a3-59266c9fd8e0.png)
![image](https://user-images.githubusercontent.com/26776908/84578021-76de8300-ad7e-11ea-8750-70ec90c08ba7.png)
![image](https://user-images.githubusercontent.com/26776908/84578025-7fcf5480-ad7e-11ea-8165-dcd5bd24eefd.png)

# ejemplos de como quedarían guardodo en la Base de datos en Firebase
![image](https://user-images.githubusercontent.com/26776908/84578047-b86f2e00-ad7e-11ea-9c12-b503c0198663.png)
![image](https://user-images.githubusercontent.com/26776908/84578055-d472cf80-ad7e-11ea-9a35-94a3cb29aa3d.png)

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
