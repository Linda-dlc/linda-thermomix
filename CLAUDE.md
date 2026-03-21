# Linda Thermomix Website – Claude Code Kontext

## Projekt
- Website für Linda De La Cruz Perea, Thermomix-Repräsentantin
- Live: https://linda-thermomix-mainz.netlify.app
- GitHub: https://github.com/Linda-dlc/linda-thermomix
- Tech: Astro + Tailwind CSS

## Deploy
Nach jeder Änderung:
cd ~/linda-thermomix/website
git add .
git commit -m "Beschreibung der Änderung"
git push
→ Netlify deployed automatisch in 1-2 Minuten. KEIN npx vercel mehr nötig!

## Ordnerstruktur
- src/pages/ → alle Seiten (.astro Dateien)
- public/assets/angebote/ → Angebotsbilder (angebot-1.jpg, angebot-2.jpg, angebot-3.jpg)
- public/assets/katalog/ → Katalogbild
- public/assets/fotos/ → Linda's Fotos (linda-hero.jpg)
- public/assets/erlebniskochen.jpg → Erlebniskochen-Foto auf Startseite

## Design
- Farben: Terracotta #C17A5A, Cremeweiß #F5F0E8, Salbeigrün #7A9B76
- Fonts: Playfair Display (Überschriften), Source Sans 3 (Fließtext)

## Kontakt Linda
- Name: Linda De La Cruz Perea
- Tel: 0176 31276883
- Mail: linda.de-la-cruz-perea@thermomix-kundenberatung.de
- Region: Nackenheim, Mainz & Umgebung

## Häufige Aufgaben
- Angebotsbild tauschen: public/assets/angebote/angebot-X.jpg ersetzen → git push
- Katalog tauschen: public/assets/katalog/ Bild ersetzen → git push
- Neues Element einbauen: src/pages/ entsprechende .astro Datei bearbeiten
