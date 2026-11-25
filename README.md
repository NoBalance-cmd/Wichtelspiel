# 🎄 Berndt – Der Weihnachts-Wichtel
Ein Weihnachts-Stealth-Abenteuer im Frohnau-Stil (Berlin), spielbar in **einer einzigen HTML-Datei** – jetzt mit **Musik** und in **2D- und 3D-Version**.

## Zwei Versionen
| Datei | Darstellung | Besonderes |
|---|---|---|
| `berndt-weihnachtsspiel.html` | 2D-Karte (detaillierte Sprites- u. Szenerie-Grafik) | sehr schnell, läuft überall |
| `berndt-3d.html` | **3D** (Three.js, atmosphärische 3D-Welt: Schneefall, Sterne behaglicher Low-Poly-Stil Mond nachts, Schornstein-Rauch, Lichtkegel unter Laternen, Kirchturm mit Uhr, möblierte Räume) | Kamera mit gedrückter Maustaste drehen (beim 'Öffnen kurz Internet nötig – Three.js kommt aus dem CDN) |

Beide haben dieselben Quests, NPCs, Minispiele, Tag/Nacht (2 min) und Kalender (4 min), Speichern/Laden und **Musik (🔊 Jingle Bells, Taste-Button oben rechts)**.

## Spielen
1. Datei herunterladen (siehe Tabelle)
2. Doppelklick → öffnet sich im Browser
3. **Enter** zum Starten (Musik startet automatisch, kann per 🔊-Button an/aus)

## Steuerung (beide Versionen)
| Taste | Aktion |
|---|---|
| WASD / Pfeile | Berndt bewegen |
| E | Benutzen / aufheben / reden |
| Q | Quests annehmen & ansehen |
| 1–8 | Gegenstände aus der Hotbar einsetzen |
| Maus ziehen | (nur 3D) Kamera drehen |

## Spielprinzip
- 4 **Hauptquests** bis Tag 24 (sonst verloren): Weihnachtsbeleuchtung im ganzen Dorf, Kirchweg freischaufeln, Orgel in der Kirche reparieren, 5 Wunschzettel aus 5 Gärten → Postkasten
- 8 Nebenquests: Baum schmücken, Adventskranz (4 Kerzen), Schneemann, Weihnachtsbrief, Glitzer mit Lupe, Nikolaus-Mandarinen, Zimtstange für Oma, Spielzeugmaus für den Kater
- Verdachtsradien bei **allen Menschen und Tieren** im ganzen Dorf – die Leiste sinkt nie; 60 Sekunden kumulativ in Radien = erwischt
- Tag/Nacht alle 2 Minuten (mit Dunkelheit + Lichtkegel um Berndt), Kalender alle 4 Minuten
- Tag 6: Nikolaus (vom Kamin bis zur Haustür, 4 Mandarinen im Kinderzimmer) · Tag 24: Gänsebraten-Fest + Weihnachtsmann mit 4 Geschenken
- ⏩ Zeit ×1/×5/×15 – spült die Tage echt vor
- 📾 Speichern als Datei (Download) + Autosave im Browser
