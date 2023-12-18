# Ex03

## Descripción
Este proyecto es una aplicación web desarrollada en Angular que permite explorar información sobre películas y series. Utiliza la API de The Movie Database (TMDb) para obtener datos actualizados sobre películas y series en cartelera y populares.

## Características Principales
    Lista de películas en cartelera.
    Detalles de películas individualmente.
    Lista de series populares.
    Detalles de series individualmente.
    Página de error para rutas no encontradas.
    
## Despliegue
La aplicación está desplegada y accesible en la siguiente URL: https://main.dwxqdz0obwkqx.amplifyapp.com/movies

## Características Principales
- Lista las características más importantes de tu aplicación.

## Requisitos Previos
- Node.js y npm instalados en tu máquina.
- Angular CLI instalado (`npm install -g @angular/cli`).

## Instalación
1. Clona este repositorio.
   ```bash
   git clone <URL_del_repositorio>
   cd <nombre_del_directorio>
   ```

2. Instala las dependencias.
   ```bash
   npm install
   ```

## Configuración
Asegúrate de tener las claves de API necesarias para acceder a los servicios de la API de The Movie Database (TMDb).

1. Obtiene una clave de API en [TMDb Developer](https://www.themoviedb.org/settings/api).
2. Reemplaza `TU_CLAVE_API` en los archivos `movie.service.ts` y `serie.service.ts` con tu clave de API.

## Uso
1. Inicia la aplicación.
   ```bash
   ng serve
   ```

2. Abre tu navegador y ve a `http://localhost:4200/`.

## Componentes Principales
- `MoviesComponent`: Muestra la lista de películas.
- `MovieComponent`: Muestra detalles de una película específica.
- `SeriesComponent`: Muestra la lista de series.
- `SerieComponent`: Muestra detalles de una serie específica.

## Servicios
- `MovieService`: Gestiona las solicitudes relacionadas con películas.
- `SerieService`: Gestiona las solicitudes relacionadas con series.

## Rutas
- `/movies`: Muestra la lista de películas.
- `/movie/:id`: Muestra detalles de una película específica.
- `/series`: Muestra la lista de series.
- `/serie/:id`: Muestra detalles de una serie específica.
