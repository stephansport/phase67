# Vokabel-Trainer (5. Klasse, Englisch)

Vokabeltrainer nach dem 6-Phasen-Prinzip. Läuft ohne Installation: einfach `index.html` im Browser öffnen.

## So funktioniert's
- Jede Vokabel startet in **Phase 1**. Neue Wörter werden zuerst gezeigt („Neue Vokabel“), danach abgefragt.
- **Gewusst** → eine Phase weiter. Die nächste Abfrage kommt nach 1 / 2 / 5 / 10 / 30 Tagen.
- **Nicht gewusst** → zurück in Phase 1, das Wort kommt in derselben Runde nochmal.
- Nach Phase 6 ist das Wort im **Langzeitgedächtnis**.
- Bei Tippfehlern oder anderen richtigen Antworten gibt es den Knopf „Ich hatte doch recht“.

## Neue Vokabeln eintragen
- In der App unter **„+ Wörter“**, oder
- dauerhaft in `vokabeln.js` als neue Lektion (Beispiele stehen in der Datei).

Der Lernstand wird im Browser gespeichert (localStorage). Unter *Einstellungen* gibt es eine Sicherung zum Herunterladen und Laden.
