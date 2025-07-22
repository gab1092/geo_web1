# geo_web1
Prueba de visualizador web

Este proyecto es un visualizador geoespacial interactivo basado en Leaflet.js que permite a los usuarios cargar, visualizar y analizar datos geográficos en formatos GeoJSON y Shapefile, así como realizar mediciones y exportar mapas.

## Características

* **Visualización de Mapas Base:** Alterna entre diferentes mapas base (Océano, Calles, Satélite, Claro).
* **Carga de Datos Geoespaciales:** Soporta la carga de archivos GeoJSON (.geojson, .json) y Shapefiles (.zip).
* **Configuración de Capas:**
    * Cambia modos de visualización (simple, clasificado, categórico).
    * Selecciona variables numéricas y categóricas.
    * Ajusta el número de clases y las paletas de colores.
    * Modifica el estilo simple (color de relleno, contorno).
* **Gestión de Capas:** Reordena las capas cargadas con la funcionalidad de arrastrar y soltar.
* **Medición en el Mapa:** Dibuja líneas y polígonos para medir distancias (km) y áreas (hectáreas).
* **Deshacer Acciones de Dibujo:** Utiliza `Ctrl + Z` para deshacer la última forma dibujada.
* **Exportación de Mapa:** Guarda la vista actual del mapa como una imagen PNG.
## Créditos y Tecnologías Utilizadas

Este visualizador geoespacial utiliza las siguientes librerías de código abierto:

* **Leaflet.js:** Una librería JavaScript de código abierto para mapas interactivos aptos para móviles.
    * [Sitio web de Leaflet](https://leafletjs.com/)
    * Licencia: [BSD 2-Clause](https://github.com/Leaflet/Leaflet/blob/main/LICENSE)
* **Leaflet.draw:** Un plugin para Leaflet que añade herramientas de dibujo y edición.
    * [Repositorio de Leaflet.draw](https://github.com/Leaflet/Leaflet.draw)
    * Licencia: [MIT License](https://github.com/Leaflet/Leaflet.draw/blob/develop/LICENSE)
* **Leaflet.GeometryUtil:** Utilidades geométricas para Leaflet.
    * [Repositorio de Leaflet.GeometryUtil](https://github.com/makinacorpus/Leaflet.GeometryUtil)
    * Licencia: [MIT License](https://github.com/makinacorpus/Leaflet.GeometryUtil/blob/master/LICENSE)
* **Leaflet-image:** Exporta mapas de Leaflet como imágenes.
    * [Repositorio de Leaflet-image](https://github.com/mapbox/leaflet-image)
    * Licencia: [BSD 2-Clause](https://github.com/mapbox/leaflet-image/blob/master/LICENSE)
* **Shp.js:** Un analizador de Shapefiles para navegadores web.
    * [Repositorio de Shp.js](https://github.com/calvinmetcalf/shp.js)
    * Licencia: [BSD 2-Clause](https://github.com/calvinmetcalf/shp.js/blob/master/LICENSE)
* **Simple Statistics:** Librería JavaScript para estadísticas básicas.
    * [Sitio web de Simple Statistics](https://simplestatistics.org/)
    * Licencia: [MIT License](https://github.com/simple-statistics/simple-statistics/blob/main/LICENSE)
* **Sortable.js:** Una librería JavaScript para arrastrar y soltar listas.
    * [Sitio web de Sortable.js](https://sortablejs.github.io/Sortable/)
    * Licencia: [MIT License](https://github.com/SortableJS/Sortable/blob/master/LICENSE)
