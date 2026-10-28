# Derrotero: explorador geográfico de la Mapoteca Digital de la BNC

Explorador geográfico de la [Mapoteca Digital de la Biblioteca Nacional de Colombia](https://www.bibliotecanacional.gov.co/es-co/colecciones/biblioteca-digital/mapoteca/Paginas/index.aspx),
al modo de MapRank Search: tres vistas (Explorar, Cobertura, Datos) construidas sobre el inventario MAPOTECA_2025.7 a partir del
rectángulo envolvente de cada uno de los 2 668 registros; filtros por década, tipología y fondo; densidad de coberturas; cartogramas por
serie, siglo, tipología y departamento; registros con coordenadas por revisar.

Concepción, diseño, fuentes y validación: Sebastián Díaz Ángel; desarrollo asistido por IA (Claude).

`index.html` es autocontenido (datos y mapa base incrustados). Carga desde Internet solo las miniaturas y fichas de la Mapoteca,
los mosaicos de Map Warper de los mapas ya georreferenciados y los mapas base de Esri. Mapa base: Natural Earth (dominio público).
Publicable tal cual con GitHub Pages (Settings → Pages → Deploy from a branch → main / root).
