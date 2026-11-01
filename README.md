# Carte des tensions — France

Carte interactive des manifestations, émeutes, interventions des forces de l'ordre et règlements de comptes en France, avec fond de rues (Plan IGN, OpenStreetMap, photos aériennes IGN).

- `index.html` : la carte (Leaflet).
- `data/evenements.json` : les événements, mis à jour chaque jour automatiquement.
- `data/departements.json`, `data/regions.json`, `data/dep2reg.json` : contours pour les vues par département et par région (IGN Admin Express).
- `data/lieux.json` : communes et populations (INSEE / Etalab), utilisé si la recherche d'adresse est indisponible.

Fonds : © IGN – Géoplateforme ; © contributeurs OpenStreetMap. Recherche d'adresse : Base Adresse Nationale.

## Carte des risques — Sahel et Afrique de l'Ouest (`/sahel/`)

Terrorisme et conflit armé, attaques de sites miniers, météo majeure et état des routes au Mali, au Niger, au Burkina Faso, au Sénégal et en Guinée.

- `sahel/index.html` : la carte (Leaflet), avec fond simplifié, OpenStreetMap ou photos satellite.
- `sahel/data/evenements.json` : les événements, mis à jour chaque jour automatiquement.
- `sahel/data/*.json` : frontières, régions, routes, cours d'eau et villes (Natural Earth, domaine public).

Fonds : © contributeurs OpenStreetMap ; imagerie © Esri.
