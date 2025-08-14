# ruta
📍 Planificador de Rutas con OSM + OSRM
Herramienta web para planificar rutas de entrega optimizadas usando OpenStreetMap (Nominatim) y OSRM, sin necesidad de APIs de pago. Permite cargar direcciones manualmente o desde un CSV, geocodificarlas y calcular el orden óptimo de visita.

https://via.placeholder.com/800x500/0f172a/22d3ee?text=Planificador+de+Rutas+OSM (Imagen ilustrativa)

🌟 Características
📌 Geocodificación con Nominatim (OpenStreetMap)

🚗 Optimización de ruta con OSRM (algoritmo TSP)

📂 Carga desde CSV o entrada manual

📊 Visualización en mapa interactivo (Leaflet)

📤 Exporta el orden optimizado a CSV

💻 100% cliente-side (no requiere backend)

🎨 Diseño responsive (funciona en móviles)

🛠 Tecnologías
Frontend: HTML5, CSS3, JavaScript vanilla

Mapas: Leaflet + OpenStreetMap

Geocodificación: Nominatim

Optimización de rutas: OSRM

CSV: PapaParse

🚀 Cómo usar
Agregar direcciones:

Manualmente: Completa los campos y haz clic en "Agregar"

Desde CSV: Usa el botón "Subir CSV" (formato: direccion,remitente,receptor)

Procesar:

Haz clic en "Procesar y Optimizar" para geocodificar y calcular la ruta óptima

Resultados:

Mapa interactivo con pines numerados en orden óptimo

Estadísticas de distancia y tiempo

Exporta a CSV con "Exportar orden"

⚙️ Requisitos
Navegador moderno (Chrome, Firefox, Edge)

Conexión a Internet (para usar OSM/Nominatim/OSRM)

📌 Notas importantes
Nominatim requiere 1 segundo de delay entre geocodificaciones

Para uso profesional, considera configurar tu email en NOMINATIM_EMAIL

OSRM es un servicio gratuito pero con límites de uso

📄 Licencia
Código libre bajo MIT License.


Datos de mapas © OpenStreetMap contributors.
