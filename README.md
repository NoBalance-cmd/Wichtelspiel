# 🎄 24 Days till Christmas
Ein Weihnachts-Stealth-Abenteuer im Frohnau-Stil (Berlin), spielbar in **einer einzigen HTML-Datei**.

## Die Spiel-Versionen
| Datei | Darstellung | Besonderes |
|---|---|---|
| `berndt-weihnachtsspiel.html` | 2D-Karte (detaillierte Sprites- u. Szenerie-Grafik) | sehr schnell, läuft überall – **empfohlen & 100 % offline** |
| `berndt-weihnachtsspiel-detailliert.html` | 2D-Karte **Extra-Detail-Version**: Wichtel, Menschen, Hunde, Vögel, Katzen, Tannen, Weihnachtsbaum, Laternen & Schneemann mit Verläufen, Konturen, Bezier-Formen, animierten Gliedmaßen, Schneekappen, Girlanden & Laternen-Glow | für starke PCs, ebenfalls 100 % offline, gleiche Steuerung wie die Standard-2D-Version |
| `berndt-3d.html` | 3D-Dorf (Three.js) | experimentell, braucht beim Öffnen kurz Internet (CDN) |

Quests, NPCs, Minispiele, **2-Minuten-Tage** (ein ganzer Tag = Tag + Nacht), Speichern/Laden und **Musik** gibt es in allen 2D-Versionen.

## Spielen
1. Datei herunterladen von deinem USB-Stick
2. Doppelklick → öffnet sich im Browser
3. **Enter** zum Starten (**Musik startet nie von selbst – erst auf Klick auf den 🔊-Button**; Tür- & Warngeräusche eher wie im echten Haus klingen automatisch)

## Steuerung (beide Versionen)
| Taste | Aktion |
|---|---|
| WASD / Pfeile | Berndt bewegen |
| E | Benutzen / aufheben / reden |
| Q | Quest-Kiste öffnen (schließt auch mit **✕ Schließen**, ESC oder Klick daneben) |
| M | **Karte** des ganzen Terrains öffnen/schließen |
| 1–8 | Gegenstände aus der Hotbar einsetzen |
| L (am Titelbild) | Auto-Speicherstand laden |

## Spielprinzip
- 4 **Hauptquests** bis Tag 24 (sonst verloren): Weihnachtsbeleuchtung im ganzen Dorf, Kirchweg freischaufeln, Orgel in der Kirche reparieren, 5 Wunschzettel aus 5 Gärten → Postkasten
- 9 Nebenquests: Baum schmücken, Adventskranz (4 Kerzen), Schneemann, Weihnachtsbrief, Glitzer mit Lupe, Nikolaus-Mandarinen, Zimtstange für Oma, Spielzeugmaus für den Kater, **Streunerkatze Mimi zähmen**
- **Intro-Cutscene**: Schlittenflug mit dem Weihnachtsmann über das nächtliche Dorf, Fallschirm-Absprung, dann ein **Dach-Jump-and-Run über drei Häuserdächer** (Leertaste = Springen, jede andere Taste überspringt) – Landung vor der Kirche. Erwischte Dach-Lücken starten neu
- Verdachtsradien bei **allen Menschen und Tieren** im ganzen Dorf – die Leiste sinkt nie; ca. **45 Sekunden** kumulativ in Radien = erwischt (Nähe beschleunigt)
- **Ein ganzer Tag = 2 Minuten** (Morgen, Tag, Abend und Nacht je 30 Sekunden) mit Dunkelheit + **Lichtkegel um Berndt**; der Küchen-Kalender zählt jeden Tag um 1 hoch
- Die **S1**: alle 2 Minuten rauscht eine **rot-gelbe Bahn** über die Gleise am Ostrand – **tödlich! Nicht auf die Gleise stellen!**
- **Mehr begehbare Häuser mit eigenem detailliertem Interieur**: Müller (Backstube), Krüger (Leseecke), Schulz (Musikzimmer), Lehmann (Festsaal) + Alte Scheune (dort liegt der **Tannenast** für den Schneemann!)
- **Frisch aufgepeppt**: Buntglasfenster in der Kirche, Bahnhofsuhr & Kofferstapel, die **Orgel am Altar** (Hauptquest dort reparieren), Werkzeugwand in der Scheune, Girlanden, Bilderrahmen, Sockelleisten u.v.m.
- **🐈 Streunerkatze Mimi zähmen** (Nebenquest): Fisch (lieber!) oder Fleisch besorgen – beide sind im Dorf versteckt –, am Eissee anreden und füttern. Danach folgt sie dir überall hin (ohne Verdacht zu erzeugen)
- **In der Nacht vom 5. auf den 6. Tag**: der Nikolaus läuft dynamisch seine Route – er durchquert das Haus, in dem du gerade bist, oder zweimal über die Straße, wenn du draußen bist (4 Mandarinen im Kinderzimmer) · Tag 24: Gänsebraten-Fest + Weihnachtsmann mit 4 Geschenken (**gleiche Lauf-Animation**, ebenfalls dynamisch)
- ⏩ Zeit – spült die Tage vor: **×1 / ×5 / ×15, maximal ×15**
- Nach Schleichen-Sounds: Türen knarren beim Kartenwechsel, NPCs geben Warn-Piep von sich
- **Karten-Hinweis**: in Innenräumen zeigt die Karte bewusst keine Live-Position an (keine irreführenden Punkte, z. B. vermeintlich auf den Gleisen)
- **🐱 Neue Katzen-Grafik** mit Laufanimation (Beine, wedelnder Schwanz, Schnurrhaare, Ohr-Bewegung)
- **Unsichtbare Wände sichtbar**: Haus-Innenwände werden jetzt gezeichnet
- Die aktive Quest wird nur noch **einmal oben rechts in der Leiste** (neben Musik & Zeit) angezeigt (Doppel-Anzeige entfernt)
- **Vor der Quest-Annahme gefundene Gegenstände zählen automatisch** – nichts geht verloren
- 💾 Speichern als Datei (Download) + Autosave im Browser >>>>> Datei auf den USB-Stick ziehen und jederzeit und überall den passenden Spielstand haben

## Dorf & Karte
Das Dorf ist **3800 × 2200** groß: Einkaufsstraße mit Zebra-Streifen, Ost-Bezirk (Scheune, Häuser Sandmeier & Wattebach, vertikale Seitenstraße), Eissee und Rodelhügel, 11 begehbare Villen-Grundstücke mit Zäunen. Die **S1** fährt am Bahnhof Frohnau: Norden → **Oranienburg**, Süden → **Wannsee** (Gleisanlage mit Anzeigetafel an der S1 im Bahnhofs-Interieur).
