# Kirikage

Downloads und automatische Updates für **Kirikage** – Third-Person-Action im Koop für bis zu 4 Spieler
(in Entwicklung, aktuell Bewegung mit Ninja-Parkour, Kamera, Lock-on, Mehrspieler-Grundgerüst und Katana-Kampf mit
Blocken, Deflect, Ausweichrolle, Todesstoß und Todesstoß aus der Luft gegen Trainingspuppen, die zum Teil
zurückschlagen; zum Ausprobieren gibt es einen Parkour-Kurs und eine Testarena).

## Installieren (nur einmal nötig)

1. Rechts unter **Releases** die neueste Version öffnen und die Datei `Kirikage-….zip` herunterladen (ca. 600 MB).
2. Die ZIP-Datei in einen eigenen Ordner entpacken, z. B. `Dokumente\Spiele\Kirikage`
   (nicht unter „Programme“ – dort kann sich das Spiel nicht selbst aktualisieren).
3. `Kirikage.exe` starten. Beim ersten Start warnt Windows eventuell
   („Der Computer wurde durch Windows geschützt“): **Weitere Informationen → Trotzdem ausführen**.
   Fragt die Windows-Firewall nach Netzwerkzugriff: für **private Netzwerke** zulassen (nötig zum Hosten).

Voraussetzungen: Windows 10/11 (64 Bit), Grafikkarte mit DirectX 12. Fehlende Laufzeitbibliotheken installiert das
Spiel beim ersten Start selbst.

## Updates

Das Spiel prüft bei jedem Start, ob es hier eine neuere Version gibt. Wenn ja, lädt es sie im Hauptmenü
herunter (Fortschritt unter dem Titel), installiert sie und startet neu. Einstellungen und Spielstände bleiben
erhalten. Während eines laufenden Spiels wird nichts geladen – erst zurück im Hauptmenü.

## Zusammen spielen

- **Über Steam** (Steam läuft und ist angemeldet): Einer wählt **Spiel hosten: …** (Parkour-Kurs oder Testarena; allein
  spielen = einfach hosten), die anderen **Spiele suchen** →
  **Beitreten**. Am Router muss nichts freigegeben werden. Zum Testen nutzt das Spiel Valves Test-App
  „Spacewar“ – in Steam steht deshalb „Spacewar“ als laufendes Spiel.
- **Im LAN / ohne Steam:** **Spiele suchen** findet Spiele im lokalen Netz, alternativ die IP-Adresse des Hosts
  eintragen → **Verbinden**.
- Alle brauchen dieselbe Version; Spiele mit anderer Version sind in der Liste markiert.

## Steuerung

| Aktion | Tastatur/Maus | Gamepad |
|---|---|---|
| Gehen | W A S D | linken Stick leicht neigen |
| Laufen | Shift + W A S D | linken Stick ganz neigen |
| Sprinten | Shift länger halten (nach 1 s Anlauf) | B halten |
| Kamera | Maus | rechter Stick |
| Springen, Doppelsprung | Leertaste | A |
| Ducken an/aus, Rutschen (beim Laufen) | Strg links oder C | linken Stick drücken |
| Lock-on an/aus (ohne Ziel: Kamera hinter die Figur) | mittlere Maustaste oder Q | rechten Stick drücken |
| Ziel wechseln | Mausrad oder Maus schnell zur Seite | rechten Stick zur Seite |
| Angriff (mehrmals = Kombo), bei wehrlosem Gegner Todesstoß | linke Maustaste | RB |
| Todesstoß aus der Luft (in der Luft bzw. an Wand oder Kante über einem Gegner) | linke Maustaste | RB |
| Blocken (halten) | rechte Maustaste | LB |
| Deflect (kurz vor dem Treffer drücken) | rechte Maustaste | LB |
| Ausweichrolle (in Bewegungsrichtung, ohne Richtung nach hinten) | Alt | X |
| Menü (mit Steuerung und Kartenwechsel) | Esc | Start |

Doppelsprung: in der Luft nochmal springen – mit Richtung ein Salto dorthin, ohne Richtung ein Rückwärtssalto.
Kampf: Treffer füllen die Haltung des Gegners; ist sie voll, ist er kurz wehrlos (roter Punkt) – dann Angriff =
Todesstoß. Blocken hält Schläge ab, kostet aber Haltung; wer die Blocktaste kurz vor dem Treffer drückt, wehrt ab
(Deflect) – der Gegner prallt zurück und verliert selbst Haltung. Wer kurz vor dem Treffer wegrollt, ist am Anfang
der Rolle unverwundbar. Wer von oben auf einen Gegner springt (Sprung, Wand, Kante) und in der Luft angreift,
stürzt sich auf ihn und tötet ihn mit einem Stich von oben. In der Testarena stehen vier Puppen, die angreifen (vom
Start aus links, Schild „ÜBUNGSKAMPF“), und vier Podeste zum Üben des Todesstoßes aus der Luft (rechts, Schild
„TODESSTOSS AUS DER LUFT“). Alle Bewegungen stehen im ESC-Menü.

Dieses Repository enthält nur die fertigen Spieldateien, keinen Quellcode.
