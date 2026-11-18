# magID-Webseite – Arbeitsregeln

## Gemeinsame Regeln und eigenständiger Einstieg

- Zu Beginn jedes Entwicklungsauftrags einmal `../flutter-development/COMMON_RULES.md` lesen. ChatGPT verwendet die im Chat oder Projekt-ZIP bereitgestellte Fassung; kein externes Nachladen von GitHub. Bereits gelesene Inhalte nur bei Änderungen erneut abrufen; keine weitere Dokumentenanalyse allein deshalb.
- Bei fehlendem Zugriff kurz darauf hinweisen und nach diesen Kernregeln weiterarbeiten. Website-spezifisches Wissen bleibt im Projekt; unbekannte zentrale Ergänzungen nicht als geprüft ausgeben. Nur bei entscheidenden fehlenden Informationen nachfragen.
- Codex lokal arbeitet in der bereitgestellten Arbeitskopie ohne GitHub-Abgleich. Für ChatGPT gilt der im Chat oder Projekt-ZIP bereitgestellte Stand als bestätigt; kein erneutes Prüfen oder Herunterladen. GitHub nur auf ausdrücklichen Auftrag lesend verwenden.
- Nur beauftragte Änderungen, keine zusätzlichen Refactorings oder Freigabeschleifen. Neueste ausdrückliche Nutzerentscheidungen gehen vor. Bestehende Änderungen schützen; keine automatischen Commits/Pushes, destruktiven Befehle oder Upgrades.
- Lieferung verbindlich nach dem Abschnitt „Liefervertrag – ChatGPT (alle Projekte)“ in `COMMON_RULES.md`: ein ZIP mit ausschließlich den geänderten Dateien und relativen Pfaden. Codex lokal liefert Dateien/Diffs, kein ZIP-Zwang. Keine Ersatzformate oder Anleitungen statt des Pakets.

## Versionierung und Website

- Bei jedem Änderungsauftrag auch lokal `VERSION` erhöhen und `version_history.txt` ergänzen, auch bei Dokumentation. PATCH für Korrekturen/Dokumentation; MINOR/MAJOR nach Funktionsumfang. Reines Lesen erhöht nichts. ZIPs verwenden die Projektversion; keine Nummer wiederverwenden.
- Dies ist eine statische Website. Die Flutter-/App-Buildregeln der gemeinsamen Datei gelten hier nicht; keine `pubspec.yaml` oder Flutter-Tests anlegen.
- Bestehende HTML-/CSS-Struktur, Navigation, responsive Darstellung und relative Links erhalten. Kein Framework oder Buildsystem ohne Auftrag einführen.
- Impressum, Datenschutz, Nutzungsbedingungen und Kontaktdaten nicht nebenbei inhaltlich ändern. Nur beauftragte Inhalte bearbeiten; keine Veröffentlichung ohne Auftrag.
- Nur passende Prüfungen für geänderte Inhalte, Links und Darstellung ausführen. Bei reinen Regel-/Versionsänderungen Dokumente und Versionskonsistenz prüfen. Tatsächlichen Prüfstatus nennen.
