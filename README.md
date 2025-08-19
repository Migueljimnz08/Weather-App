# ☁️ Weather-App

Aplicación web sencilla para consultar el clima en cualquier ciudad del
mundo usando la API de [OpenWeatherMap](https://openweathermap.org/).\
Está construida con **Node.js**, **Express**, **EJS** y **dotenv**

------------------------------------------------------------------------

## 🚀 Características

-   Búsqueda del clima por ciudad
-   Consulta en tiempo real con la API de OpenWeather
-   Muestra temperatura y condiciones actuales
-   Manejo de errores cuando la ciudad no existe o no hay conexión
-   Motor de plantillas **EJS**
-   Estilos personalizados con CSS

------------------------------------------------------------------------

## 🛠 Tecnologías usadas

-   [Node.js](https://nodejs.org/) + [Express](https://expressjs.com/)
-   [EJS](https://ejs.co/) (motor de plantillas)
-   [dotenv](https://www.npmjs.com/package/dotenv) (manejo de variables
    de entorno)
-   [body-parser](https://www.npmjs.com/package/body-parser) (procesar
    formularios)
-   [cowsay](https://www.npmjs.com/package/cowsay) 🐧 (mensaje divertido
    en consola)
-   [OpenWeather API](https://openweathermap.org/api)

------------------------------------------------------------------------

## 📂 Estructura del proyecto

    /weather-app
    │
    ├── server.js          # Servidor Express principal
    ├── package.json
    ├── .env               # Clave de API (NO subir a GitHub)
    │
    ├── /views
    │   └── index.ejs      # Plantilla principal
    │
    ├── /public
    │   └── css/style.css  # Estilos

------------------------------------------------------------------------

## ⚙️ Instalación y uso

1.  Clona este repositorio:

    ``` bash
    git clone https://github.com/Migueljimnz08/Weather-App.git
    cd weather-app
    ```

2.  Instala dependencias:

    ``` bash
    npm install
    ```

3.  Crea un archivo `.env` en la raíz del proyecto con tu clave de
    OpenWeather:

        API_KEY=tu_api_key_aqui

4.  Inicia el servidor:

    ``` bash
    node server.js
    ```

5.  Abre en el navegador:

        http://localhost:3000

------------------------------------------------------------------------

## 💡 Próximas mejoras

-   Añadir soporte para mostrar iconos de clima
-   Mostrar temperatura máxima/mínima, humedad y viento
-   Historial de búsquedas
-   Selector de unidades (°C / °F)
-   Traducción multilenguaje
