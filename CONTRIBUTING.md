# Mitarbeit

Diese Regeln gelten für jedes Repository von Infeed8, das keine eigene `CONTRIBUTING.md` hat.

## Vorgang

- Jede Änderung gehört zu genau einem Vorgang in Jira. Sein Schlüssel ist die ID, zum Beispiel `NEXUS-12`.

## Branches

- `main` ist geschützt und jederzeit auslieferbar. Direkte Pushes gibt es nicht.
- Je Vorgang ein Branch: `paket/<ID>-<kurzbeschreibung>`.
- Die Kurzbeschreibung ist klein geschrieben, mit Bindestrich, ohne Umlaute und höchstens fünf Wörter lang.
- Beispiel: `paket/NEXUS-12-testprojekt-anlegen`.

## Commits

- Form: `<ID>: <Gegenstand> <Verb in der Grundform>`, auf Deutsch. Beispiel: `NEXUS-12: Testprojekt anlegen`.
- Der Text darunter ist freiwillig und erklärt den Grund, nicht den Diff.
- Eine Änderung je Commit. Keine Zugangsdaten und keine Kundendaten in der Historie.
- Keine automatischen Signaturen und keine Co-Autor-Zeilen.

## Pull Requests

- Der Titel ist wie der Commit aufgebaut und beginnt mit der ID.
- Ein Vorgang je Pull Request, so klein, dass er sich in einem Zug prüfen lässt.
- Die Vorlage ausfüllen: was sich ändert, warum und wie es geprüft wurde.
- Auf `main` kommt eine Änderung nur mit grüner Pflichtprüfung und der nötigen Freigabe: keine in Einzelarbeit, eine sobald zwei Personen entwickeln.
- Merge, Squash und Rebase sind erlaubt.
- Den Branch nach dem Zusammenführen löschen.
- Den Status des Vorgangs in Jira nachführen.
