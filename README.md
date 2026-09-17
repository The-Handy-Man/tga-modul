# TGA MODUL – Redesign (Entwurf)

Dieser Ordner enthält den Quellcode des neuen Startseiten-Entwurfs für tga-modul.de.

- `Main.dc.html` – die Design-Komponente (HTML/CSS, mit eingebetteten Bearbeitungs-Tags für den Claude-Design-Editor)
- `canvas.json` – Layout-/Canvas-Metadaten des Entwurfs

**Live-Ansicht / Weiterbearbeitung:** https://claude.ai/artifact/8SfQTZqa79pBcDzvMxU6ub

`Main.dc.html` ist kein eigenständig lauffähiges HTML-Dokument – es referenziert eine Runtime (`support.js`) und Editor-spezifische Tags (`<x-dc>`, `{{platzhalter}}`), die nur innerhalb des Claude-Design-Canvas funktionieren. Für eine produktionsreife, eigenständige HTML/CSS-Version bitte Bescheid geben, dann exportiere ich eine reine statische Fassung.
