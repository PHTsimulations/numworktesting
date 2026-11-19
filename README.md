# Aero Database — NumWorks external app (source prototype)

Offline aircraft type and airline code reference for NumWorks Epsilon external apps.

## Current prototype features
- Browse a curated aircraft-type list (ICAO-style designators)
- Browse a curated airline list with IATA, ICAO, callsign and country fields
- Detail pages and simple calculator-key navigation
- Offline; no network connection required

**Important:** this is a prototype dataset, not an authoritative or exhaustive database. Codes and callsigns should be checked against official/current sources before relying on them.

## Build
This project targets the official NumWorks EADK/NWLink C SDK. Install a compatible ARM GNU embedded toolchain and Node.js/npm, then adapt/use the official `epsilon-sample-app-c` Makefile template. The SDK/compiler is not bundled in this archive.

Official app docs and template:
- https://github.com/numworks/epsilon-sample-app-c
- https://github.com/numworks/epsilon/tree/master/epsilon/eadk

Once built, install the generated `.nwa` through NumWorks' external-app uploader: https://my.numworks.com/apps

## Keyboard
- Up/Down: browse items
- OK: view details
- Back: return to previous menu

## Planned
- Code search (enter designator / IATA / ICAO / callsign)
- FAA registry search and registration data importer
- Expandable database generation script and official-data provenance metadata
- UI polish and testing on calculator / simulator
