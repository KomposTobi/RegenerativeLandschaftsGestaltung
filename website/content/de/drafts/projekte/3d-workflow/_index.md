---
title: "3D Landscape Workflow — Digitale Geländemodelle"
description: "Von der Drohne zum 3D-Modell: Photogrammetrie, GIS und Blender für regenerative Gestaltung"
# source: knowledge/01-projects/3d-landscape-workflow/
# source: knowledge/01-projects/3d-landscape-workflow/drone-photogrammetry.md
status: draft
---

**Status:** Konzept / Entwicklung  
**Typ:** Technischer Workflow für Standortanalyse und Visualisierung  
**Unternehmens-Phase:** Phase 1-2 (Analyse + Design)

---

## Warum 3D?

Regenerative Gestaltung beginnt mit dem Verständnis des Geländes. 2D-Karten zeigen Höhenlinien — aber erst im 3D-Modell werden Wasserflüsse, Blickbeziehungen und Vegetationsstruktur wirklich greifbar.

Der 3D Landscape Workflow verbindet Drohnen-Photogrammetrie, GIS-Analyse und fotorealistische Visualisierung in Blender — von der Rohdatenerfassung bis zum begehbaren Gelände-Modell.

---

## Der Workflow

### Schritt 1: Datenerfassung vor Ort

**Drohne:** DJI Mini 3 (48MP, unter 250g)  
**GCP-Messung:** ARDUSIMPLE RTK Handheld 2 (cm-Genauigkeit)  
**Software:** Agisoft Metashape für Photogrammetrie

Ergebnis: Georeferenziertes 3D-Punktwolkennetz + Orthofoto + Digitales Geländemodell (DGM/DTM)

### Schritt 2: GIS-Analyse in QGIS

Import der Rohdaten und Aufbereitung:
- **DGM → Terrain-Mesh** (Höhenmodell für 3D-Export)
- **Orthofoto → Textur** (Satellitenbild als Oberflächentextur)
- **Baumdetektion** (DeepForest → Position, Art, Kronendurchmesser)
- **Baumhöhe** aus CHM (Canopy Height Model)
- **Gebäude-Footprints** mit Extrusionshöhe

### Schritt 3: 3D-Modell in Blender

Import via BlenderGIS Addon:
- Terrain-Mesh aus DGM
- Geometry Nodes für Vegetation (Punkte → 3D-Bäume)
- Gebäude-Extrusion aus Footprints
- Tageslicht-/Jahreszeiten-Simulation

### Schritt 4: Design & Präsentation

Im 3D-Modell können regenerative Maßnahmen direkt platziert werden:
- Swales und Gräben im Gelände modellieren
- Vegetationsstruktur visualisieren
- Regenwasserabfluss simulieren
- Kundenpräsentation mit fotorealistischen Renderings

---

## Hardware & Kosten

| Komponente | Option Einsteiger | Option Professionell |
|------------|-------------------|---------------------|
| Drohne | DJI Mini 3 (~500€) | DJI Mavic 3 Enterprise (~7.000€) |
| GCP-Messung | ARDUSIMPLE RTK (~559€) | — |
| Genauigkeit | ±5-10cm (mit GCPs) | ±1cm (mit RTK) |
| Shutter | Elektronisch (Rolling) | Mechanisch (kein Roll) |

---

## Bezug zu anderen Projekten

→ GIS-Methodik aus Bachelorarbeit erweitert  
→ Drohnendaten ergänzen Weiz-Analyse (höhere Auflösung)  
→ Blender-Visualisierung für Ansitz Hofer Kundenpräsentation  
→ Pearl River Eco Design (Ben Missimer) als Benchmark: GIS + Drone + Permaculture

---

*[Dieser Entwurf basiert auf dem Drone-Photogrammetrie Wissen aus dem Knowledge-System. Bilder und Screenshots fehlen noch.]*
