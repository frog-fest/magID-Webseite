# magID-Webseite – Arbeitsregeln

## Gemeinsame Regeln und eigenständiger Einstieg

- Zu Beginn jedes Entwicklungsauftrags einmal `../flutter-development/COMMON_RULES.md` lesen. ChatGPT liest stattdessen `COMMON_RULES.md` aus `frog-fest/flutter-development` (https://github.com/frog-fest/flutter-development). Bereits gelesene Inhalte nur bei Änderungen erneut abrufen; keine weitere Dokumentenanalyse allein deshalb.
- Bei fehlendem Zugriff kurz darauf hinweisen und nach diesen Kernregeln weiterarbeiten. Website-spezifisches Wissen bleibt im Projekt; unbekannte zentrale Ergänzungen nicht als geprüft ausgeben. Nur bei entscheidenden fehlenden Informationen nachfragen.
- Codex verwendet lokale Dateien ohne GitHub-Abgleich. ChatGPT klärt den GitHub-Ausgangsstand einmal, sofern noch nicht bestätigt; ein aktuelles Projekt-ZIP kann stattdessen Grundlage sein.
- Nur beauftragte Änderungen, keine zusätzlichen Refactorings oder Freigabeschleifen. Neueste ausdrückliche Nutzerentscheidungen gehen vor. Bestehende Änderungen schützen; keine automatischen Commits/Pushes, destruktiven Befehle oder Upgrades.
- Codex liefert lokale Dateien/Diffs, ChatGPT fertige ZIP-Änderungspakete mit vollständigen Dateien und relativen Pfaden; Löschungen nennen. Keine Hilfsskripte oder Platzhalter als Ersatz für fertige Dateien.

## Versionierung und Website

- Bei jedem Änderungsauftrag auch lokal `VERSION` erhöhen und `version_history.txt` ergänzen, auch bei Dokumentation. PATCH für Korrekturen/Dokumentation; MINOR/MAJOR nach Funktionsumfang. Reines Lesen erhöht nichts. ZIPs verwenden die Projektversion; keine Nummer wiederverwenden.
- Dies ist eine statische Website. Die Flutter-/App-Buildregeln der gemeinsamen Datei gelten hier nicht; keine `pubspec.yaml` oder Flutter-Tests anlegen.
- Bestehende HTML-/CSS-Struktur, Navigation, responsive Darstellung und relative Links erhalten. Kein Framework oder Buildsystem ohne Auftrag einführen.
- Impressum, Datenschutz, Nutzungsbedingungen und Kontaktdaten nicht nebenbei inhaltlich ändern. Nur beauftragte Inhalte bearbeiten; keine Veröffentlichung ohne Auftrag.
- Nur passende Prüfungen für geänderte Inhalte, Links und Darstellung ausführen. Bei reinen Regel-/Versionsänderungen Dokumente und Versionskonsistenz prüfen. Tatsächlichen Prüfstatus nennen.
