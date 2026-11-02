# Werkstatt-Katalog – öffentliche Vorschau

Eine eigenständige `index.html` zeigt drei generisch formulierte Arbeitspaketfamilien
mit Varianten und Fragen. Fassung `pilot-2026-11-02-v1`. Kein Zugriff auf eine
Auftragsverwaltung, keine Schreibfunktion in deren Datenbestand.

## Öffnen und Feedback

`index.html` herunterladen und im Browser öffnen oder nach gesonderter Freigabe
über GitHub Pages bereitstellen. Kein Build nötig. Antworten werden nach Möglichkeit
nur in diesem Browser zwischengespeichert, nicht auf GitHub gespeichert.
„Bearbeitete HTML-Datei speichern“ erzeugt eine neue Datei mit den Eingaben;
„Antworten als JSON speichern“ ist eine zusätzliche Sicherung. Downloads mit
Antworten sind vertraulich und dürfen **nicht in dieses öffentliche Repo**.

Je Paket öffnet „Rückmeldung auf GitHub prüfen“ ein vorbereitetes Issue im separaten
privaten Repository `ThorstenHalsch/werkstatt-katalog-feedback`. Erst dort bestätigen.
GitHub-Anmeldung und Zugriff erforderlich; ohne Berechtigung ist auch 404 möglich.
Lange Rückmeldungen als JSON sichern und dem privaten Fragebogen anhängen.
Keine Kundennamen, FINs, Rechnungsinhalte oder Passwörter eingeben.

## Veröffentlichung

Pages ist nicht automatisch eingerichtet. Erst nach Prüfung der Vorschau:
Settings → Pages → Deploy from a branch → main → /(root).
`.nojekyll` markiert die unverändert auszuliefernden statischen Dateien.
Pages kann eigene Deployment-Läufe anzeigen. Keine zusätzlichen Test-/Release-
Workflows einrichten; das Anwendungsrepository bleibt davon unabhängig.
Nur freigegebene Vorschläge veröffentlichen, niemals Originalexporte/Mappings.

## Datenschutz und Sicherheit

Keine extern geladenen Ressourcen, Tracker, Tokens oder GitHub-API-Schreibzugriffe.
Antworten nur als Text darstellen. Die Vorschau enthält ausschließlich manuell
zusammengestellte allgemeine Vorschläge, keine historischen Einzeltexte oder
Geschäftsdaten. Technische Vorschlagskennungen sind öffentlich lesbar, keine Secrets.
Die eingebettete Vorschlagsfassung dient der Zuordnung, nicht der Authentifizierung.
