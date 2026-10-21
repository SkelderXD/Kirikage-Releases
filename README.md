# Kirikage

Downloads und automatische Updates für **Kirikage** – Third-Person-Action im Koop für bis zu 4 Spieler
(in Entwicklung, aktuell Bewegung, Kamera, Lock-on und Mehrspieler-Grundgerüst).

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

- **Über Steam** (Steam läuft und ist angemeldet): Einer wählt **Spiel hosten**, die anderen **Spiele suchen** →
  **Beitreten**. Am Router muss nichts freigegeben werden. Zum Testen nutzt das Spiel Valves Test-App
  „Spacewar“ – in Steam steht deshalb „Spacewar“ als laufendes Spiel.
- **Im LAN / ohne Steam:** **Spiele suchen** findet Spiele im lokalen Netz, alternativ die IP-Adresse des Hosts
  eintragen → **Verbinden**.
- Alle brauchen dieselbe Version; Spiele mit anderer Version sind in der Liste markiert.

## Steuerung

| Aktion | Tastatur/Maus | Gamepad |
|---|---|---|
| Bewegen | W A S D | linker Stick (leicht = gehen) |
| Kamera | Maus | rechter Stick |
| Springen | Leertaste | A |
| Sprinten (halten) | Shift links | B |
| Gehen an/aus | Alt links | – |
| Ducken an/aus | Strg links oder C | linken Stick drücken |
| Lock-on an/aus | mittlere Maustaste oder Q | rechten Stick drücken |
| Ziel wechseln | Mausrad oder Maus kräftig zur Seite | rechten Stick zur Seite |

Dieses Repository enthält nur die fertigen Spieldateien, keinen Quellcode.
