# Rutas Peatonales — Estadio Azteca · Copa del Mundo 2026

Mapa web interactivo con las rutas peatonales de acceso al Estadio Azteca para el Mundial 2026.

## Funcionalidades
- Mostrar/ocultar cada ruta por capa
- Popups con información al hacer clic
- Leyenda de colores
- Herramienta para medir distancias
- Mapa base oscuro (CartoDB Dark)

## Cómo usar
1. Clona el repositorio
2. Abre `index.html` en un servidor local (o activa GitHub Pages)
3. Para GitHub Pages: Settings → Pages → Branch: main → Save

## Archivos de datos
Los archivos `.geojson` en `/data` fueron exportados desde QGIS con CRS EPSG:4326.

## Tecnologías
- [Leaflet.js](https://leafletjs.com/) v1.9.4
- [Leaflet Measure](https://github.com/ljagis/leaflet-measure)
- [CartoDB Basemaps](https://carto.com/basemaps/)
