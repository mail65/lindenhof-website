# Changelog – Lindenhof Website

## 2026-05-23

### Fixes
- **Willkommen-Bild wiederhergestellt** – Layout mit Luftbild + „1971 Gegründet" Badge zurückgebracht (war versehentlich entfernt worden)
- **Alle Bilder lokal gespeichert** – Keine externen jimcdn.com URLs mehr → zuverlässiges Laden auf allen Geräten
- **Galerie-Karussell** – Lightbox war schwarz (img hatte display:none). Komplett neu gebaut: Prev/Next-Buttons, Swipe-Geste auf Mobile, Tastatur-Navigation (←→ + ESC), Bildnummer-Anzeige
- **Tanja-Foto Zuschnitt** – object-position auf 30% 40% korrigiert für besseren Gesichts-Ausschnitt auf Mobile
- **Willkommen-Bild Broken-Icon** – Ursache: jimcdn Referrer-Check. Behoben durch lokales Hosting aller Bilder
- **Bildqualität** – Alle 14 Bilder aufgewertet: Upscaling, Helligkeit (+8–30%), Sättigung (+15–22%), Schärfung

### Änderungen (rückgängig gemacht)
- Willkommen-Sektion war auf „nur Text, kein Bild" umgestellt worden → auf Wunsch wiederhergestellt

---

## 2026-05-22 (Erstveröffentlichung)

### Neu
- Komplette neue Homepage gebaut (Single-Page, responsive)
- Hero mit Luftbild, Navigation, Willkommen, Anlage, Unterricht, Philosophie, Team, Galerie, Wetter, Live-Cam (Coming Soon), Stallservice, Kontakt
- Echte Fotos von pferdesport-lindenhof.de übernommen
- GitHub Pages Deployment: https://mail65.github.io/lindenhof-website/
- 20 initiale Commits
