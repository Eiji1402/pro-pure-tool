# PCC Pro/Pure Tool – iPhone "App" (PWA) Paket

Dieses Paket macht aus deiner HTML eine installierbare Web-App (PWA), die auf iPhones über Safari
zum Home-Bildschirm hinzugefügt werden kann und danach offline läuft (Cache).

## Inhalt
- index.html (deine HTML + PWA-Hooks)
- manifest.json
- service-worker.js (Offline-Cache)
- /icons (App-Icons)

## So nutzt du es (Kurz)
1) Lege den kompletten Ordner auf einen Server, der per **HTTPS** erreichbar ist.
   - Für Tests im WLAN geht auch ein lokaler Server am PC, aber iOS ist mit HTTPS am glücklichsten.
2) Öffne auf dem iPhone **Safari** und rufe die URL zu `index.html` auf.
3) Tippe auf **Teilen** → **Zum Home-Bildschirm**.
4) Einmal starten lassen, damit der Offline-Cache aufgebaut wird.
5) Danach Flugmodus testen: App öffnen → sollte weiterhin laufen.

## Wichtig
- Installation auf iOS geht praktisch nur über Safari (nicht Chrome).
- Andere iPhones können es installieren, sobald sie die gleiche URL erreichen.