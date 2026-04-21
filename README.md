# Madrid — Mapa de calor: Precio × Estudiantes

Mapa interactivo que cruza el precio de habitación en alquiler con la densidad estudiantil por barrios de Madrid.

## 🗺️ Ver el mapa

👉 **[Abrir mapa interactivo](https://TU-USUARIO.github.io/madrid-heatmap/)**

*(Sustituye `TU-USUARIO` por tu nombre de usuario de GitHub)*

## Datos incluidos

- **120+ barrios** de Madrid con coordenadas GPS reales
- **Precio de habitación** en rango €/mes (datos 2025-2026)
- **Densidad estudiantil** en escala 1-5 estrellas
- **21 distritos** agrupados en 4 tiers de precio

## Fuentes de datos

- Idealista (informes de precios por barrio)
- Fotocasa (índice inmobiliario)
- Bankinter (análisis de barrios)
- Comunidad de Madrid (localización universidades)
- Portal de datos abiertos del Ayuntamiento de Madrid

## Funcionalidades

- 🔄 Alternar entre vista combinada, solo precio o solo estudiantes
- 🏷️ Filtrar por tier (Premium, Alto, Medio, Asequible)
- 🖱️ Hover para ver detalle de cada barrio
- 📱 Responsive (funciona en móvil)
- 🗺️ Mapa real con tiles CartoDB sobre OpenStreetMap

## Tecnologías

- [Leaflet.js](https://leafletjs.com/) para el mapa interactivo
- [CartoDB Dark Matter](https://carto.com/basemaps/) tiles
- HTML/CSS/JS puro (sin dependencias de build)

## Cómo desplegar

1. Fork este repositorio
2. Ve a **Settings → Pages**
3. En "Source" selecciona **Deploy from a branch**
4. Selecciona la rama `main` y carpeta `/ (root)`
5. Guarda y espera ~1 minuto
6. Tu mapa estará en `https://tu-usuario.github.io/madrid-heatmap/`

---

*Proyecto de data analytics — Análisis del mercado de alquiler estudiantil en Madrid*
