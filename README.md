# 🎄 24 Days till Christmas

*Berndt – Der Weihnachts-Wichtel*

Ein Weihnachts-Stealth-Abenteuer im Frohnau-Stil (Berlin), spielbar in **einer einzigen HTML-Datei** – 100 % offline, kein Installer, keine Internetverbindung nötig.

---

## Die Spiel-Versionen

| Datei | Darstellung | Besonderes |
|---|---|---|
| `berndt-weihnachtsspiel.html` | 2D-Karte mit detaillierten Sprites & Szenengrafik | sehr schnell, läuft auf praktisch jedem PC – **empfohlen & 100 % offline** |
| `berndt-weihnachtsspiel-detailliert.html` | 2D-Karte **Extra-Detail-Version**: Wichtel, Menschen, Hunde, Vögel, Katzen, Tannen, Weihnachtsbäume, Laternen & Schneemann mit Farbverläufen, Konturen, Bezier-Formen, animierten Gliedmaßen, Schneekappen, Girlanden & Laternen-Glühen | für starke PCs, ebenfalls 100 % offline, identische Steuerung |
| `berndt-3d.html` | 3D-Dorf (Three.js) | experimentell, **eingefroren** – braucht beim Öffnen kurz Internet (CDN) |

Alle Spielinhalte (Quests, NPCs, Minispiele, 2-Minuten-Tage, Speichern/Laden, Musik) sind in beiden 2D-Versionen identisch.

## So startest du

1. HTML-Datei auf den USB-Stick ziehen
2. Auf jedem PC: Doppelklick → öffnet sich im Standard-Browser
3. **ENTER** drücken, um zu starten
4. **Musik startet nie von selbst** – nur wenn du auf den 🔊-Knopf oben rechts klickst (Türknarzen & Warngeräusche im Spiel sind unabhängig davon aktiv)

---

## Das Spielprinzip

Du bist **Berndt**, ein kleiner Wichtel, der heimlich in einem Haus in Frohnau wohnt und im Advent Aufgaben erledigt, ohne von den Bewohnern oder Tieren gesehen zu werden:

- **Hauptquests bis Tag 24**: Alle 6 Hauptquests müssen bis **Tag 24** abgeschlossen sein. Ist Tag 24 vorbei, bevor alle fertig sind → verloren. Alle geschafft → Weihnachtssieg 🎁 – und du kannst **mit LEERTASTE weiterspielen** und Nebenquests fertig machen
- **Verdachts-System**: Jeder Mensch, jede Katze, jeder Hund und jedes andere Tier hat einen **Verdachtsradius** (gestrichelter Kreis). Betrittst du ihn, steigt die rote Verdachtsleiste oben rechts. Die Leiste **sinkt niemals** ab! Etwa **45 Sekunden** insgesamt in Verdachtsradien (Nähe beschleunigt stark) = **erwischt → verloren**. Zeigt ein NPC sein Ausrufezeichen („!") über dem Kopf: wegrennen!
- **Nachts schlafen alle** – die beste Zeit zum Schleichen. Nachts herrscht Dunkelheit, aber um Berndt gibt es einen **Lichtkegel**, damit du ihn immer siehst
- **Gefundene Gegenstände zählen rückwirkend**: Nimmst du eine Quest erst an, nachdem du bereits einen passenden Gegenstand hast, springt der Quest-Schritt automatisch weiter – nichts geht verloren

## Das Intro

Beim Spielstart segelst du mit dem **Weihnachtsmann auf seinem Schlitten** (mit galoppierenden Rentieren davor) über das nächtliche Dorf, springst mit einem **Fallschirm** ab und landest über ein **Jump-and-Run über drei Häuserdächer** (Leertaste/W/↑ = Springen) schließlich direkt **vor der Kirche**. Ein Fehler auf den Dächern startet den Dachlauf neu. Jede andere Taste überspringt das Intro.

## Steuerung

| Taste / Knopf | Aktion |
|---|---|
| WASD / Pfeiltasten | Berndt bewegen |
| **E** | Benutzen / aufheben / reden (Interaktionskreise im Spiel zeigen dir was) |
| **Q** | Quest-Kiste öffnen – Aufträge annehmen, Schritte lesen (schließt auch mit ✕, ESC oder Klick daneben) |
| **M** | Karte des ganzen Terrains öffnen/schließen |
| **1–9, 0** | Hotbar-Slot einsetzen (auch: direkter **Klick auf den Hotbar-Slot**) |
| ⏩ | Zeit umstellen **×1 / ×5 / ×15** (Maximum ×15 – mehr geht nicht) |
| 🔊 | Musik an/aus (ruhige „Stille Nacht", nur manuell) |
| 💾 / 📂 | Spielstand als Datei speichern / laden (oben rechts) |
| ENTER | Am Titelbild: neues Spiel · L = Auto-Speicherstand laden |

---

## Zeit, Kalender & Events

- **Ein ganzer Tag = 2 Minuten**: Morgen → Tag → Abend → Nacht (je 30 Sekunden), mit animierter Dunkelheit und Lichtkegel nachts
- Der **Kalender in der Küche** zeigt immer den aktuellen Tag an
- **In der Nacht vom 5. auf den 6. Tag** kommt der **Nikolaus**: Er läuft eine dynamische Route – durch das Haus, in dem du gerade bist, oder einmal über die Straße, wenn du draußen bist – und hinterlässt **4 Mandarinen im Kinderzimmer**
- **Tag 24**: Alle Menschen zieht es zum gedeckten **Esstisch mit Gänsebraten**; nachts kommt der **Weihnachtsmann** (gleiche Lauf-Animation wie der Nikolaus, ebenfalls dynamisch) und stellt **4 Geschenke unter den Weihnachtsbaum**
- **Die S1**: Alle 2 Minuten rauscht eine **rot-gelbe Bahn** über die Gleise – **Tödlich! Berührt sie dich, hast du sofort verloren!** (Am Bahnhof Frohnau: Norden → Oranienburg, Süden → Wannsee.)

## Die Welt: Dorf, Häuser & Innenräume

Das Dorf ist **3800 × 2200 px** groß: Einkaufsstraße mit Zebra-Streifen, Ost-Bezirk (Scheune, Häuser Sandmeier & Wattebach, Seitenstraße), Eissee mit Spielplatz, umzäunte Villen-Grundstücke – **jedes Haus hat seinen eigenen Garten** (in 5 davon wehen Wunschzettel). Neuer Mittelpunkt: ein **kleiner Kreisverkehr, der die Hauptstraße an dieser Stelle ersetzt**, mit dem großen, spitzen Dorf-Weihnachtsbaum (Kugeln + goldenem Stern) auf der Schneainsel in der Mitte – Baum und Insel sind fest blockiert, die Ringfahrbahn bleibt frei. Die Häuser Krüger, Schulz und Lehmann betritt man durch ihre **sichtbaren Haustüren an der Vorderseite** (Hofseite – durch das Zauntor, dann in den Türspalt treten).

Begehbare Orte mit eigenem Interieur:

| Ort | Innenraum |
|---|---|
| **Haus EG** (Berndt) | Flur, Küche (mit Adventskranz & Kalender), Wohnzimmer (Weihnachtsbaum, Schreibtisch, Sofa mit Katzenspielzeug), Esszimmer |
| **Haus OG** | Kinderzimmer, Schlafzimmer, Bad, Flur (hier wohnt auch Kater Murr) |
| **Keller** | Werkstatt-Regale: Werkzeugkiste, Kohle, Schaufel, Lichterkette, Wollmütze, Fisch |
| **Kirche** | Bänke, Buntglasfenster, **Orgel am Altar** (Hauptquest) |
| **Bahnhof Frohnau** | Bahnhofsuhr, Kofferstapel, Stromkasten, Postkasten, Gleisanlage |
| **Weihnachts-Laden** | Kugeln, Glocken, Lichterketten, Lupe, Briefpapier, Siegelstempel, Kerzen |
| **Haus Müller** | Backstube (Vanillekipferl!) |
| **Haus Krüger** | Leseecke mit Bücherregal |
| **Haus Schulz** | Musikzimmer mit Klavier |
| **Haus Lehmann** | Festsaal (Familienfoto) |
| **Alte Scheune** | Heulager + Werkzeugwand (Tannenast & Kohle für den Schneemann) |

**🚋 Stehende S-Bahn am Abstellgleis**: Direkt **südlich am Bahnhof Frohnau** steht auf einem eigenen Abstellgleis ein haltender Zug, den du betreten kannst (vom Bahnhofsvorplatz oder aus dem Bahnhofs-Inneren) – drinnen bewegt er sich nicht. In seinem Innenraum (Fenster mit Schnee, Bänke, Gepäcknetz, Haltestange) hat jemand **Weihnachtseinkäufe** liegen lassen…

**Lebendiges Haus & Dorf**: 6 Bewohner mit festen Laufrouten (Mama, Papa, Luise, Oma, Finn + **Kater Murr** mit Schlafbereich), plus Dorfbewohner (Frau Berg, Herr Klein, Postbote August, Herr Sommer, Frau Winter), Kirchenpfarrer, Bahnhofswärter, Verkäuferin, Scheunenhund Bo, Katze Minka, Hund Bello und ein Taubenpaar.

## Quests

**Hauptquests (bis Tag 24, sonst verloren):**

1. **Weihnachtsbeleuchtung im ganzen Dorf** (à la Berlin-Frohnau): 5 Lichterketten einsammeln → Stromkasten am Bahnhof einschalten
2. **Schneeschaufeln auf dem Kirchweg**: Schaufel finden → Kirchweg freischaufeln (Klick-Minispiel)
3. **Orgel in der Kirche reparieren**: Werkzeugkiste finden → Orgel-Minispiel im **Leichtmodus** (sichtbare farbige Reihenfolge zum Nachspielen)
4. **5 Wunschzettel aus 5 Gärten** → alle in den Postkasten am Bahnhof
5. **Vergessene Weihnachtseinkäufe**: Im stehenden Zug am Abstellgleis aufheben → an der Haustür des questmarkierten Hauses (goldener Pfeil) ablegen
6. **Weihnachtsbrief schreiben**: Papier + Stempel aus dem Laden → Wunsch am Schreibtisch wählen, versiegeln, einwerfen

**8 Nebenquests:**

| Quest | Kurz |
|---|---|
| Weihnachtsbaum schmücken | Kugel + Glocke finden → Klick-Minispiel am Baum |
| Adventskranz | 4 Kerzen in richtiger Reihenfolge anzünden (Küche) |
| Schneemann bauen | Tannenast + Kohle → 3-Schritt-Auswahl-Minispiel |
| Glitzer im Schnee | Lupe → 3 Eiskristalle im Garten von Haus Keiler aufspüren |
| Nacht des Nikolaus | In der Nacht von Tag 5→6 Mandarinen im Kinderzimmer einsammeln – die Quest lässt sich **auch nachträglich annehmen**, wenn der Nikolaus schon da war (die Mandarinen liegen dann noch da) |
| Zimt für Oma | Zimtstange in der Küche → Oma ansprechen |
| Spielzeugmaus für den Kater | Maus unterm Sofa → Kater Murr schläft 60 Sekunden tief und fest |
| 🐱 Streunerkatze Mimi zähmen | Fisch (bevorzugt) oder Fleisch besorgen und in Mimis Nähe am Eissee gehen – die Fütterung passiert **automatisch**, danach folgt sie dir überall hin (ohne Verdacht zu erzeugen) |

Nach dem Annehmen zeigt das **Quest-Panel (Q)** einen **Schritt-für-Schritt-Plan**, der den Weg andeutet, aber nie direkt die Lösung verrät. **Mehrere Quests gleichzeitig? Kein Problem** – nimm einfach alle an: Sie werden im Spiel als Hinweisboxen **untereinander** angezeigt (bis zu 3 sichtbar, Rest zählt zusammen), und die Leiste oben zeigt die erste aktive Quest plus „+N weitere (Q)“. Sobald eine Quest abgeschlossen ist, **verschwindet auch ihr blauer E-Interaktionskreis** an der zugehörigen Stelle.

Zwei kleine Komfort-Fixes: Die **Weihnachtseinkäufe** und der **Weihnachtsbrief** zählen als Hauptquests, und der **Weihnachtsbrief kann auch nachträglich in den Postkasten eingeworfen** werden (der Brief bleibt nach dem Versiegeln im Inventar-Flagsystem erhalten). Außerdem laufen die Bahnhofs- und Laden-NPCs (Krause & Stern) wieder **frei über ihre kompletten Routen**, statt in Ecken stehen zu bleiben.

## Items & Hotbar

Sobald du etwas findest, landet es in der **Hotbar unten** (20 Gegenständen, farbig benannt mit Emoji-Icon, Slot-Nummern-Badge):

Lichterkette 💡 · Schneeschaufel ⛏️ · Werkzeugkiste 🧰 · Lupe 🔍 · Christbaumkugel 🔴 · Weihnachtsglocke 🔔 · Kerze 🕯️ · Tannenast 🌿 · Kohle ⚫ · Weihnachtsbrief ✉️ · Siegelstempel ✒️ · Zimtstange 🥮 · Spielzeugmaus 🐭 · Mandarine 🍊 · Wunschzettel 📝 · Eiskristall ❄️ · Wollmütze 🧢 · Fisch 🐟 · Fleisch 🥩 · **Weihnachtseinkäufe 🎁**

Einsetzen per **Zahlentaste 1–9/0** oder **Klick auf den Slot** – je nach Gegenstand startet ein Minispiel, gibt einen Hinweis oder löst etwas aus.

## Musik & Sounds

- **Musik nur auf Knopfdruck** (🔊): eine ruhige, weiche **„Stille Nacht"** mit warmen Bässen und langsamen Hüllen – das Cozy-Weihnachtsabend-Gefühl, ohne nerviges Dauer-Geplätscher
- **Sound-Effekte** (automatisch): Türen knarren beim Kartenwechsel, NPCs geben Warntöne von sich, Erfolgs- und Fehlerklänge in Minispielen

## Speichern & Laden

- **💾 Speichern als Datei**: Download eines Spielstandes – ideal, um ihn **auf den USB-Stick** neben das Spiel zu legen
- **📂 Laden**: Datei wieder einlesen, wo und wann du willst
- **Autosave** läuft zusätzlich im jeweiligen Browser
- Kehrt ein geladener Spielstand sofort ins Spiel zurück (das Intro läuft nicht erneut)

## Karte (M)

- Draußen: Live-Position von **Berndt und allen NPCs** auf der Dorfkarte (inkl. Bahnhof, Gleise, Eissee, Kreisverkehr-Baum)
- **In Innenräumen: bewusst keine Live-Position** – so kannst du dich nie über irreführende Punkte wundern (z. B. vermeintlich auf den Gleisen stehen)

## Tipps & Taktiken

- **Nachts schleichen** ist fast immer sicher – tagsüber großen Bogen um die Radien machen
- **⏩ ×15** nutzen, um auf Tag 6 (Nikolaus-Nacht) oder Tag 24 (Weihnachtsmann) zu warten
- Erst **Gegenstände sammeln, dann Quests annehmen**? Egal – das rückwirkende Zählen* springt automatisch weiter
- **Tödliche S1** nie auf den Gleisen abpassen – 2-Minuten-Takt
- Mimi braucht **Fisch** (lieber!) oder Fleisch – Fisch liegt im Dorf und im Keller, Fleisch in Scheune und Kirche
- Der **stehende Zug** ist sicher – nur die schnelle rote S1 auf den Gleisen ist tödlich

## Technik

- Eine einzige HTML-Datei, reines HTML/CSS/JS, **kein Internet nötig** (nur die 3D-Datei braucht einmalig ein CDN)
- Canvas 960 × 600, läuft offline in jedem modernen Browser; Spielstand-Speicherung im Browser + Download als Datei
- Getestet mit automatisierten Headless-Tests: Intro & Dachlauf, Portale, Verdacht, Minispiele, Mimi-Fütterung, Zug & Einkäufe, Nikolaus & Weihnachtsmann, Canvas-Validierung (Kontext-Argumente) für beide 2D-Versionen
