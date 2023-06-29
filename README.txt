# Aplicación de Clima

Esta es una aplicación de clima que utiliza HTML, CSS, JavaScript y la API de OpenWeatherMap para mostrar información meteorológica actual y pronósticos.

## Funcionalidades

- Muestra el clima actual de una ciudad buscada.
- Proporciona un pronóstico de 5 días para la ciudad seleccionada.
- Permite buscar ciudades por nombre.
- Muestra destacados del clima, como la temperatura máxima, mínima y la humedad.
- Proporciona un pronóstico por hora.

## Instalación

1. Clona este repositorio en tu máquina local.
2. Abre el archivo `index.html` en tu navegador web.

## Uso

1. Abre la aplicación en tu navegador.
2. En el campo de búsqueda, ingresa el nombre de una ciudad y presiona Enter o haz clic en el botón de búsqueda.
3. Verás el clima actual y el pronóstico para la ciudad buscada.

## Configuración de la API de OpenWeatherMap

1. Regístrate en [OpenWeatherMap](https://openweathermap.org/) y obtén una API Key.
2. En el archivo `app.js`, reemplaza el valor de la constante `api_key` con tu API Key.

```javascript
const api_key = "tu_api_key_aqui";
