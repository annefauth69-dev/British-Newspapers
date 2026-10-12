# At the Restaurant – interaktives Rollenspiel (Englisch A2/B1)

Webanwendung für den Englischunterricht an der Berufsschule. Die Schülerinnen und Schüler
besuchen das britische Pub-Restaurant *The Red Lion*, bestellen typisch britisches Essen und
reagieren auf die Fragen des Kellners.

## Starten

`index.html` im Browser öffnen (Chrome oder Edge empfohlen). Es gibt keine Installation, keinen Server
und kein Login. Die Datei läuft auch offline und kann z. B. über Moodle/Teams verteilt werden.

## Ablauf des Rollenspiels

1. Begrüßung und Frage nach einem Tisch (mit oder ohne Reservierung)
2. Getränk bestellen, dazu Rückfrage (*still or sparkling?*, *milk and sugar?* …)
3. Vorspeise (oder keine), Hauptgericht, dazu Rückfrage (*mushy peas or garden peas?*, *beef, chicken or lamb?* …)
4. Frage nach Allergien
5. Kellner wiederholt die Bestellung
6. **Problem:** Der Kellner bringt das falsche Gericht → höflich reklamieren
7. *Is everything all right with your meal?*
8. Nachtisch (oder keiner)
9. Nach der Rechnung fragen, bezahlen (Karte oder bar), Trinkgeld
10. Verabschiedung → Auswertung mit Sternen, Rechnung und Übersicht aller Antworten (druckbar)

## Niveaus

- **A2 – Choose:** Die Lernenden wählen aus mehreren Antworten. Unhöfliche oder unpassende Antworten
  bekommen eine Rückmeldung mit Verbesserungsvorschlag. Danach dürfen sie es noch einmal versuchen.
- **B1 – Write / Speak:** freie Antworten per Tastatur oder Mikrofon (Spracherkennung in Chrome/Edge).
  Die Anwendung erkennt Gerichte, Ja/Nein, Zahlen und Bezahlarten. Sie gibt Tipps zur Höflichkeit
  (*I want* → *I'd like*). Die Lernenden können nachfragen (*What is a Scotch egg?*,
  *What do you recommend?*, *Could you repeat that?*). Nach zwei Fehlversuchen erscheinen
  Auswahlantworten als Hilfe.

## Weitere Funktionen

- Der Kellner spricht britisches Englisch (Sprachausgabe, abschaltbar, jede Zeile kann wiederholt werden)
- Deutsche Hilfe einblendbar
- Speisekarte mit Erklärungen und Bestellübersicht mit Preisen
- **Vocabulary:** Karteikarten zu allen Gerichten und eine Wortliste Englisch–Deutsch
- **Phrases:** wichtige Redemittel für Gast und Kellner und ein Warm-up-Quiz *Who says it?*

## Anpassen

Speisekarte, Rückfragen, Redemittel und Dialogschritte stehen als Daten am Anfang des
`<script>`-Blocks in `index.html` (`MENU`, `FOLLOW`, `PHRASES`, `STEPS`). Dort lassen sie sich leicht ändern.
