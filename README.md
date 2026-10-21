# Geschichte Lernzettel – Geschichte erinnern

Eigenständig verständlicher Lernzettel zur Mittelalterrezeption, Geschichtskultur und zum Umgang mit deutscher Kolonialgeschichte. Aufbau nach den vorhandenen Repositories `musik-politik-lernzettel` und `politik-demografie-lernzettel`: helle Themenkarten, farbige Kapitel, kurze Lernblöcke, Sprungauswahl und Druckansicht; responsive bis zu sehr schmalen Displays.

## Lesen

`index.html` im Browser öffnen. `content.js` muss im gleichen Ordner liegen. Die Textfassung steht in [LERNZETTEL.md](LERNZETTEL.md).

## Inhalt

10 Kapitel, 54 Lernblöcke und 10 zusätzliche Prüfungsfragen mit Musterantworten. Kernwissen folgt dem Merkheft. Buchvertiefungen decken Mittelalterfeste, Medienkritik, Herkunft kolonialer Museumsobjekte und das Bremer Antikolonialdenkmal ab. Ein Methodenteil erklärt Operatoren, Materialanalyse und begründete Urteile.

## Quellen und Grenzen

- Vier bereitgestellte Merkheft-Seiten: Geschichte erinnern, Mittelalterrezeption, politische Nutzung, Geschichtskultur und koloniale Erinnerung/Straßennamen.
- Bereitgestellte Auszüge aus *Forum Geschichte – Neue Ausgabe*, S. 12–29. Buchmaterialien werden eigenständig zusammengefasst, keine Scans veröffentlicht.
- Zusätzliche Begriffserklärungen und selbst erstellte Musterantworten unterstützen das Verständnis; sie sind keine offiziellen Klausurlösungen.
- Historische Debatten werden im Stand der Materialien wiedergegeben, nicht als aktuelle Nachrichten.
- Der vollständige Prüfungsumfang und die Aufgaben der Lehrkraft sind nicht bekannt. Auswendiglernen ersetzt weder Materialanalyse noch begründete Anwendung; eine bestimmte Note ist nicht garantiert.

## Technik

Keine externen Bibliotheken, Schriftarten, Tracker oder Build-Schritte. Inhalte stehen in `content.js`, Darstellung und Navigation in `index.html`. `.nojekyll` erlaubt die direkte Bereitstellung als statische Seite. GitHub Pages kann nach Erstellung des Repositories aus `main` und dem Stammordner bereitstellen; eine Live-Veröffentlichung ist erst nach erfolgreicher Aktivierung gegeben.

## Lokal starten

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Danach im Browser `http://127.0.0.1:8765` öffnen.
