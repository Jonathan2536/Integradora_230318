<p align="center">
  <img src="https://lh3.googleusercontent.com/d/1EVoNQAIppYUD9L_saWyLe_8Zydiw4y1u" alt="UTXJ Logo" width="400"/>
</p>

# Práctica 06 - Diagrama de Secuencia de Pantallas de Spotify

Representación visual e interactiva del flujo de navegación de la aplicación móvil de Spotify para oyentes y creadores de contenido.

## Diagrama interactivo

Consulta la práctica publicada en GitHub Pages:

[![Abrir diagrama de secuencia en GitHub Pages](https://img.shields.io/badge/Diagrama%20de%20Secuencia-Abrir%20en%20GitHub%20Pages-1ED760?style=for-the-badge)](https://jonathan2536.github.io/Integradora_230318/Practica6/)

También puedes abrir la página directamente desde el repositorio: [index.html](./index.html).

## Descripción

La práctica modela la navegación entre las pantallas principales de Spotify y muestra cómo cambian las opciones según el tipo de usuario. El prototipo reúne bocetos de interfaz, flujos de secuencia y una especificación JSON que puede utilizarse como referencia para construir el diagrama en Archify.

## Objetivo

Identificar las pantallas principales de la experiencia móvil de Spotify y representar de forma clara las rutas entre ellas para los roles de oyente y creador.

## Roles y pantallas

El prototipo incluye 16 pantallas:

| Rol | Pantallas | Descripción |
|---|---|---|
| Compartidas | P01–P04 | Inicio de sesión, registro, recuperación de contraseña, perfil y ajustes. |
| Oyente (Free / Premium) | P05–P12 | Inicio, búsqueda, reproductor, biblioteca, contenido, Premium, letras y Jam. |
| Artista / Creador | P13–P16 | Panel de creador, lanzamientos, analítica y monetización. |

## Flujos representados

- **Oyente:** autenticación → inicio → búsqueda o biblioteca → detalle de contenido → reproductor → letras y Jam.
- **Premium:** acceso a la biblioteca y presentación de la suscripción cuando se intenta utilizar una función Premium.
- **Creador:** autenticación → panel → gestión de lanzamientos, analítica de audiencia o monetización.

## Funcionamiento interactivo

- La pestaña **Bocetos / Sketches** muestra las 16 pantallas como tarjetas.
- La pestaña **Diagramas de Secuencia / Flujos** presenta los recorridos de oyentes y creadores.
- La pestaña **Código / Prompt para Archify Agent** contiene la especificación JSON de pantallas y rutas.
- El diseño utiliza una temática inspirada en Spotify y se adapta a distintos tamaños de pantalla.

## Tecnologías utilizadas

- HTML5 para la estructura y el contenido.
- CSS3 para los bocetos, estilos y distribución adaptable.
- JavaScript para la navegación entre pestañas.
- JSON para documentar pantallas, roles y rutas del diagrama.
- GitHub Pages para publicar el prototipo.

## Estructura de la práctica

- [`index.html`](./index.html): prototipo interactivo del diagrama de secuencia.
- [`readme.md`](./readme.md): descripción, contenido y enlace de publicación.

## Resultado

Prototipo web autónomo para consultar los bocetos de pantalla, analizar los flujos de navegación y reutilizar la especificación de rutas.

## Estado

| Práctica | Nombre | Tema | Estatus |
|---|---|---|---|
| 06 | Diagrama de Secuencia de Pantallas de Spotify | Flujos de navegación móvil | Completada [x] |