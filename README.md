# Awesome-Web-Mapping-Platform

## Top Web Mapping Platform Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Interactive Maps, Geospatial APIs & Location Intelligence*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Web Mapping**. These tools enable developers to embed interactive maps, geocode addresses, calculate routes, and build location-aware applications for web and mobile.



**Examples** include Google Maps Platform, Bing Maps, Mapbox, HERE Technologies, TomTom, Esri ArcGIS Online, OpenStreetMap, MapLibre, Stadia Maps, and MapTiler (the category leaders).



**Open-source emphasis**: Web mapping is one of the strongest open-source domains, built on the **OpenStreetMap** data foundation. **MapLibre GL JS**, **Leaflet**, **MapStore**, and **Pelias** collectively power interactive maps, geocoding, and GIS applications worldwide, with **MapLibre** emerging as the de facto open-source successor to Mapbox GL JS after the 2020 license change .



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Google Maps Platform](https://mapsplatform.google.com/)**  

  The most widely used mapping platform with unmatched global data quality, Street View, and Places. March 2025 pricing overhaul replaced the $200 monthly credit with per-SKU free caps (10K Essentials, 5K Pro, 1K Enterprise). No default spending cap — budget alerts notify but do not stop charges. At scale, costs 7–14x Mapbox .



- **[Bing Maps](https://www.bingmapsportal.com/)**  

  Microsoft's mapping platform with strong enterprise integration and Azure ecosystem ties. Free tier for basic usage; enterprise pricing for high-volume deployments.



- **[Mapbox](https://www.mapbox.com/)**  

  Developer-favorite mapping platform with beautiful customizable styles, native offline support, and 50,000 free GL JS map loads monthly. Powers Strava, AllTrails, and Snapchat. First paid tier at $5 per 1,000 loads. Strong vector tile and navigation SDKs .



- **[HERE Technologies](https://www.here.com/)**  

  Enterprise mapping platform with automotive-grade data, location services, and strong presence in connected vehicle and logistics.



- **[TomTom](https://www.tomtom.com/)**  

  Mapping and location technology with 200K free Orbis tile requests monthly, 20K geocodes, and 20K reverse geocodes. Strong routing and traffic APIs .



- **[Esri ArcGIS Online](https://www.esri.com/)**  

  Enterprise GIS platform with comprehensive mapping, spatial analysis, and app-building tools. The industry standard for professional GIS workflows.



- **[Stadia Maps](https://stadiamaps.com/)**  

  Developer-friendly mapping platform with 200K free credits monthly (non-commercial), Starter at $20/mo. Stops requests at published limits by default. SDKs are BSD licensed .



- **[MapTiler](https://www.maptiler.com/)**  

  OpenStreetMap-based mapping services with hosted and self-hosting options. Free plan includes 5,000 map sessions; Flex at $30/mo with 25,000 sessions. Supports MapLibre GL JS .



## Open-Source GitHub Projects



- **[MapLibre GL JS](https://github.com/maplibre/maplibre-gl-js)**  

  The leading open-source TypeScript library for GPU-accelerated vector maps, **11K+ GitHub stars** and BSD-3-Clause license . Community-governed fork of Mapbox GL JS v1.13 created after Mapbox went proprietary in 2020 . Renders interactive maps from vector tiles and MapLibre Style Specification using WebGL (WebGPU in development). Supports globe view, 3D terrain, building extrusions, and custom 3D layers. **Zero licensing costs** — you only pay for tile hosting .



- **[Leaflet](https://github.com/Leaflet/Leaflet)**  

  The most widely used open-source JavaScript library for mobile-friendly interactive maps, **42 KB gzipped** with no external dependencies . BSD-2-Clause licensed. Leaflet 2.0.0-alpha.1 (August 2025) modernizes the codebase: dropped IE support, adopted Pointer Events, published as ESM module, and added automatic OSM attribution . Uses raster tiles by default, making it simple and fast to start with . Extensive plugin ecosystem for routing, clustering, and drawing.



- **[OpenStreetMap](https://www.openstreetmap.org/)**  

  The free, community-driven map of the world — the data foundation for most open-source mapping. **10+ million registered users, 2+ million active contributors**, with 45K active contributors monthly . Data licensed under ODbL; map tiles under CC BY-SA. Used by Meta, Microsoft, Amazon, Mapbox, TomTom, and the United Nations . **The de facto geographic data source for open-source mapping**.



- **[MapStore](https://github.com/geosolutions-it/MapStore2)**  

  Open-source WebGIS platform built on React and Redux for creating and sharing maps, dashboards, and geostories. Supports OpenLayers, Leaflet, and Cesium (with MapLibre GL planned) . Features WMS/WFS/WMTS/TMS/CSW/3D Tiles support, user/group permissions, WFS-T editing, and deep customization. Used by City of Genova, City of Florence, Halliburton, and Austrocontrol . **The most comprehensive open-source platform for building geoportals and GIS applications**.



- **[Nominatim](https://github.com/osm-search/Nominatim)**  

  Open-source geocoding software for OpenStreetMap data. Converts addresses to coordinates and coordinates to addresses. The official OSM geocoder, available via public API (1 request/sec limit) or self-hosted for higher volume .



- **[Pelias](https://github.com/pelias/pelias)**  

  Modular open-source geocoder using Elasticsearch, **3,190+ GitHub stars** . On-premise geocoder with your own dataset for specific regions or countries . Note: Pelias has had robustness issues — one study showed 61% top-level match rate for address geocoding, compared to 63% for Nominatim . **Not updated since February 2021** .



- **[GeoLibre](https://github.com/opengeos/GeoLibre)**  

  Free and open-source, lightweight, cloud-native GIS platform for visualizing, exploring, and analyzing geospatial data across web browsers, desktop, mobile, and Jupyter notebooks. MIT licensed, built on MapLibre and Python .



- **[Leaflet (R package)](https://github.com/rstudio/leaflet)**  

  R interface to Leaflet for creating interactive maps from the R console, RStudio, Shiny applications, and R Markdown documents. MIT licensed, CRAN package .



### Additional Strong Open-Source Options



- **GeoLibre** — MIT-licensed GIS platform for web, desktop, mobile, and Jupyter, built on MapLibre .

- **OSM Names** — Place name search using OpenStreetMap data .

- **Photon** — Open-source geocoder built on OSM + Elasticsearch, with on-premise deployment for specific regions .

- **Overpass API** — Query OpenStreetMap data directly via API .

- **GraphHopper** — Open-source routing engine with Route Optimization API .

- **OSRM** — Open Source Routing Machine, integrates with Leaflet Routing Machine .



**Frameworks for building custom web mapping solutions**: Choose based on rendering approach and scale. **Leaflet** for simple raster tile maps with minimal bundle size (42 KB) — the fastest path to a working map . **MapLibre GL JS** for vector tiles, 3D, globe view, and GPU-accelerated performance with no licensing fees . **MapStore** for full WebGIS portals with dashboards, permissions, and multi-engine support . For geocoding, use **Nominatim** (mature, OSM-native) or **Pelias** (Elasticsearch-based, but verify maintenance status) . The critical decision: raster vs vector tiles. Raster (Leaflet + OSM tiles) is simple but less flexible. Vector (MapLibre + tile provider) enables dynamic styling, dark mode, and 3D — but requires a tile source (self-hosted or hosted like MapTiler/Stadia) .



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Map data accuracy varies by region and source. OpenStreetMap coverage is strong in urban areas but may be incomplete in rural or developing regions compared to Google Maps .

- Self-hosted solutions require infrastructure for tile servers, geocoding engines, and routing services. **OSM public tile servers are not production CDNs** — host your own tiles or use a tile provider for high-traffic applications .

- **Google Maps' March 2025 pricing changes** eliminated the flat $200 credit, making cost management more complex for multi-API applications .

- The open-source ecosystem provides strong rendering, geocoding, and GIS foundations, but managed tile hosting, global data coverage, and Street View remain primarily commercial offerings.



---



**Made for GIS developers, web developers, and location intelligence engineers.**  

Let's make web mapping more open, transparent, and accessible.
